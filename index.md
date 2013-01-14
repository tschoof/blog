---
layout: default
title: Home
---
<div id="article">
<!-- {% for post in site.posts limit: 8 %} -->
<h2 class="title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
<div id="post-date">{{ post.date |date: "%B %d, %Y" }} | {{  post.category  }} | <a href="{{ post.url }}/#disqus_thread">comments coming soon</a></div>
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

<div class="pagination">
<ul>
{% if paginator.previous_page %}
{% if paginator.previous_page == 1 %}
<li class="disabled"><a href="#">&laquo;</a></li>
{% else %}
<li><a href="/page{{paginator.previous_page}}">&laquo;</a></li>
{% endif %}
{% endif %}
 
{% if paginator.page == 1 %}
<li class="disabled"><a href="#">1</a></li>
{% else %}
<li><a href="/">1</a></li>
{% endif %}
 
{% for count in (2..paginator.total_pages) %}
<li class="page">
{% if count == paginator.page %}
<li class="active"><a href="#">{{count}}</a></li>
{% else %}
<li><a href="/page{{count}}">{{count}}</a></li>
{% endif %}
{% endfor %}
 
{% if paginator.next_page %}
<li class="active"><a href="/page{{paginator.next_page}}">&raquo;</a></li>
{% else %}
<li class="disabled"><a href="#">&raquo;</a></li>
{% endif %}
</ul>
</div>