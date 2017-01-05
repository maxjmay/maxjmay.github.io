---
layout: post
title:  "NBC London Hackathon"
date:   2015-06-07 22:00:00 +0000
categories: hackathons
---

<img class="screenshot" src="/assets/2015-06-07-nbclondon/screenshot.jpg" />

<h1>ADapTV</h1>

Using viewing information to provide more targeted advertisements.

## Inspiration
There is a lack of reach with common personalised advertising methods so we hope to bring smart advertising to smart TV's, and replace the archaic advertising methods to better understand the reach of an advert.

## How it works
ADapTV aims to provide more targeted advertising, by just using the viewing habits of an everyday user.

A set top box plays a standard tv broadcast, the server scans the content for information to pofile the user based on the shows that they watch, by using image recognition and AlchemyVision to pick out key objects in the image, and AlchemyLanguage to pick out key words in the programme description for the currently playing programme.

Advertisers add the adverts that they want to play, and specify key words for that advert.

When we see that an ordinary advert is playing, by comparing video thumbnails against known adverts, we can then play the advert that most closely matches the users profile, literally on top of the currently playing stream, bringing more relevant and useful adverts.

The advantages of this are:
1. We are only monitoring viewing habits of a user, no other personal data is used.
2. The user doesn't have to do anything different from their everyday activities; no questions to answer, tweets to post etc.
3. We can use data from users of all ages, as there is no barriers such as not having a Twitter account.
4. Also, people only post information on social network sites which they want people to see; guilty pleasures would be completely missed.
5. TV Users get adverts that they may be interested in, making adverts more enjoyable to watch.
6. Advertisers know that there adverts are more targeted, providing a better response.
7. We can provide advertisers with data on whether a user changed channel while that advert was on.

## Challenges we ran into
Efficiently swapping from broadcast to custom advert, and building the algorithm to categorise both users and programmes.

## What we learned
We learnt how to use APIs to perform image recognition, how to carry out video insertion and also how to used the FFMPEG library.

<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2015-06-07-nbclondon/1.JPG" />
	<img class="gallery-image" src="/assets/2015-06-07-nbclondon/2.jpg" />
	<img class="gallery-image" src="/assets/2015-06-07-nbclondon/3.jpg" />
	<img class="gallery-image" src="/assets/2015-06-07-nbclondon/4.jpg" />
</div>