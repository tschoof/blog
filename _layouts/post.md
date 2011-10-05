---
layout: default
---
<div id="article-container">
<h2 class="title">{{ page.title }}</h2>
<div id="post-date">Posted on {{ page.date | date_to_string" }} in {{  category  }}</div>
{{ content }}
</div>
