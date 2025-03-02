---
author: linaro
comments: true
date: 2016-11-14 21:51:41+00:00
layout: post
link: https://www.96boards.org/blog/recap-of-the-96boards-openhours-27-op-tee-for-96boards/
slug: recap-of-the-96boards-openhours-27-op-tee-for-96boards
title: Recap of the 96Boards OpenHours 27 - OP-TEE for 96Boards
image: /assets/images/blog/OpenHours-02.png
image_name: OpenHours-02.png
wordpress_id: 18559
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

Welcome to our 27th episode of 96Boards OpenHours sponsored by Linaro.  This episode has guest speaker, David Brown from Linaro, who discussed OP-TEE for 96Boards.  David also answered questions the attendees had about OP-TEE.  David began by talking about his background in working with cell phones and working with Qualcomm for 18 years and about his work with Linaro for for the last 11 months.  Below are more details about this episode with a time note where this is discussed in the video (i.e. 11:00).

David then began his talk with a very basic definition of OP-TEE and what it is.  OP-TEE can basically be described as trusted computing.  The idea is you have things you need to protect from most of the system and OP-TEE provides a way of doing that.  Historically this has been done with a separate processor.  The best use case is NetFlix, when you play a video the companies that own that content don't want you to be able to copy that video so the video is encrypted so that it can be played and viewed but it cannot be copied.

