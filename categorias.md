---
layout: page
permalink: /categorias/
title: Categorias
---

<div class="listagem-posts">
	<p>Todos os registros do blog separados por categorias.</p>
	{% for category in site.categories %}
		{% capture category_name %}{{ category | first }}{% endcapture %}

		<h2 id="{{ category_name | slugize }}" class="category-head">#{{ category_name }}</h2>
		<ul>
			{% for post in site.categories[category_name] %}
			<li><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
			{% endfor %}
		</ul>

	{% endfor %}
</div>