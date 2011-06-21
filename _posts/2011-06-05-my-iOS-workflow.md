---
layout: post
title: My current iOS 'workflow'*
published: true
category: tech
date: 2011-06-05 09:00:00
---
As you may have recognized, I'm an Ubuntu user. But I also like using Apple Hardware. This results in some special configurations and workarounds I want to present in this post. I also find it interesting to see how other people handle tasks of all kind on their devices, even with a standard setup like iOS device + OS X. Lately, a friend of mine and already-iPhone-user discovered that he **needs**<sup>1</sup> an iPad, so I want to give some advice. It takes quite some money and time to search through all the apps until you find the one you were looking for. Maybe I can help avoid some unnecessary testing on your side, too.  
Funny coincident: In the [34th](http://minimalmac.com/enough/#ep34) episode of [**enough**](http://minimalmac.com/enough), a podcast by Patrick Rhone and Myke Hurley, Myke talks about how he has set up his iDevices so that he basically doesn't have to sync them. Though he uses a Mac, his setup is very similar to mine. I strive to not having to sync either, because in order to I would have to boot windows which always ruins my day. But let's go more into detail.

# Organizing #
A long time ago, I set up a google account so I could use Google Analytics. Then, I started using Google Chrome and its nice syncing features.  
After I got my iPad and had two devices I wanted to have my contacts and calendars on, I tried the stuff Google offers in that field, too. It worked great, so contacts, calendar and mails on iPad and iPhone now sync with my Google account. That's in addition to all the awesome gmail features you may or may not know about, like that it pulls mails from every mail account you may use, labels etc.  
For best functionality with iDevices, I suggest you set up your gmail account as an (Microsoft)Exchange Server how it's described [here](http://www.cultofmac.com/how-to-set-up-push-gmail-on-your-iphoneipod-touch/16966), not as IMAP. It works like a charm. Though it dosn't happen instantaneously, new events or contacts get synced very reliably.  
On Ubuntu, all the gmail functions seamlessly integrate with evolution, even the next few days' events show up under the calendar when you click on the time in the system's panel. I don't know how well or if any of that works with Outlook, but I think Google has figured something out.  

# Texts #
**Notes**  
I came to the conclusion that notes I can search through (read: which were taken with the iPad) are more valuabe to me than notes I took with pen and paper. It certainly isn't for everyone, but I'm willing to trade having to slightly change the way I take notes for the comfort of having them all with me on the iPad and in my Dropbox<sup>2</sup>. For this purpose, I use [**Elements**](http://itunes.apple.com/us/app/elements-dropbox-powered-text/id382752422?mt=8). One of its perks is that it's able to understand and convert to [**markdown**](http://daringfireball.net/projects/markdown/), John Gruber's markup language. Don't know what that means? Me neither. It's an easy way to write down HTML, that's all you need to know. This way, I can look up all the notes I took while attending lectures. Saved my ass several times, and that's just since the iPad 2 is available.  
Great post about markdown: [Markdown is the new Word 5.1](http://forkbombr.net/markdown-new-word51/)

**Blog**  
Sadly, Elements seems to write some invisible stuff at the beginning of a text document so that the markdown-engine Jekyll (the site generator I use for this blog) uses can't handle posts written with Elements without further editing.  
So I'll have to find a better solution for this, maybe I'll switch back to Elements despite the corrupting invisible stuff, but for now I use another Dropbox-syncing text editor for Blogposts, [**Nocs**](http://itunes.apple.com/de/app/id396073482?mt=8). It really isn't that great. Writing Kit, Markdown Edit and other text editors I tried didn't please me to full extent either.  
\* **With the latest update, Elements now apparently produces jekyll-ready text files. So forget about other iOS Dropbox-enabled Editors.**

**PDFs**  
All the documents I need for my studies sit in [**GoodReader**](http://itunes.apple.com/de/app/goodreader-for-iphone/id306277111?mt=8). Mostly they are PDFs, but GoodReader also handles .doc and other formats. Of course, GoodReader syncs with Dropbox (in my case with the 'Study' folder within my Dropbox) so the files sit locally in GoodReader on the iPad and are available offline, but also always up to date.  
I don't like GoodReader that much, there are many little things that could be improved<sup>3</sup>. Sadly it's the only app that does what it does. So, if you're an iOS developer: here's an idea.

### Videos ###
Here comes the fun stuff. My setting: TV shows and movies, somehow, are available on my hard drive. From this point forward: 

**Air Video**  
With [**Air Video**](http://itunes.apple.com/de/app/air-video-watch-your-videos/id306550020?mt=8), you're able to select the tv show or movie you want to watch, and let your desktop convert and stream it directly onto your iOS device. You can also select some videos and add them to the queue so that they sit in Dropbox already converted when you want to watch them.  
I like watching the current week's episodes of HIMYM, BBT, Simpsons, 30 Rock, Dexter, South Park and Family Guy on the iPad before bed or, sometimes, when I have dinner. That's more comfortable than firing up XBMC on my desktop machine 'just' for 20 minutes of a TV show.  
The Air Video Server is available for Windows and OS X only, but it works well on Ubuntu via Wine.  
I, for my part, put the Air Video output folder in my Dropbox and make the video files a favorite in the Dropbox app on my iPad. So they are available offline. And maybe that's worth mentioning: Air Video converts a 500 mb, 20 minutes episode in HD quality to only ~160 mb and the quality is quite decent.

**Handbrake**  
Oh, this one isn't an app. [**Handbrake**](http://handbrake.fr/) is an awesome piece of software, available for every current Os. For me, it's the counterpart to Air Video. When I'm working with my desktop machine and there happens to be some video file I'm inclined to watch later on the iPad, I convert it with Handbrake. It's easy to use and even comes with presets for the iPad. The target folder, of course, is the same as the Air Video folder that sits in my Dropbox.  

**IMDb**  
The [**IMDb app**](http://itunes.apple.com/us/app/imdb-movies-tv/id342792525?mt=8) is an awesome tool for every movie nut. Which film this actor starred in, which director did this film and which other films? IMDb got all the answers. And it offers trailers.  
Often, you see an app and think 'Oh, I need this!', and afterwards use it only once. With the IMDb app,  it actually was the other way round. 

### Podcasts ###
If you listen to podcasts and own an iPhone, you should use [**Instacast**](http://itunes.apple.com/de/app/instacast/id420368235?mt=8). Oh, and subscribe to the [5by5](http://5by5.tv/)-podcasts you may be interested in. My favorites are [Hypercritical](http://5by5.tv/hypercritical), [Build and Analyze](http://5by5.tv/buildanalyze/) and [The Talk Show](http://5by5.tv/talkshow/).  
I use a portable speaker, the [**Mobi Wavemaster**](http://www.amazon.de/Wavemaster-Mobile-Speaker-System-schwarz/dp/B002MW3G78). Music and voice sound really good, and the volume it produces allows me to listen to podcasts even while I cook. Incredible battery. Top notch. I also use the wavemaster all the time with the iPad, so I don't have to deal with the 2's annoying speaker when I listen to the masterpieces that Cartman's monologues are. 

### RSS ###
RSS is **the** tool for keeping up with today's information overflow. Of course, you should use Google Reader as the tool to manage your feeds. On top of it, everyone loves [**Reeder**](http://itunes.apple.com/us/app/reeder-for-ipad/id375661689?mt=8). Why? Seamless Google Reader functions, Instapaper, twitter and mail integration, great usability. Once you've used it on the iPad, you won't need the desktop or iPhone version. Short articles I read directly in Reeder. Anything longer than 'short' I'm interested in goes to Instapaper.

### Instapaper ###
[**Instapaper**](http://itunes.apple.com/us/app/instapaper/id288545208?mt=8) is for the 'Sunday morning, having coffee, sitting on a couch' mode of reading, kind of. I'm always happy to launch Instapaper, cause there are only interesting articles in it. Via my Twitter client or browser plugin, I send articles to Instapaper and it collects them. It then offers a text-only view for distraction and ad-free reading.  
You can also like articles so your buddies can see which awesome posts you read recently, similar to Google Reader's favorite and shared item functions. 

### Twitter ###
On the iPad, I use [**Twitterriffic**](http://itunes.apple.com/us/app/twitterrific-for-twitter/id359914600?mt=8). Instapaper integration, nice interface, what's not to love?  
On the iPhone, I use [**Tweetbot**](http://itunes.apple.com/us/app/id428851691?mt=8). Great interface, smart use of gestures, love it. Can't wait for the iPad version. 

### Marvel ###
For me, more 'revolutionary' than anything regarding the big question of journalism in the digital age and the apps trying to answer that question is the way the [**Marvel**](http://itunes.apple.com/us/app/marvel-comics/id350027738?mt=8) app let's me read, nay, *experience* comics. I only read the free ones Marvel releases every month, but when I do, I'm totally sucked into it. You only get to see one frame at a time and then you swipe to the next, I find that very intense. Got me hooked onto Iron Man.

### Tools ###
What would iOS be without all the little helpers you don't even think about anymore?<sup>4</sup>

**Simplenote**  
Apple's note app is nice, but doesn't sync (at least not without mobile me), so screw it. I use [**Simplenote**][Simple], it even has a chrome web app, so your shopping list is available on your desktop machine. 

**DB Navigator**  
I live in Hamburg, Germany, so the 'Deutsche Bahn' or 'DB' is what I rely on mostly when a destination is too far away for a bike ride. They offer an awesome app for [iPhone](http://itunes.apple.com/de/app/db-navigator/id343555245?mt=8) and [iPad](http://itunes.apple.com/de/app/db-navigator-fur-ipad/id416877198?mt=8). 

**Due**  
I never will understand why Apple's clock app doesn't offer multiple timers. But since it simply doesn't, we need another app. With [**Due**](http://itunes.apple.com/de/app/id390017969?mt=8), you can have a timer for your French press, eggs and your rolls. Alarm and timer mode, Dropbox syncing, it's all there. 

**Wunderlist**  
[**Wunderlist**](http://itunes.apple.com/de/app/wunderlist/id406644151?mt=8) is a nice, simple to do app. It's not as 'professional' as, say, [**Omnifocus**](http://itunes.apple.com/us/app/omnifocus-for-iphone/id284885288?mt=8), but it's free. I really don't need all the complexity most to do apps offer, so I'm perfectly happy with Wunderlist. But if you go all professional on your to dos, I'm positive Omnifocus is the way to go. 

This was a huge one, I hope it's of use to you.

---
1. As much as one can **need** a gadget.   
2. Of course, all the documents I need and use are stored in Dropbox. Needless to say that if you don't already use Dropbox, you **need** to do so. [Sign up](http://db.tt/X3XjJMl).
3. recent documents view, animations for example, and overall look & feel
4. I literally had to look at every single app on my devices to collect the ones in this category.

[Simple]: http://itunes.apple.com/de/app/simplenote/id289429962?mt=8
