---
layout: post
title: "Como fazer para voltar do congelamento de tela no PopOS 22.04?"
author: rthealien
summary: "Resolvendo um problema que me fazia reiniciar o computador sempre que acontecia mesmo sem conseguir descobrir o que causava a situação."
categories: ["TIL"]
---

**Problema**

Essa instalação do PopOS 22.04 no meu notebook tem sido minha experiência mais estável até o momento com o Linux, já são 2 anos e alguns meses sem maiores problemas, mas volta e meia sem nada que eu tenha conseguido identificar como causa todas as interações gráficas ficavam lentas até chegarem ao ponto de travar e não responderem mais.

Se tiver um vídeo ou música rodando ele continua sem problemas, mas não é possível interagir com mais nada. Não consigo abrir novos programas, maximizar ou minimizar janelas, até mesmo pausar/passar o vídeo que está rodando fica impossível. Acabava precisando reiniciar para conseguir voltar a fazer minhas coisas.

Não é algo que acontece tantas vezes, mas o problema maior é justamente não saber o que causa. E se acontece quando estou no meio de alguma tarefa importante/urgente?

**Solução?** [Reddit]

Pesquisei bastante, mas não consegui descobrir a causa do problema, logo não terei uma solução aqui. Mas encontrei uma forma de fazer as coisas voltarem a funcionar sem que eu precise reiniciar o PC, ou seja, sem correr o risco de perder o progresso do que estava fazendo!

O passo a passo dos comandos vai fazer a gente usar o terminal, mas não se assuste! É só seguir os passos que vai dar tudo certo. Se não der, aí é sugiro reiniciar o PC e voltar a buscar uma solução na internet, afinal se chegou até aqui vai conseguir encontrar mais opções pela web.

- Quando tudo travar, pressione as teclas ```Ctrl+Alt+F3``` e você vai abrir uma tela do terminal.
- Faça o login utilizando o nome do seu usuário e a senha do mesmo (a mesma que você usa para logar)
- Quando estiver logado digite o comando ```killall -3 gnome-shell``` para fechar e reiniciar o ambiente gráfico
- Então é hora de voltar para o modo gráfico utilizando as teclas ```Ctrl+Alt+F1```
- Agora é só logar novamente, esperar uns segundos para tudo carregar novamente e pronto, pode continuar seu trabalho.


[Reddit]:https://www.reddit.com/r/pop_os/comments/o6ak72/i_just_installed_popos_and_random_freezes_keep/
