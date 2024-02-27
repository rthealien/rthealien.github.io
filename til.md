---
layout: page
permalink: /descobri-hoje/
title: Descobri hoje
---

{% assign categoria = "TIL" %}

<div class="">
	<p>Fiquei encantado quando descobri o conceito de <strong>TIL</strong> (Today I Learned/Aprendi Hoje) internet afora. Utilizarei o blog como uma forma de deixar as pequenas coisas que aprendi ou precisei pesquisar no dia a dia para concluir uma tarefa ou simplesmente para conseguir colocar um emoji no calendário.</p>
	<p>Se esse conhecimento já me ajudou uma vez pode me ajudar de novo no futuro ou melhor ainda, pode ajudar outras pessoas.</p>
		<ul>
			{% for post in site.categories[categoria] %}
			{% assign categories = post.categories %}
			{%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
			<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date: date_format }}: {{post.title}}</a></li>
			{% endfor %}
		</ul>	
</div>