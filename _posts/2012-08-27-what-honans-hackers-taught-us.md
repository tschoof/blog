---
layout: post
title: What Mat Honan&#39;s Hackers taught us
date: 2012-08-27 20:12:16
category: tech
published: true
---

You may have heard of Mat Honan's case. [He got hacked pretty bad](http://www.wired.com/gadgetlab/2012/08/apple-amazon-mat-honan-hacking/all/). In the end, it was mostly the fault of Amazon's and Apple's crappy policies. But it would be short-sighted not to rethink your current setup. Just let me recap what happened to Mat.

The hackers wanted his Twitter Account. They got the link to his personal website on his Twitter profile. On his personal website, they found his Gmail address. On the [Google Account Recovery pagge](https://www.google.com/accounts/recovery/), they saw that his (partially displayed) recovery email address was an apple-run @me.com address. Basically, the rest is Apple's and Amazon's fault. They got access to his Amazon account, got the last four digits of the credit card and used that information to get into his Apple ID. The email address associated with it was the Google Account Recovery address mentioned above, so we've come full circle. 

## Countermeasures
I was disappointed with most articles claiming to be a step-by-step guide on how to prevent this from happening to you. So here's my two cents.  
The answer (of course) can't be not to have your website displayed on the twitter profile page or to use different names on every platform.  
Amazon and Apple have changed the policies which enabled Honan's hackers to do what they did. But that doesn't mean you can relax. There are other ways, and other service providers may have crappy policies in place.

So, I basically recommend to do what [Lifehacker suggests](http://lifehacker.com/5932501/strong-passwords-arent-enough-how-to-to-ensure-the-apple-and-amazon-exploit-never-happens-to-you). Like/plus this:

* Use strong passwords. So, use [1Password](https://agilebits.com/onepassword) or another password software.  
Yeah, everything depends on that one password then. But what's the alternative? I definitely chose one monster password with ultra complex individual passwords for every service behind it over one or two mediocre passwords that are worth nothing once **one** service is hacked. 
* Use Two-Factor-Authentication with every Service that offers it. Currently: [Google](http://support.google.com/accounts/bin/answer.py?hl=en&amp;answer=180744), [Facebook](http://lifehacker.com/5801597/set-up-two+factor-authentication-in-facebook-for-better-security), [Dropbox](https://www.dropbox.com/help/363/en).
* [Make the Google Recovery Mail Address](http://support.google.com/mail/bin/answer.py?hl=de&amp;answer=6566) (Since you're reading this, I assume you're a nerd and use Gmail) an address that is *not* an Apple-run one, or even better: one not even associated with an Apple ID. That way, if your Google Account gets hacked despite your efforts, the hacker can't remote wipe your Apple devices.  
It also shouldn't be easy to guess, since Google displays a few characters of the Recovery Mail Address (like *m••••n@me••om*, in Mat Honan's case). But even the best hacker in the world can't hack something he can't target. I created a new email address on a different service that is not related to anything else. You can remember that address, print out the password and keep it at your grandparent's place. 
* Create a new Apple ID and use it just for iCloud. Again: An email address that no one knows about is hard to target. And iCloud with its Remote Wipe feature can save you, but also destroy you, like in Honan's case. If you disassociate your iCloud-specific Apple ID from your other one, it's not used that often, you just have to enable it once on every device. It's another Apple ID than the one you use (and that 's displayed) every time you buy an App via one of the App Stores. Security win.

The above is all cloud, password, account and Internet stuff. Of course, you should never leave your laptop alone without locking the screen or logging off. Once someone evil gets physical access to your device, **it.is.over.** So, [use the heck out of magic corners](http://lifehacker.com/253490/mac-tip--activate-your-screen-corners), the [iOS four-digit-code](http://support.apple.com/kb/HT4113?viewlocale=en_US&amp;locale=en_US) and so on. With the daily iCloud backup enabled, you should consider the ['10-times-wrong-code? Erase my iPhone!'](http://www.techbitnbyte.com/how-to-erase-data-after-10-incorrect-passcodes/) feature.

I'm no securtiy expert, but I think this will prevent you from being the next Honan.