---
layout: post
title:  "HackLondon Hackathon"
date:   2015-03-01 22:00:00 +0000
categories: hackathons
---

<img class="screenshot" src="/assets/2015-03-01-hacklondon/screenshot.jpg" />

<h1>HomeSpun</h1>

A raspberry pi IPTV system.

## Inspiration
After attending many hackathons previously, but only doing software hacks, we wanted to have a go at developing a hardware hack. So we brought our Raspberry Pi, and television, and built HomeSpun.

## What it does
We reverse engineered streams from various websites such as BBC1, 2 and 3, NASA HD, and online cams of famous locations throughout the world to build up our list of channels.

We then used websockets to connect the Raspberry Pi to our HomeSpun remote server. From here we can change the channel of any Raspberry Pi's connected to the server, or all at the same time.

But we didn't want just a basic video system, so we integrated features such as timers, alarms, and on-screen messages to enable the users to not lose track of time, and to remember to turn the oven off, for example. All of these can be applied to all Rasberry Pi's on the server at the same time, with our own API.

We then added our social element to HomeSpun. When a user receives a mention on Twitter, a notification appears on the screen, telling the user the message that they have received, meaning their phone can remain in their pocket.

We then started page scraping the websites we retrieved the channels from, to gain information about what was currently playing, which we could insert into our remote.

## How we built it
The frontend was built using HTML, CSS and Semantic UI. The backend was built using Node.js and Socket.IO.

## What I learned
How to setup a a raspberry pi and run an application off of it so that we could watch live video streams. This was the first hackathon where I myself had to pitch the idea to a room of around 150 people, so it helped to improve my public speaking skills.

<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2015-03-01-hacklondon/1.jpg" />
	<img class="gallery-image" src="/assets/2015-03-01-hacklondon/2.jpg" />
</div>