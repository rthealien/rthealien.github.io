---
layout: post
title: Volume do microfone abaixando automaticamente durante vídeo chamada
author: rthealien
summary: "Texto explicando como descobri uma forma de desabilitar o ajuste de volume do microfone durante chamadas"
categories: ["TIL"]
---

**Problema**

Estava fazendo uma reunião pelo Google Meet usando o Vivaldi como navegador no meu Pop!OS e percebi que as pessoas estavam com dificuldade de me ouvir.

Ao observar as configurações notei que o volume do microfone estava muito baixo, então aumentei e consegui concluir minha fala.

O mesmo aconteceu nas outras 3 vezes que tentei falar e foi nesse momento que percebi que alguma coisa estava fazendo o volume do microfone se ajustar automaticamente.

**Solução?** ([Reddit])

Com uma breve pesquisa no Google, encontrei uma conversa no Reddit em que um usuário relata o mesmo problema que o meu e alguém cita que os navegadores baseados no Chromium tinham um ajuste automático de volume.

Encontrei então um parâmetro para desabilitar isso no Vivaldi, digitando `vivaldi://flags` na barra de endereço do navegador, desabilitando a opção: **Allow WebRTC to adjust the input volume.** e reiniciando o navegador.

Isso resolveu meu problema, mas não sei exatamente porque esse ponto só me incomodou hoje, já que faço reuniões usando esse navegador faz muito tempo. Pode ter sido o calor e um monte de ventiladores barulhentos apontados para mim e o microfone, mas fica a dica para quem precisar.


[Reddit]:https://www.reddit.com/r/pop_os/comments/mr31ug/comment/lixmg83/
