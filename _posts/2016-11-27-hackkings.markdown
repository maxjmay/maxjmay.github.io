---
layout: post
title:  "HackKings Hackathon"
date:   2016-11-27 22:00:00 +0000
categories: hackathons
---

<img class="screenshot" src="/assets/2016-11-27-hackkings/screenshot.jpg" />

<h1>Pail Blue Sky</h1>

An intelligent list management application. 

## Inspiration
I have multiple ways of keeping track of all the gigs I want to go to, movies I want to see, hackathons I want to attend, and many more. I wanted one central place where I could keep track of all these different things, as well as find out more information about them.

## What it does
We've built a web app on which users can create and share bucket lists of a range of things including places to visit, films to watch, music artists to see live, restaurants and more. We pull data in from different APIs to help users search for things to add and also to provide them information about the things in their lists; google map locations, event listings etc.

## How we built it
It's built using primarily NodeJS, since we're using browserify on the front end too. We started by building an API using Expressjs and Sequelize and signed up for lots of API keys. Then we built the ReactJs web-app to use our API.

The APIs that we were able to integrate were:
1. OMDB (Movie database).
2. Last.fm
3. Discogs
4. Ticketmaster
5. Zomato (Restaurant database).
6. Google Books
7. Video Games Database
8. Countries Database

## Challenges we ran into
Tried to be too ambitious with the amount of APIs we could fully implement into the application in the given time period.

## Accomplishments that we're proud of
We finished a ship-able app, and it did basically all the things what we wanted it to do, without going over the time limit.

## What we learned
We learned how to quickly integrate multiple different 3rd party APIs into our application and package the data up so it is in a comman format.

<div class="photo-gallery">
	<img class="gallery-image" src="/assets/2016-11-27-hackkings/1.jpg" />
	<img class="gallery-image" src="/assets/2016-11-27-hackkings/2.jpg" />
	<img class="gallery-image" src="/assets/2016-11-27-hackkings/3.jpg" />
</div>