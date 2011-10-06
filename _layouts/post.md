---
layout: default
---
<div id="article-container">
<h2 class="title">{{ page.title }}</h2>
<div id="post-date">{{ page.date | date: "%B %d, %Y" }} | {{  page.category  }}</div>
{{ content }}
</div>
