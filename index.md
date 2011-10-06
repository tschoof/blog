---
layout: default
title: Home
---
<div id="article">
{% for post in site.posts limit: 6 %}
<h2 class="title"><a href="{{ post.url }}#disqus_thread">{{ post.title }}</a></h2>
<div id="post-date">{{ post.date |date: "%B %d, %Y" }} | {{  post.category  }}</div>
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
<!-- DISQUS -->
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    var disqus_shortname = 'blogtimmschoof'; // required: replace example with your forum shortname

    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function () {
        var s = document.createElement('script'); s.async = true;
        s.type = 'text/javascript';
        s.src = 'http://' + disqus_shortname + '.disqus.com/count.js';
        (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
    }());
</script>
