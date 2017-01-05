---
layout: post
title:  "IBC Hackfest"
date:   2015-09-13 22:00:00 +0000
categories: hackathons
---

<img class="screenshot" src="/assets/2015-09-13-ibchackfest/screenshot.png" />

<h1>Vidlytics</h1>

Providing statistics about CDN providers.

## Inspiration
One of the sponsors at IBC Hackfest was Streamzilla, and their challenge at the event was:.........

## What it does
An online tool for content providers to test out CDNs for providing video streams, and to monitor the quality received by the end user, as well as receive a timeline of events such as buffering video and dropped frames.

It had three main features:

### QoE Triangulation
Actively discovering viewer connection problems by comparison between multiple route mid-points.

### Manifest Engineering
Strategicially injecting, proxying and redirecting to gather media request analytics with minimal client disruption.

### Analytics
Real-time visual representation of a user's video experience by leveraging data agregated from our servers and the client's themselves.

## How we built it
We continued to use Meteor for the frontend and backend of the application and used our knowledge of video streaming that we had accrued while on our placement year at Techex.

## What we learned
We learned how to inject code into a video so that we could carry out the redirection for gathering information.

<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2015-09-13-ibchackfest/1.jpg" />
	<img class="gallery-image" src="/assets/2015-09-13-ibchackfest/2.jpg" />
</div>