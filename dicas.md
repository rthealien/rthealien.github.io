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
			<li>
				<a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a> 
					{% for cat in post.categories %}
						{% if cat == 'dicas' %}
						{% else %}
							<span class="badge">{{cat}}</span>
						{% endif %}
					{% endfor %}
				</li>
			{% endfor %}
		</ul>	
</div>