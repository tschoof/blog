---
layout: default
title: Archives
permalink: /archives/
---
<h1 class="page">Archives</h1>
<div id="post_links">
	<ul>
	{% for post in site.posts %}
	<li><span>{{ post.date | date_to_string }}</span> <a  href="{{ post.url }}">{{ post.title }}</a></li><br>
	{% endfor %}
	</ul>
</div>
