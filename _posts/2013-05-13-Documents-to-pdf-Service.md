---
layout: post
title: Documents to .pdf Service
date: 2013-05-13 15:06:53
category: tech
published: true
---

There's probably about three people out there who are interested in this, but here's an OS X system service ([.zip](http://appchive.net/f/tschoof/71512)) that converts documents to pdfs. 

It uses [LibreOffice](http://www.libreoffice.org/download), so you need to have that installed, and supports .doc, .docx, .odt, .ppt and .pptx. [Here's how to install a system service on OS X](http://brettterpstra.com/howtos/install-an-os-x-system-service/).

Simply select the files you want to convert, wait a second, and they should all be there as .pdf files. The Service moves the original files to the trash. 

Thanks to the person who posted the script line I used for this on stackoverflow.