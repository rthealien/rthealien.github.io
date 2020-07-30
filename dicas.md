---
layout: page
permalink: /dicas/
title: Dicas
---

{% assign categoria = "dicas" %}

<div class="">
	<p>Dicas publicadas por aqui.</p>
		<ul>
			{% for post in site.categories[categoria] %}
			{% assign categories = post.categories %}
			<li><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
			{% endfor %}
		</ul>	
</div>