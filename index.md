---
layout: default
title: Home
---
<div id="article">
{% for post in site.posts limit: 6 %}
<h2 class="title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
<div id="post-date">{{ post.date |date: "%B %d, %Y" }} | {{  post.category  }} | <a href="{{ post.url }}#disqus_thread" data-disqus-identifier="{{ post.title }}">Comments</a></div>
{{ post.content }}
<hr style="
			border-width: 0px; 
			border-top: 1px solid #BDBDBD; 
			margin-top: 28px;
			margin-bottom: 40px; 
			width: 670px;
			margin-right: 20px;
			text-align: left; ">
{% endfor %}
</div>

