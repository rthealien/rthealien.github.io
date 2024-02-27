---
layout: page
permalink: /categorias/
title: Categorias
---


<div class="">
	<p>Todos os registros do blog separados por categorias.</p>
	{% for category in site.categories | sort  %}
		{% capture category_name %}{{ category | first }}{% endcapture %}
	    {% if category_name == 'dicas' %}
		{% else %}

		<h2 id="{{ category_name | slugize }}" class="category-head">#{{ category_name }}</h2>
		<ul>
			{% for post in site.categories[category_name] %}
			<li><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
			{% endfor %}
		</ul>
		
		{% endif %}

	{% endfor %}
</div>