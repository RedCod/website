---
author: linaro
comments: true
date: 2016-10-24 20:54:54+00:00
layout: post
link: https://www.96boards.org/blog/recap-96boards-openhours-24-season-2-opener/
slug: recap-96boards-openhours-24-season-2-opener
image: /assets/images/blog/OpenHours-03.png
image_name: OpenHours-03.png
title: Recap of the 96Boards OpenHours 24 - Season 2 Opener
wordpress_id: 17913
Boards:
  - DragonBoard 410c
  - HiKey
category: blog
tags:
  - 64-bit
  - 96Boards
  - aarch64
  - Android
  - ARM
  - ARMv8
  - Breakout
  - bubblegum-96
  - CE
  - Consumer Edition
  - Consumer IoT
  - DB410c
  - debugging
  - dragonboard410c
  - gdb
  - gui
  - HiKey
  - Library
  - Linux
  - Low speed expansion header
  - Open Embedded
  - Open Hours
  - OpenHours
  - Reference Platform
  - rpb
  - sensors
  - UART
---

Welcome to episode 24 in our OpenHours series, we have been at this for six months now and it has been great seeing our audience grow.  We officially launched season 2 of OpenHours this week with a guest speaker, Keith Lee from Gumstix.  Keith talked about Gumstix the company, Geppetto the drafting tool, and gave a lead into a drone demo.  This was a deep look into what [Gumstix ](https://www.gumstix.com/)does and some of their products as well as a chance for those attending the call to ask questions.

Keith Lee began by discussing his background, he started working in Tech about 10 months ago straight after finishing his master's degree and has been with Gumstix about 9 months.  Gumstix has been around about 12 years and started with a release of a single board computer.  Now their boards have been used in many different areas including boards strapped to the side of the international space station, industrial applications and even a supercomputer based on Gumstix.  He discussed the Aerocore board in great detail including his attempt to get a camera working with it.  He is also working on a drone demo and hopes to show this in OpenHours next week.  He talked about some of the new boards that have been announced but are not available just yet.  Then at 27.10 minutes into the episode Keith gave a demo of the Geppetto board drafting tool and built out a board.  He took several questions throughout the call regarding not only the Geppetto but also other boards that Gumstix has.   Keith then ended the call talking about the demo next week that will be a drone demo where he will get his mezzanine board onboard and do a ground test and tethered test.

To watch episode 24 go to[ https://www.youtube.com/watch?v=iR1YzwGwGQE ](https://www.youtube.com/watch?v=T-0KGstxTgA) or watch below:

{% include media.html media_url="https://www.youtube.com/embed/T-0KGstxTgA?feature=oembed" %}

**Be sure to join us for next week's OpenHours:  [https://www.96boards.org/](/)**

As always there is a lot of good information and resources that is available in the chat below, this is a great place to get more detailed information mentioned during the call.  Also a while ago in the hangout Robert shared a link to allow people to submit topics or questions for the developers on the hangout.  The link is:[ https://discuss.96boards.org/t/openhours-topic-suggestion/ ](https://discuss.96boards.org/t/openhours-topic-suggestion/)and Robert will take these suggestions and try to incorporate these into future OpenHours.

Please remember, if you get stuck, there are resources to help you through the installation. Feel free to check out the [96Boards forums](https://discuss.96boards.org/), [96Boards wiki](https://github.com/96boards/documentation/wiki), or [Freenode IRC](http://webchat.freenode.net/?channels=%2396boards) channel #96boards (there are many ways to access IRC, this website is one of them). Dig around the wiki, create a new forum thread, and/or post a question in the chat.

**Below is the chat log from the OpenHours session today:**

D

Refresh worked... I hear now.  Thank you.

https://www.gumstix.com/

https://twitter.com/gstixguru

PR

Sound is terrible my side

MB

sound is great here

I would suggest you try restarting your browser or application

https://www.96boards.org/product/aerocore2/

MB

or even computer

PR

trying an other browser

K

here is link to aerocore2, nodana and radium https://store.gumstix.com/expansion/partners-3rd-party.html?cat=47

C

Very cool!

https://www.gumstix.com/geppetto/

FP

Hi Folks

You are listening to Keith Lee from Gumstix. He is talking about Geppetto, AeroCore2, and 96Boards. Getting ready to build a drone

https://www.96boards.org/blog/geppettotm-offers-makers-rapid-path-to-market/

G

Where can components be placed within the 96B footprint?

MB

Could I take the DragonBoard and add an ethernet port?

V

there should be a price tag at the bottom that changes as you add/remove components

G

What is occuppying the "greened-out" regions?

K

it sounds like a form-factor/packaging  cabability is wanted for geppetto - how can we take the next step for a "pre-silicon" design to go to a curie button size vs a dev board  -- how can you get a true insect-size MAV?

G

Oh, you have an interface to the HS signals on there too?

MB

does it have to be via USB? Does SOC not have direct ability

SD

BLE support is also there?

MB

How about changing the SOC to one that does support Ethernet directly?

SD

it supports BLE and classic BLE both??

MB

I was wondering if Gepetto was strong enough to swap out the SOC, even if I need to add a bit more board space

Using 410C as an original template, and only specify the changes I want... then getting my own custom board.

W

yes.  that would be great.  a detailed blog on that

S

Hello...

I don't want to disturb this meeting.. But I wouldn't be able to follow the talk...

Does this meeting recorded ?

SS

Thanks

https://www.youtube.com/playlist?list=PL-NF6S9MM_W1QBjUc2B5Pg502bz7qslxk

Sanji

S

RW many thanks !!!

Bookmarked !

![](https://ssl.gstatic.com/ui/v1/icons/mail/images/cleardot.gif)

{% include image.html path="/assets/images/blog/OpenHours.png" alt="OpenHours Image" class="img-fluid" %}

Click here to join us for [next OpenHours ](/)
