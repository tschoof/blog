---
layout: default
---
<div id="article-container">
<h2 class="title"><a href="{{ page.url }}">{{ page.title }}</a></h2>
<div id="post-date">{{ page.date | date: "%B %d, %Y" }} | {{  page.category  }}</div>
{{ content }}
</div>
