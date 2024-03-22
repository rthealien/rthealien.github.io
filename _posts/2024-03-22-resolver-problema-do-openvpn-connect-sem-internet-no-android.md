---
layout: post
title: Resolver problema do OpenVPN Connect sem internet no Android
author: rthealien
summary: Como consegui fazer a internet usar junto com a VPN
categories: ["TIL"]
---

**Problema**

Volta e meia preciso acessar o computador do meu trabalho remotamente utilizando uma VPN. 

Quando comecei, instalei no Windows e tudo funcionou normalmente. Depois migrei para o Linux e tive problemas para acessar a internet enquanto a VPN estava conectada, mas consegui resolver através das telas de configuração do próprio sistema.

Recentemente eu adquiri um tablet e durante uma urgência precisei fazer o mesmo tipo de aceso, mas ao instalar e configurar o OpenVPN Connect cheguei ao mesmo problema enfrentado no Linux, mas dessa vez sem encontrar uma forma de resolver através das opções do aplicativo.

**Solução?** ([severfault](https://serverfault.com/questions/648118/openvpn-not-default-gateway-for-all-traffic))

Depois de um longo tempo pesquisando que era uma questão de redirecionamento do Gateway e que existe uma opção para fazer ele cuidar disso do jeito que eu precisava e que apesar de não ter encontrado essa opção no aplicativo era possível resolver o problema alterando o arquivo de configuração da VPN.

Basicamente para configurar tudo eu preciso de 3 arquivos:
- Um arquivo de configuração com a extensão .ovpn: é aqui que ficam os parâmetros para realizar a conexão, como o tipo de protocolo utilizado, endereços, tipo de autenticação, etc
- Uma chave privada: para segurança da conexão
- Um certificado: para autenticação entre a VPN

A solução do problema se deu basicamente inserindo a linha abaixo no final do arquivo de configuração .ovpn (pode mandar abrir no bloco de notas)

```
redirect-gateway autolocal
```