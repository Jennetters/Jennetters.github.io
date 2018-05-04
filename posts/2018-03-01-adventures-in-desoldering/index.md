---
layout: post
title:  "Adventures in desoldering"
date:   2018-03-01 23:18:28 -0500
tags: split mechanical keyboard, iris keyboard, mechanical keyboard, pictures
---

Finally had a chance to open up the keyboard and see what the problem was with the dead keys. As it turns out, the issue with the U and J keys was that I didn't solder the switches. And here I thought I was being so careful, must have been over excited. So I solderd those and plugged the board in and TADAA!!! Right half is fully functional.

As for the left half, which had the dead row. Well, this is my life now.

<blockquote class="imgur-embed-pub" lang="en" data-id="a/vdXBm"><a href="//imgur.com/a/vdXBm">View post on imgur.com</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

I checked all of the diodes and paths, but I could see one pin on the controller didn't appear to be soldered, so I tried to solder it and it just. wouldn't. flow. I'm confident that I damged the Pro Micro when I desoldered it on Monday and the connection for that pin is just toast. I tried several times and couldn't get it soldered to make the connection.

So, here I am faced with a really, really gross dillemma. Because of the construction of the board/case plates, if I want to get at the top side of the board to remove the header pins and attach a new Pro Micro, I've literally got to desolder all of the switches on the board in order to be able to remove the plate. 

Super disgusting, right?!

In an ideal world, I could desolder the Pro Micro and leave the pins on the board, then just put a new one in its place. This was harder than it seemed, even though it looked like I had a clean pin I still couldn't get the Pro Micro off. So, I did what any sane person would do, I grabed some pliers and wire cutters and obliterated the pro micro, leaving the pins intact. Then I desoldered the pins and cleaned everything with a little bit of rubbing alcohol. Good as new... if new was chewed up by a dog and spit out.  

Attaching the new Pro Micro onto the existing header pins which were a little less than straight was a bit of a challenge, I used some needle nosed pliers to feed them through one at a time but I managed to get it and solder it down.

Now I'm back to having issues flashing the board because, Wandows. 

And once again, it's way past my bedtime.