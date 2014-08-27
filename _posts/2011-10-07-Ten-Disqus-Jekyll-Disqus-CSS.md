---
layout: post
title: Ten - Disqus and Jekyll &amp; Disqus and CSS
date: 2011-10-07 18:40:00
category: blog
---
As you can see under [every blogpost](http://blog.timmschoof.com/archives/) and in the now updated [contact section](http://blog.timmschoof.com/contact/), I slapped the [Disqus](http://disqus.com/) comment system over this blog. As this is a barebone-slim-minimal kind of blog that's hosted accordingly, it lacks a database and everything else a comment system would require. I liked Disqus and really didn't want to manage the comments with Facebook's system. So here we are. 

**Disqus and Jekyll**  
In combination with Jekyll, the awesome static site generator, theres two things to Disqus. First, getting it to work and then fitting it into your own blog with CSS. Disqus [tells you](http://docs.disqus.com/developers/universal/) how to do that. In short, you just:

* Embed Disqus's Universal Code at the bottom of your post.md in the _layouts folder.
* Exchange your *disqus_shortname* for the example in the code. The comment system should work now. For a comment count on your index page, continue:
* Paste Disqus's [Coment count code](http://docs.disqus.com/developers/universal/) in your default.md, right before the `</body>` tag
* Put in your shortname again.
* Whereever on your index.md you want to put the articel's comment counts, you need to put a link that tells Disqus that it has to look it up for a comment count. That's `#disqus_thread`. Since we're using Jekyll, and with it YAML and Liquid and whatnot, it makes sense like this:  
`<a href="{{ post.url }}/#disqus_thread">Comments</a>`

The necessity of the slash before `#disqus_thread` depends on how you style your permalinks (consult your config.yml). My permalink style lacks *.html* or */* at the end, so for the comment count lookup to work, I needed to put it there. Cost me half a day. Kudos again to the wonderful [@talinee](https://twitter.com/talinee) who located the error in the end.  
I couldn't get the whole data-disqus-identifier thing to work, but it works fine without. As long as I don't migrate the blog, at least.

**Disqus and CSS**  
Probably it isn't helpful for anyone but me, but [here's the CSS](https://adn-uf-01.s3.amazonaws.com/adn-uf-01/Zz/5A/9R/Zz5A9RlI5V6DkIPbpgUddCpgPRqhZ-qlSirqlMVSczc?Signature=aUlFdHmNkHYC%2Fr84VtVDFMIb2Uo%3D&Expires=1367179200&AWSAccessKeyId=AKIAIKZV7DVMMUT2ECFQ&response-cache-control=public%2C%20max-age%3D7200%2C%20s-maxage%3D172800&response-content-disposition=attachment%3B%20filename%2A%3DUTF-8%27%27disqus.css) I styled Disqus with. For applying custom CSS to Disqus, just log in to it, go to [disqus.com/admin/settings/appearance/](http://disqus.com/admin/settings/appearance/) and paste yours in the Custom CSS box at the bottom.

For additional info, you can check out [my setup on github](https://github.com/tschoof/blog).
