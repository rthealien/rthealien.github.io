---
layout: page
permalink: /alien-awards/
title: Alien Awards
---

{% assign categoria = "alien-award" %}

<div class="">
	<p>Todos os anos eu tento listar as 3 melhores coisas que ouvi, assisti, joguei e li. Já fiz essa lista em vários lugares diferentes e começo a fazer por aqui, agora, em 2020.</p>
	<p>Com o tempo, espero conseguir recuperar as listagens dos anos anteriores.</p>
		<ul>
			{% for post in site.categories[categoria] %}
			{% assign categories = post.categories %}
			<li><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
			{% endfor %}
		</ul>	
</div>