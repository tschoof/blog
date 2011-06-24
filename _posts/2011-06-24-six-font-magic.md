---
layout: post
title: Six - Font Magic
date: 2011-06-24 23:30:00
category: blog
published: true
---
I had no idea! I was sabotaging my minimalistic approach towards this blog entirely by using the Ubuntu font all wrong.  
I implemented it via @font-face and had **nothing** but problems with getting f#ing Firefox to display it correctly. Yesterday, I spent several hours and finally got it fixed. The joy didn't las long: Since December of 2010, the Ubuntu font is available via the Google Font API, and I just discovered today that's a good thing. What did I do all the time instead of [using it](http://www.google.com/webfonts/family?family=Ubuntu&subset=latin#code)? Let my visitors load some nice 1,5mb of font data. Yay.  
Loading a font equals loading a font you might think: *Google has to load it too, stupid!* -  Wrong. Well, yes but: I don't know whether github (where I'm hosted) slowed it all down, being free and and offering correspondent performance, but sure is: Now, with the Google Font API, this site loads amazingly fast. 

Literally, one new line of code and 3 or 4 adjustments in my stylesheet was all it took. The latter solely due to my poor CSS skills and huge amount of [technological debt](http://5by5.tv/buildanalyze/15) I created. In case this is news to you - Everything necessary is to find here: [font.ubuntu.com/web](http://font.ubuntu.com/web/).
