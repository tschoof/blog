---
layout: post
title: AirPlay in Totme
category: tech
published: true
date: 2011-06-19 15:20:00
---
A plug-in for Totem (Ubuntu's standard movie player), [released in January](http://www.omgubuntu.co.uk/2011/01/airplay-video-playback-comes-to-totem/), allows to stream video via Apple's AirPlay. I tried it immediately, and it worked. With the release of Ubuntu 11.04, it stopped working. The plugin refused to start with the error message
                     Unable to activate plugin AirPlay Support

Then, I found the solution, a comment on the very same article I linked to above. [Paul Kehle](https://twitter.com/#!/pgkehle) says, once you install 'avahi-discover', it works. Run 
                     sudo apt-get install avahi-discover
                     
and you're fine. I just wanted to share this because I'd given up hope and just came across it by accident. 
