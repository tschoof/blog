---
layout: default
title: Dublin
permalink: /categories/dublin/
---
<h1>Category: Dublin</h1>

	<ul>
	{% for post in site.categories.dublin %}
	<li><span>{{ post.date | date_to_string }}</span> <a  href="{{ post.url }}">{{ post.title }}</a></li><br>
	{% endfor %}
	</ul>
</div>