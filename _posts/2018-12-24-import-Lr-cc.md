---
layout: post
title: "Importing photos into Lightroom CC"
date: 2018-12-28 18:12
category: tech
published: true
---


Recently, I took the plunge and started using Adobe’s Creative Cloud. While there's a ton of stuff to get into with Lightroom CC on the Mac as well as on iOS, I just want to tackle one very specific topic in this post:

How to improve the import process (on the Mac, that is). Why does it need improving? I'm glad you asked. With Lightroom CC, pictures aren’t “touched” on import anymore: They don’t get converted to [.dng](https://petapixel.com/2015/12/08/dng-the-pros-cons-and-myths-of-the-adobe-raw-file-format/) and aren’t renamed, as was the case with the "old" Lightroom.

Bummer.

Why do I care? Isn’t Creative Cloud the only truth and relevant source anyway? Yes, kinda. 

## file format

But when *exporting* a file in Lr CC, the format is still relevant. Lr CC offers the option to export an *original with edits*. If I didn't convert the files on import, I'd end up with an .orf (the name of Olympus' RAW format) file – with an ugly .xmp sidecar file containing Lr's edit information. Yuck. If you work with .dng files, the edits get baked into the file, so there's no extra .xmp file. Bliss.

## file names

Next up, file names. While this may show my pathological sense of order, I *care about file names*. My camera uses continuous naming scheme for photos. Dealing with that is a non starter.

Like any sane person, I work with my photos in Lr or some other library software only. And there's always metadata, so the file names aren't that relevant. But a naming scheme that reflects the date a photo was taken is a good fallback, and simply reassuring to me. When it comes to backups, sync etc. being able to look at the file and knowing the creation date just makes sense and is something I don’t want to miss.

## the script(s)

Here’s how I solved these problems. 

I wrote two bash scripts. One grabs the .orf files from the SD card, copies and converts them. I execute it manually via [Alfred](https://www.alfredapp.com/). The other one renames the files, I execute it manually *like an animal* as well, after the import and conversion script is done. 

If you don't use Alfred: With Apple's Automator.app, it's easy to make these scripts easily executable as a [system service, or even "apps"](https://www.engadget.com/2008/01/01/mac-automation-saving-automator-workflows/). 

I couldn’t for the life of me figure out a non-hacky way to string these two together, that's why I execute them manually (If you know how, let me know!).

### Copy and Convert
This script uses [Adobe’s own, standalone DNG converter](https://helpx.adobe.com/photoshop/using/adobe-dng-converter.html). Yes, there is such a thing. 

To work for you as well, the script needs a little adjusting: The paths to **a)** a temp folder for storing the .dng files (which the second script will need), **b)** your SD card (when it's inserted and mounted of course). Then, **c)** you only need to turn the *.orf* into whatever your camera brand's RAW format name is, so that the script grabs those files.

<script src="https://pastebin.com/embed_js/vivrDk43"></script>
<br>

### Rename
This script uses EXIFtool to rename files, ant then moves them to another folder, just for a sense of order. It took me a long time to find the darn *4c* option (for ascending numeration) in EXIFtool, but in the end I did. This script uses a *yyyymmdd-####* scheme for renaming. So the first picture I take on chrismas eve 2018 is named 20181224-0001.dng.

The script also strips any comment from the description tag your camera might have put there (My Olympus is obnixious like that). [Get EXIFtool](http://web.mit.edu/jhawk/mnt/cgs/Image-ExifTool-6.99/html/install.html#OSX) if you don't already have, adjust folders as neccessary and naming to your liking and you're all set.

<script src="https://pastebin.com/embed_js/hLtHSpHh"></script>
<br>

I hope this is helpful. Feedback is very welcome! Cheers.