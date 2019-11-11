---
layout: post
title: "Fuji, Blinkies and Everything in between"
date: 2019-11-11 22:15
category: photography
published: true
---


This blog post consists of two parts: In the first, I explain a phenomenon about a feature that is important to understand when shooting raw with a mirrorless (or a DSLR when used in live view) camera. In the second, I point out what I find to be huge problems with Fuji's implementation of said feature – in several ways.

## Part 1: Why Blinkies are Wrong

In my [previous post](https://blog.timmschoof.com/2019/09/26/xh1-em10-features/), I talked about highlight warnings, also known as "blinkies". What I didn't talk about there was that blinkies are wrong, most of the time. 

Here's why: When you review pictures in-camera, it shows you a jpg generated from the raw file. This jpg has less dynamic range than the underlying raw data, et voilá!

Therefore, part of getting to know your camera is getting a feeling for how much leeway there generally is, so that when you're out shooting, you know when you'll *actually* have lost detail in your file. Of course, this becomes especially relevant when using the technique of ["ETTR", exposing to the right](https://en.wikipedia.org/wiki/Exposing_to_the_right).

## Part 2: Fuji and Blinkies

<p></p>
### The jpg Problem

Now, what's special about this with Fuji? As I said, blinkies and histogram are derived from a jpg. Well, Fuji is big in the game of fabulous (from what I hear) jpg files *sooc* – straight out of camera. And that's great, except for in one aspect:

A jpg that is intended to be a final photo is a fundamentally different *thing* than a raw file with the highest possible dynamic range, or even a jpg file approximating the same. A final picture may have... contrast. Or intense colors. Therefore, it's not at all suitable to be the base for a feature that is intended to show the limits of a file's dynamic range. The two goals of showing a final picture and a file's dynamic range are at odds with each other. That's why Fuji's focus on jpg works out to be a disadvantage for the raw shooter in this instance.

So, what's the solution? Well, there is none. But there's a hack: A jpg look that is as "flat", as little "opinionated" as possible. Eterna is a Fuji film profile intended for video use very flat and can be configured to be even flatter, so it's very well suited for the inclined raw shooter's needs in this instance. With this, the images you review in-camera are the best representation of a raw file Fuji's current system/philosophy allows for.

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/eterna.jpg"></a><br>Recommended "film simulation" setup for raw shooters</p>

Check out this [dpreview forum thread](https://www.dpreview.com/forums/thread/4325169) for some more Fuji-specific talk on this.

### The EVF Problem vs. "Natural Live View"

But there's one more thing: Before, I was a bit imprecise and only talked about reviewing pictures on the back of the camera, completely omitting that you gotta be looking at something *while shooting* as well! The EVF/back screen are showing video feeds. To a close approximation they're showing something like jpgs as well, just so many per second it becomes a video. So the same rules apply.

Talking about Fuji specifically though, there's good news in this regard: There's a feature called "[Natural Live View](http://fujifilm-dsc.com/en/manual/x-h1/menu_setup/screen_set-up/index.html#natural_live_view)". It takes the "film look" configuration out of the equation and actually gives you an even flatter look/profile/whatever-you-wanna-call-it for operating the camera. It still shows the effects of exposure correction (and everything else would be really dumb), so it's a really great feature. 

With this enabled and the above mentioned Eterna-configuration, you're good to go.

### The Contradiction between EVF and Playback-jpg

Sadly the praise ends here, because there's already a big problem. There's inconsistency between how a scene is represented blinkies-wise live in the EVF, and in a Playback-jpg. 

Which means the camera contradicts itself. Also: You can't be completely sure that the light just changed between you pressing the shutter release button and the camera taking the exposure. For all you know, the moment you saw in the "Natural Live View"-EVF/back screen has gone by, and the blinked-to-death (I'm exaggerating) playback-jpg is all you're left with. Example:

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/evflive.jpg"></a><br>Scene viewed through the back screen</p>

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/jpgpreview.jpg"></a><br>Same, "exposed" scene as playback-jpg</p>

So, which one is "more right"? I'm sure this varies from scene to scene, but here's this example scene in Lightroom.

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/lostdetail.jpg"></a><br>Tons of lost detail showing in Lightroom</p>

As you can see, It's bad. The playback-jpg was "more right". There's only a little less detail lost than the playback-jpg indicated, and way more than the view in the EVF/back screen led us to believe. As a general rule, the raw file in the end will retain *more* detail than the playback-jpg and not less, but that's obvious.  
In case you're tripped up by "ISOA1 12800" showing in the upper grab from the back screen, that's something I [already talked about](https://blog.timmschoof.com/2019/09/26/xh1-em10-features/).

### It's even worse

There's *even more* – I'm sorry. Between EVF and playback-jpg, there's a third... "opinion". With Fuji cameras, they stop down and do some amount of actual metering towards taking the picture upon half-press of the shutter relasse button, [as I have already complained about, also in my previous post](https://blog.timmschoof.com/2019/09/26/xh1-em10-features/). At that point, the metering – or at least the blinkies display – goes crazy. Or becomes more accurate? Who knows? It's all up in the air. 

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/halfpress.gif"></a><br>In some situations, the blinkies increase in area on half-press of the shutter</p>

To make matters even worse: In between the blackouts that are caused by the shutter when taking a photo, the camera shows the scene, and takes *another* run on guessing how much of the scene is overexposed. Shown in frame 3.

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/betweenblackouts.jpg"></a><br>Just another instance of inconsistent metering</p>

I don't blame you if you lost count. We're up to *four* differing interpretations metering/blinkies-wise of a given scene (chronological order):

1. EVF/back screen
2. EVF/back screen upon half-press
3. In between blackouts
4. jpg in playback

... what the heck?


### Another Example

For illustration purposes, here's two more real-world examples.

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/shot_a_back.jpg"></a><br>Shot A as a playback-jpg from the back of the camera. Note the (circled) black blinkies indicating the amount of lost detail.</p>

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/shot_b_back.jpg"></a><br>Shot B as a playback-jpg from the back of the camera. Note the (circled) black blinkies indicating the amount of lost detail.</p>

Shot A I had corrected down so that upon *half-press* I didn't get significant blinkies. Then I decided to be stubborn, trust the metering just looking through the EVF and take shot B. Just to have an idea of the scale, as the EV+/- indicator... indicates, these two exposures are 1 stop apart.

(by how much) Was my trust betrayed? Let's find out in Lightroom!

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/shot_a_lr.jpg"></a><br>Shot A in Lightroom</p>

<p class="pic"><a href="URL"><img src="http://blog.timmschoof.com/images/shot_b_lr.jpg"></a><br>Shot B in Lightroom</p>

It's not easy to see only looking at shot B, but in direct comparison with shot A, there's some lost detail, especially on the side of the boat. Zoomed in, the tree's small branches also look very fuzzy, and there's blue sky in the whole area behind the tree, no solid white like it shows in shot B. My trust was betrayed by ~ 1 stop, as the playback-jpgs did indicate.

So, based upon this example, I'd mentally "throw away" the blinkies displayed during just looking through the EVF, and only pay attention to the ones displayed after half-press, and with them overshoot +1/3 to +2/3 EV I guess? Or do the same just based upon the playback-jpg, if you miss the feeling of using an old-school DSLR. I, for one, didn't go mirrorless for having to go back to playback in order to know how my pictures turned out – yes, *like an animal*.
That's workable, but I still don't appreciate the inconsistency. If the camera can only display accurate-ish measurements after half-press, then don't bother with blinkies before!

## Conclusion

Of course, this doesn't prevent anyone from taking any conceivable picture, and I'm not arguing that. You have to be pretty oblivious to not think twice about losing detail in a high-contrast scene. Also, this phenomenon becomes more extreme with more exposure compensation as well as contrast in the scene (that's my recollection, I didn't do explicit test on it, though).

That being said, I don't get why in this somewhat mature age of digital photography, an accurate overexposure warning is not on Fuji's (or any manufacturer's) radar. The "Natural Live View" feature seems to indicate that it is to some extent, but the utter oversight in every other aspect contradicts this.

What really, really bugs me is the increase of blinkies upon half-press, because it makes the camera feel unreliable to me. And this is not limited to me taking a picture of a lamp in the dark with exposure compensation +4, but happens in absolutely normal everyday situations with elevated contrast, as the shot A/shot B example shows.

My old Olympus E-M10, while being a *little* inconsistent between EVF and preview as well in a quick test, doesn't show this (weird) behaviour at all.

I could accept this if there was **a)** less variation and **b)** one of 'em was consistently more accurate. **a)** is a minus, and during my test done for this post, I found no indication of **b)** either. 

Thank you for reading/skimming this far. Have you encountered the same problem? How do you deal with it? Most importantly: Was I unclear with anything? Any [feedback](https://timmschoof.com/) is very welcome :) Especially about whatever happens or is the reasoning behind the behaviour upon half-press with Fuji cameras. Thank you!