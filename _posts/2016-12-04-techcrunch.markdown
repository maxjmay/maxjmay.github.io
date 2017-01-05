---
layout: post
title:  "TechCrunch Disrupt Hackathon"
date:   2016-12-04 22:00:00 +0000
categories: hackathons
comments: true
---

<img class="screenshot" src="/assets/2016-12-04-techcrunch/screenshot.jpg" />

<h1>Not Impressed</h1>

## Inspiration
After the 2016 U.S. General Election, fake news websites have become a growing concern on social media sites, without too many solutions existing to combat this problem.

Notably, we saw this TechCrunch article mentioning a new Chrome Extension: https://techcrunch.com/2016/12/01/facebook-fake-news-flags-reliable-news-source/ However, after a closer inspection, we've noticed that the extension used a manual list of websites to power it, and with fake news sites popping up and shutting down on a regular basis, we didn't think that this would be an efficient long term approach.

## What it does
1) Notim.press/ed allows a user to quickly check the authenticity of a news provider. It uses machine learning to dynamically determine a trust metric for a given news article, based on metrics from a variety of sources:

Alexa Ranking
Sentiment Analysis
Bounce Rate
Headline Clickbait detection Machine learning technology allows our product to improve its accuracy over trials and trials, with a significant benefit over other Chrome Extensions.

2) We compile that result for different articles per domain, and put the geolocation of the domain on a Map based on the trustworthiness of its related articles.

3) As a BONUS we are providing a Chrome extension in order to quickly check the trustworthiness of a piece of news.

## How we built it
We're using Node.js for the backend, with the help of IBM Watson's Alchemy Language api to provide semantic analysis on the articles text. We've implemented our machine learning system using a neural network with 4 hidden layers and 10000 iterations. We're using a mix of ESRI and THREE.JS for mapping the geolocations of the news providers we've tested.

## Challenges we ran into & Accomplishments that we're proud of
We didn't know much about machine learning when we first began the hackathon, so we felt pretty good about learning about it on-the-fly and managing to make it work! Also, the new version of ESRI had some very tricky changes compared to other versions and making it integrate correctly with THREE.JS wasn't a piece of cake.

## What we learned
How to implement successfully a form of machine learning and working with the latest version of ESRI ARCGIS in conjunction with THREE.JS.

## What we won
Our project was given a mark above 3, and we were provided with tickets for TechCrunch Disrupt London. On Tuesday 6th December I wvisited TechCrunch Disrupt, where I saw the finals of the Statup Battlefield and networked with other startup companies.

<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2016-12-04-techcrunch/1.jpg" />
	<img class="gallery-image" src="/assets/2016-12-04-techcrunch/2.jpg" />
	<img class="gallery-image" src="/assets/2016-12-04-techcrunch/3.jpg" />
	<img class="gallery-image" src="/assets/2016-12-04-techcrunch/4.jpg" />
</div>