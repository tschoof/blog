---
layout: post
title: "AppleScript for generating podcast-ready mp3s"
date: 2015-03-21 12:40:20
category: podcasts
published: true
---

Here's an AppleScript that passes variables (episode title and description)  to a bash script, opens it in a terminal window and runs it, letting you watch how it generates a podcast-ready mp3 file. I've put it into an Automator workflow that accepts audio files.

<script src="http://pastebin.com/embed_js.php?i=PAtEKm0J"></script>
<br>
Here it is [on GitHub](https://gist.github.com/tschoof/6ed9100fa05e635cadd6).

It should be pretty self-explanatory: Just  fill in the path to the script. Which script? I'm glad you asked! It's the script that does the "work", if you will, of generating an mp3 using LAME. I used [a fork of Marco's script](https://gist.github.com/tjluoma/357bf0c0efc9bb5591fc) because it was easy to feed with variables and a bit more elegant. To use it, just fill in your podcast's name, the path to the artwork, and you're good to go!

Getting the POSIX file name of the input file via AppleScript was kind of a hassle, I hope whoever runs into the same problem finds this.

With the method of using AppleScript to pass variables to a bash script, I riffed off of [Jason Snell's solution](http://sixcolors.com/post/2015/03/bad-applescript-shell-scripting-and-automator/). 