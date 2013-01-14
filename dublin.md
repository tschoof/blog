---
layout: default
title: Dublin
permalink: /dublin/
---
<h1>Category Dublin</h1>
	
{% for post in site.categories.dublin %}
<li>{{ post.date | date_to_string }} <a  href="{{ post.url }}">{{ post.title }}</a></li><br>
{% endfor %}
</ul>