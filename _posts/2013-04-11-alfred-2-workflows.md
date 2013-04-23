---
layout: post
title: Alfred 2 and some Workflows (Updated)
date: 2013-04-11 17:15:24
category: tech
published: true
---

It's all over the Internet: [Alfred 2](http://www.alfredapp.com) is out, and you can do awesome stuff with it. The short version is that you can use Alfred for free, but you're somewhat limited. You can't use workflows, mainly. Custom, precious and powerful workflows. For those you have to buy the [Powerpack](http://www.alfredapp.com/powerpack/). I think it's worth it.

I lost a few days getting into Alfred, discovering core functions and workflows, and now it boosts my productivity to a degree I never dreamed of. It really feels like an intermediary between me and my laptop has been removed. It feels like discovering the one shortcut you never knew existed again and again. Like when you finally remove this annoying little piece of popcorn that's been stuck between your teeth.

As a German law student, for example, I regularly browse [dejure.org](http://dejure.org/) to look up provisions. With Alfred's custom web searches, I now hit the Alfred shortcut, type in ‘433 bgb’, hit return and Safari shows me the provision for a contract of purchase. Saves about 3.5 seconds for every lookup. Sum that up over the time of my studies, and I'm a considerably younger graduate.

The iTunes controls (Mini Player, they call it), the system controls (shut down, empty trash), the [1Password](https://agilebits.com/onepassword) integration, custom web searches (if you don't want to do your own workflows), clipboard management: the list is long. 

If you want to hide the OS X Spotlight icon in the menubar, since Alfred of course does everything Spotlight does, you might find [Broomstick](http://www.zibity.com/broomstick) useful.

But, of course, the workflows.

[Alfredworkflow.com](http://www.alfredworkflow.com) is a good place to look if you just want to get started with a few simple workflows, or just browse to see what they're like. The Alfred Forum also has a [corner for workflows](http://www.alfredforum.com/forum/3-share-your-workflows/). Here are [a few more suggestions](http://blog.alfredapp.com/2013/04/03/alfred-v2-workflows-a-few-of-our-favourites-so-far/) from the Alfred folks themselves. [Florian Pellet has quite a few workflows](http://florianpellet.com/alfred/) he's working on. [Simon as well](http://simonbs.dk).

## My favourite Workflows
You can tweak workflows however you like regarding modifier keys, exchanging shortcuts for keywords and the other way around etc., or even alter the scripts contained in them. It doesn't get more personalised and individual than this.

* There is a big group of ‘suggest’ workflows. Searching [Google](http://tedwise.com/2013/03/04/alfred-2-workflows/), [Amazon](http://dferg.us/amazon-suggest-workflow/), [IMDB](https://github.com/Dexwell/alfred-imdb-suggest), [piratebay](http://florianpellet.com/alfred/), [YouTube](https://github.com/simonbs/alfred-youtube-workflow) and [Wikipedia](http://www.alfredforum.com/topic/1005-wikipedia-workflow-alternate/?hl=wikipedia) with suggestions makes way more sense.  
Many of these workflows are out there in several varities, these particular ones are just my favourites. 
* [WolframAlpha](http://www.alfredforum.com/topic/655-wolframalpha-workflow/), [Leo Dictionary](https://github.com/psistorm/alfredapp) and [Urban Dictionary](https://github.com/danylokostyshyn/urbandictionary-alfred-workflow) offer inline results, directly there, in Alfred. Amazing.
* [Forecast.io workflow](https://github.com/conigs/forecastio-alfred) by [conigs](http://conigs.com/#all) – Takes forecast.io's brilliant weather data and shows you directly if you'll get home dry.
* [Reminders workflow](http://www.alfredforum.com/topic/917-reminders/) by Jack James – Lets you create reminders that go directly into Reminders.app. A bit buggy, but James is working on it, gets better every other day.
* [Open current Safari tab in Chrome](http://www.alfredforum.com/topic/533-open-current-safari-tab-in-chrome/) by runar – Does what it says, for all Flash-less Safari users out there. I was able to uninstall a Safari extension that did the same because of this simple workflow. Less clutter.
* [Domainr workflow](http://www.alfredforum.com/topic/1485-domainr-workflow/) by dingyi – Checks for availability of an URL, with different TLDs. If you're a URL buying junkie, don't get this.
* [URL to Clipboard](https://dl.dropboxusercontent.com/u/7586201/URLtoClipboard.alfredworkflow) by Michael Matochkin – Copies the URL of the current Safari Tab, which doesn't have to be active or even in the front, to the clipboard. I can't find the original source, so I uploaded it to my Dropbox.  
I also made a ‘reverse’ version of this workflow that opens a URL from the clipboard in a new Safari tab and brings it to the front. [Here](http://cl.ly/0x2O15380I3p) you go (**updated, see further down**). (I use cmd+alt+U and shift+cmd+alt+U as hotkeys, respectively)
* If you're like me and don't like having stuff in your menubar the [battery workflow](http://www.alfredforum.com/topic/1211-battery-view-summary-stats-about-your-laptop-battery/?hl=%2Bbattery+%2Bworkflow#entry6850) and the [date and time calculator](http://www.alfredforum.com/topic/1663-display-and-calculate-with-current-date-and-time/?hl=%2Bdate+%2Bcalculator) workflow come in handy.

## Themes
As far as theming goes: You might be interested in the [blur hack](http://www.alfredforum.com/topic/289-cheeky-little-transparency-blur-hack-in-b78-now-available/). [This theme](http://www.alfredforum.com/topic/1881-os-x-dock/#entry10016) goes well with it. [The forum](http://www.alfredforum.com/forum/4-v2-themes/) has more. 

**Update:** [Alphred 2](https://directory.app.net/app/191/alphred-for-alfred-2/) by [mina](https://alpha.app.net/mina/) lets you post to app.net, now with PMs, sharing of the frontmost Safari tab and more :)

## *Bigger Update, April 23*
I figured out a bit more about Alfred, but didn't want to spread it out into another post, so here we go:

The [Mac Power Users Episode on Alfred](http://macpowerusers.com/2013/04/mac-power-users-133-alfred-2/) made me aware of a few core functionalities I had missed, like the action menu. Once Alfred recognises an app, you can go to the actions menu via the right arrow key, and with another stroke, you're in its recent documents.  
If it's a folder or a file, the action menu lets you perform other actions. Here the buffer comes in, which lets you perform actions on multiple files. Going through a few documents you want to send via email is way more efficiet all of a sudden.  Powerful stuff. 

From the shownotes of that episode, I highly recommend [Tim Stringer's Screencast](http://technicallysimple.com/screencasts/alfred-2-hotkeys/) made me realise *how* easy it is to make workflows for really rudimental stuff, and *how* much sense it makes.  
At first I thought I didn't need a shortcut to launch Safari, cause it's running all the time anyway. But the shortcuts also unhide apps (and unhide if you check the right box), and that is quite handy. Hotkeys for folders, and searches from selection are also quite nifty. Tim takes his time in the Screencast, but it's worth it.

I discovered a few more ‘top notch’ workflows

* [EggTimer](http://geekzone.philosophicalzombie.net/post/45984228801/eggtimer2) is very nice, does what it says.
* [Skype Call](http://guiguan.github.io/Skype-Call/) is quite amazing, lets you call phone numers or skype contacts from Alfred, in a very fast manner.

I updated the above mentioned [URL to Safari Tab Workflow](http://cl.ly/0x2O15380I3p) from a crappy script to built-in functions, so that it actually only works with URLs.

Finally, my global ‘[New Byword Document](http://cl.ly/1E390g2r3q0d)’ workflow is in shareable shape. It should work in every situation, with Byword running or not. Also shouldn't be too hard to edit it to fit the texteditor of your choice.