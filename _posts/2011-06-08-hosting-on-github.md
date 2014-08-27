---
layout: post
title: Five - Hosting on github
date: 2011-06-08 16:30:00
category: blog
published: true
---
Git is a revision control system. It manages changes to documents or any other file. To be honest, that's the most I am currently able to understand of it. But that doesn't hurt, this isn't about git.

The often so-called best feature of git is [**github**](www.github.com), a hosting service for people who use git. You can look at other people's work, share projects (they're called repositories), fork repositories<sup>1</sup> and so on. Github is free, and you can even host web pages on it, which is really awesome. Especially for people who use Jekyll for their blog, because github runs it for you. You just need to push a new article to your blog's repository and the rest is taken care of.  
Of course, you can also use custom domains. All of that is described [here](http://pages.github.com/).

<<<<<<< HEAD
### What I had to do ###
=======
## What I had to do ##
>>>>>>> gh-pages
At first, I made timmschoof.com point at tschoof.github.com and added a CNAME file to the repo, all of which worked like a charm. But then my blog setup caused me some headache because of its blog. subdomain. Without a redirect from blog.timmschoof.com to tschoof.github.com/blog, all the internal links wouldn't work, of course. But I thought they would until I recognized that the previously configured redirect of the top level domain made it impossible.<sup>2</sup> After a few hours I recognized that I'd need a CNAME file in the blog repository, too.  
Of course this alone didn't do the trick. I had to wait some very uncomfortable 24-48 hours of uncertainty during which this blog lacked the CSS file, all the pictures and working internal links.

**Ha**, no wait I didn't, I just was too stupid. I first tried to make the subdomain blog.timmschoof.com point to tschoof.github.com/blog. Somehow that didn't work, I had to change the A-Record-IP for blog.timmschoof.com just like I had for timmschoof.com. The github tutorial tells you to create a CNAME record pointing to the domain you like (in my case that would've been tschoof.github.com/blog) but that didn't work for me, my webspace provider wouldn't let me. However, it accepted github's IP, just like it did before. More experience or the right question to the right people could've saved me 3 hours. 

But hey, that's how you *get* experience, I guess. And now this baby's completely hosted on github, which I find very compelling because of the easy deployment (and no monthly costs for webspace). Let's see how long git's free 300Mb suffocate.

---
<<<<<<< HEAD
=======
<br>
>>>>>>> gh-pages
1. It's recommended that you rip off other people's work.
2. Well, that's what **I** think happened. If I'm wrong and you know what really happened, please give me a shout. 