**11:00 -** David then spoke about TrustZone, OP-TEE and Global Platform, and discussed the differences and similarities of these efforts.  He also talked about the implementations of each and how they worked.  David gave a great in-depth overview of these platforms.  Here is a link for more information:  [https://www.arm.com/products/security-on-arm/trustzone-ready/index.php ](https://www.arm.com/products/security-on-arm/trustzone-ready/index.php)

**For further information you can also visit: **

(Great video from Connect LAS16 with some nice diagrams)- LINK REMOVED [http://www.op-tee.org/
](http://www.op-tee.org/)OP-TEE Docs [https://www.op-tee.org/documentation/
](https://www.op-tee.org/documentation/)OP-TEE on github [https://github.com/OP-TEE/
](https://github.com/OP-TEE/)[https://github.com/96boards/documentation/wiki/HiKeyOPTEE
](https://github.com/96boards/documentation/wiki/HiKeyOPTEE)OP-TEE OS [https://github.com/OP-TEE/optee_os](https://github.com/OP-TEE/optee_os)

**17:45 -**  The first question of the call was, "Are there places to go to review repositories if someone is interested in getting involved in OP-TEE?" David goes into detail about this, also you can get some information from the links above.

**24.09** - "Do key and certificate management work well/or not with trustzone enabled soc?"  David explained that this is sort two questions, how do we know the code we are running is safe and the second question is regarding eboxes and how does this get protected?  David then gave an in-depth answer to how this works.

**27:55 -** Another question to David was - "Can you execute multi-threaded applications in op-tee?"  David was not sure of the answer for this one but offered some of his thoughts and recommended some places to find out.

**29:42 -** The next question to David was, "Can we be choosy on the cpus OP-TEE runs on?"  David gave a quick overview for this one.

**31:39 -** Robert thanked David for attending and then introduced the topic for the 2nd half of the call, which was a discussion with one of the attendees regarding the issue they were having with their Mezzanine board.  The team then discussed the issued and tried to come up with solutions that might solve the problem.

**46:00 -** Robert then wrapped up the hour and recapped what was discussed.  He then went on to announce the topic for next week which will be an interview with members from AiStarVision about their efforts towards creating a MIPI camera mezzanine for 96Boards.

To watch episode 27 go to[ https://www.youtube.com/watch?v=f8I-jXHu45Q](https://www.youtube.com/watch?v=gjWnEZJFa_U) or watch below:

{% include media.html media_url="https://www.youtube.com/embed/gjWnEZJFa_U?feature=oembed" %}

**Be sure to join us for next week's OpenHours:  [https://www.96boards.org/](/)**

As always there is a lot of good information and resources that is available in the chat below, this is a great place to get more detailed information mentioned during the call.  Also a while ago in the hangout Robert shared a link to allow people to submit topics or questions for the developers on the hangout.  The link is:[ https://discuss.96boards.org/t/openhours-topic-suggestion/ ](https://discuss.96boards.org/t/openhours-topic-suggestion/)and Robert will take these suggestions and try to incorporate these into future OpenHours.

Please remember, if you get stuck, there are resources to help you through the installation. Feel free to check out the [96Boards forums](https://discuss.96boards.org/), [96Boards wiki](https://github.com/96boards/documentation/wiki), or [Freenode IRC](http://webchat.freenode.net/?channels=%2396boards) channel #96boards (there are many ways to access IRC, this website is one of them). Dig around the wiki, create a new forum thread, and/or post a question in the chat.

**Below is the chat log from the OpenHours session today:**

DB

I don't have any more video

Carbon board: [https://www.96boards.org/product/carbon/](/product/carbon/)

Youtube: [linaro.co/96byt](http://linaro.co/96byt)

---

V

[https://www.arm.com/products/security-on-arm/trustzone-ready/index.php](https://www.arm.com/products/security-on-arm/trustzone-ready/index.php)

look at the 3rd tab "TEE Standardisation" while David explains..

op-tee is an implementation of the TEE kernel

---

RW

OP-TEE video from Linaro Connect:

LINK REMOVED

[http://www.op-tee.org/](http://www.op-tee.org/)

OP-TEE Docs [https://www.op-tee.org/documentation/](https://www.op-tee.org/documentation/)

OP-TEE on github [https://github.com/OP-TEE/](https://github.com/OP-TEE/)

---

YZ

[https://github.com/96boards/documentation/wiki/HiKeyOPTEE](https://github.com/96boards/documentation/wiki/HiKeyOPTEE)

OP-TEE OS [https://github.com/OP-TEE/optee_os](https://github.com/OP-TEE/optee_os)

---

YZ

do we want to also talk about key and certificate management? and how that work well/or not with trustzone enabled soc

both

---

J

can you execute multithreaded applications in op-tee?

---

YZ

yep thanks

---

J

linaro

---

RW

[https://www.op-tee.org/](https://www.op-tee.org/)

---

J

can we be choosy on the cpus OP-TEE runs on?

---

J

ok. thx. I think it has been worked in progress, just wondering if the work was done. cool.

---

RW

:D

---

YZ

still here

---

BS

Rob how do i get hold of a complimentary 410cDragon  boards , do you have any giveaways

today

---

RW

Not today, we are hoping to do another giveaway between Season 2 and Season 3

probably in January

---

DM

Possibly your Level shifter at our Read end is not doing it properly..

Could you please share the way you are doing the level shifting ?

---

JM

I guess it goes well, thanks

I must be leaving now, see you

---

DB

#include <terminos.h> should be available for a native app in Android. I don't know if there is a JAVA api for this

termios.h

---

DM

Please share the link I will have a look at that this weekend..

---

TS

Nope

Sorry

Working on it, thanks for your help

Will get back

---

YZ

@jean-marc, please send me the forum post link

I just tried on my dragonboard - certainly input is working

on android,

or drop me an email

---

J

here is the link of my question in the forum

---

YZ

got to run now - later

---

J

[https://discuss.96boards.org/t/uart0-android-sensors-mezzanine/#post-17786](https://discuss.96boards.org/t/uart0-android-sensors-mezzanine/#post-17786)

---

multithreaded ta is not supported but multiple cores can run the same ta at the same time

[https://twitter.com/sdrobertw](https://twitter.com/sdrobertw) [https://twitter.com/96boards](https://twitter.com/96boards)

---

Click here to join us for [next OpenHours ](/)
