---
layout: page
title: Sobre
permalink: /sobre/
---


<img src="/assets/sobre/eu2.jpg" class="foto_sobre" style="">

Meu nome é Rafael e sou um desenvolvedor web que passou boa parte da adolescência criando blogs para falar sobre as coisas que fazia (assistia, ouvia, jogava) e resolveu juntar um pouco desses mundos aqui no GitHub Pages só para trocar a `Postagem de Textos` pela `Commitagem de Textos`.

Não temos caixa de comentários por aqui, mas caso queira entrar em contato a melhor opção é me procurar no Twitter pelo [@rthealien] ou no Mastodon pelo [@rthealien@usal.zone].

<!-- <center>

<ul class="" style="display: inline-flex;list-style: none;">
 
  <li><a rel="me" href="https://github.com/rthealien" target="_blank" title="GitHub: rthealien"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg></a></li>
  <li><a rel="me" href="https://www.instagram.com/rthealien" target="_blank" title="Instagram: rthealien"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/minima-social-icons.svg#instagram' | relative_url }}"></use></svg></a></li>
  <li><a rel="me" href="https://www.linkedin.com/in/rthealien" target="_blank" title="Linkedin: rthealien"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg></a></li>
  <li><a rel="me" href="https://twitter.com/rthealien" target="_blank" title="Twitter: rthealien"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/minima-social-icons.svg#twitter' | relative_url }}"></use></svg></a></li>
 
</ul>
</center> -->

<div class="">
	<p><strong>Outras redes:</strong></p>
<ul> 
  <li><a rel="me" href="https://github.com/rthealien" target="_blank" title="GitHub: rthealien">GitHub</a></li>
  <li><a rel="me" href="https://www.instagram.com/rthealien" target="_blank" title="Instagram: rthealien">Instagram</a></li>
  <li><a rel="me" href="https://www.linkedin.com/in/rthealien" target="_blank" title="Linkedin: rthealien">Linkedin</a></li>
  <li><a rel="me" href="https://letterboxd.com/rthealien/" target="_blank" title="Letterboxd: rthealien">Letterboxd</a></li>
  <li><a rel="me" href="https://www.backloggd.com/u/rthealien/" target="_blank" title="Backloggd: rthealien">Backloggd</a></li>
</ul>
</div>

{% assign categoria = "blog" %}

<div class="">
	<p><strong>Textos que podem ajudar a me conhecer melhor:</strong></p>
		<ul>
			{% for post in site.categories[categoria] %}
			<li>
				<a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a> 
			</li>
			{% endfor %}
		</ul>	
</div>


<!-- ### Interesses

<div class="interesseiro">
<div class="interesses">
	<img src="/assets/sobre/controle-de-video-game.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px;">

	<h4>Jogos</h4>

	<small>Sempre fui um apaixonado por games. Os jogos me motivaram a gostar de tecnologia, aprender inglês e solucionar enigmas. Com o passar do tempo comecei a jogar bem menos, mas estou sempre atento a tudo que rola nesse mundo.</small>
</div>

<div class="interesses">
	<img src="/assets/sobre/desenvolvimento-web.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px;">
	<h4>Desenvolvimento</h4>

	<small>Minha profissão é Desenvolvedor de Sistemas e gosto muito do fato do meu dia a dia ser baseado em encontrar soluções para problemas. Estou sempre pesquisando novas formas de solução e é claro que os problemas sempre vão se aprimorando também.</small>

</div>
<div class="interesses">
	<img src="/assets/sobre/fones-de-ouvido.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px;">
	<h4>Música</h4>

	<small>Outra fator que me motivou a aprender inglês, a música sempre fez parte da minha vida. Ultimamente estava sendo deixada um pouco de escanteio por causa dos podcasts, mas é só a música que consegue te dar aquele ânimo quando você mais precisa.</small>
</div>
<div class="interesses">
	<img src="/assets/sobre/pipoca.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px;">
	<h4>Cultura Pop</h4>

	<small>Filmes, seriados e livros são coisas que vocês vão encontrar por aqui nas minhas dicas/indicações. Em algumas fases falarei sobre um tema mais do que outros, mas as coisas variam conforme a vida vai fluindo.</small>
</div>
<div class="interesses">
	<img src="/assets/sobre/cat.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px;">
	<h4>Gatos</h4>

	<small>Desde que adotei minhas gatinhas parece que eu só sei falar disso, mas é que elas são tão lindas S2. Tenho um projeto com minha esposa onde falamos também de outros bichinhos que passam pelo nosso caminho: <a href="https://www.instagram.com/miauchados/">Miauchados</a></small>
</div>
<div class="interesses">
	<img src="/assets/sobre/cat.png" style="-moz-border-radius: 5%;border-radius: 5%;width: 150px;margin: 10px; display: none;">
	<h4></h4>

	<small></small>
</div>
</div>



<br/>
<small>[créditos] dos ícones.</small> -->

[@rthealien]:https://twitter.com/rthealien
[créditos]:https://www.flaticon.com/br/autores/juicy-fish
[@rthealien@usal.zone]:https://ursal.zone/@rthealien