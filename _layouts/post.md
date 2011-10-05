---
layout: default
---
<div id="article-container">
<h2 class="title">{{ page.title }}</h2>
<div id="post-date">posted on {{ page.date | date_to_string" }} in {{  page.category  }}</div>
{{ content }}
</div>
