---
layout: post
title: Como cortar vídeos no Linux?
author: rthealien
summary: Texto sobre como aprendi a cortar vídeos pelo terminal do Linux
categories: ["TIL"]
---

**Problema**

Tinha acabado de baixar um show que foi transmitido em uma *grande rede social de vídeos* e percebi que tinha muito conteúdo que não precisava antes e depois da parte musical.

Nunca nem editei vídeos na minha vida, então fui atrás de uma forma de fazer isso com o mínimo esforço possível (lembrando que o esforço pode ser algo relativo nesse caso).

**Solução?** ([Medium])

Tenho usado o linux como sistema operacional principal no meu dia a dia e nas minhas pesquisa descobri que é bem tranquilo fazer esse corte simples utilizando a biblioteca FFmpeg através do terminal (aquela tela preta com letras que te faz parecer um hacker). 

No meu caso a biblioteca já até estava instalada, então foi só utilizar o comando abaixo no terminal:

```
ffmpeg -i VIDEO_ORIGINAL.mp4 -ss 00:01:30 -to 01:03:41 -c copy VIDEO_CORTADO.mp4
```

Note que neste exemplo ele vai cortar o vídeo do tempo 1 minuto e 30 segundos até 1 hora 3 minutos e 41 segundos do vídeo original e criar um novo arquivo com o nome VIDEO_CORTADO.mp4 

[Medium]:https://byteshiva.medium.com/how-to-cut-videos-in-linux-7fcc95c36a46
