---
layout: default
---
<div id="article-container">
<h2 class="title"><a href="{{ page.url }}">{{ page.title }}</a></h2>
<span class="post-date">{{ page.date | date: "%B %d, %Y" }} | {{  page.category  }} | <a href="{{ page.url }}/#disqus_thread">comments coming soon</a></span>
{{ content }}
</div>
<!-- DISQUS -->
<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    var disqus_shortname = 'blogtimmschoof'; // required: replace example with your forum shortname
    
    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = 'http://' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
<a href="http://disqus.com" class="dsq-brlink">blog comments powered by <span class="logo-disqus">Disqus</span></a>
