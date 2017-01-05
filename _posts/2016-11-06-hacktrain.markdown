---
layout: post
title:  "HackTrain Hackathon"
date:   2016-11-06 22:00:00 +0000
categories: hackathons
---

<img class="screenshot" src="/assets/2016-11-06-hacktrain/screenshot.png" />

<h1>CheckM8</h1>

A tool for train ticket inspectors.

## Inspiration
HackTrain is a hackathon focused purely on the rail industry. A variety of companies such as Trainline, and Transport for London provided access to their APIs so that the hackathon attendees could build products to solve some of the issues with infrastructure, as well as customer service.

## What it does
The application would hook into the existing CCTV system on the train, and it would use the Microsoft image recognition API to gather information about the different passengers getting on the train at any given stop. The kind of information we would try to establish would be the gender, possible age range, whether the passenger is wearing glasses, has a beard, hairstyle and colour etc. We would then display this information to the ticket inspector as he makes his way through the train.

We built the app with the aim to make ticket inspectors jobs more efficient, potentially allowing them to fulfil other roles as well on the train, while also helping to reduce the amount of fare dodgers. We went for a visual representation of the person, rather than simply showing a photo, to help ease privacy concerns.

## How we built it
We used React to build the frontend, powered by a Python backend. It was my first time using React with no assistance from teammates that had used it before, and I found it incredibly easy to setup, and will be my favoured choice going forward for the next few hackathons.

## Challenges we ran into
The hackathon, although starting on a Friday and finishing on a Sunday, was quite limited with the amount of hacking time available, with a lot of travelling from London to Colchester to Cambridge and finally back to London. This meant we weren't able to complete the project to the standard we had hoped for.


<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2016-11-06-hacktrain/1.jpg" />
	<img class="gallery-image" src="/assets/2016-11-06-hacktrain/2.jpg" />
	<img class="gallery-image" src="/assets/2016-11-06-hacktrain/3.jpg" />
</div>