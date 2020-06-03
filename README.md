# Intro to Web Mapping (Part 2: Street View)
## 😎 Overview
Web mapping workshop for ITP Camp 2020, a 4 week crash course for experimentations and skill sharing in art, media, and technology organized by the Interactive Telecommunications Program (ITP) at New York University.

In this workshop, we will expand the limits of web mapping by exploring the Google Street View API. When Google first began the Street View project, it was said to ["provide users with a rich, immersive browsing experience"](https://googlepress.blogspot.com/2007/05/google-announces-new-mapping_29.html). Over 10 years into its introduction, many artists, designers and researchers have used the platform creatively and critically — from captures of unexpected Street View images, virtual road trips, surveillance critique, to tracking gentrification.

This workshop aims to give participants basic toolkit to explore the capacity of Street View. We will be using Google Street View API, Glitch, HTML/CSS & JavaScript to build a web project comparing streets with the same name in two different cities or countries ([Project Reference](https://winnieyoe.com/Tracing-History-Through-Street-Names)).

The workshop takes place online through Zoom.

## Authors
Co-taught by [Winnie Yoe](https://winnieyoe.com) and [Karina Hyland](https://karinahy.com/).

## Outcomes & Goals
- Consider creative and critical use of Street View and satellite imageries
- Create a Google Street View API key
- Learn about fundamentals of using Google Street View in a web project
- Publish a web project using Glitch

## Workshop Schedule
Duration: 2 hours
- Context & Introduction
- Project References
- Guided coding exercise - let's make a web map!
- Project sharing
- (If time permits) Google Earth Studio Demo

### Note to participants
- No coding experience is required
- Don't worry if you did not participate in the first workshop, the relevant part will be how to use Glitch, which we will cover again in this workshop

---
## 🎈 Let's get started!
## Google Maps API (Step-by-Step)
🤔 **What is an API?**
An analogy: API is the waiter, server/assets (in this case Google Maps) is the kitchen, and your website is the client. API is the messenger that will take your request, process it, and eventually give a chicken rice to you.   

**Part A: Let's find all the APIs we need!**
1. Go to [Google Cloud Platform](https://console.cloud.google.com/google/maps-apis/). *(You'll need a Google account)* Agree to the terms of service and set your country.
<img src="images/API-1.jpg" alt="screenshot of create new project" width="800">

2. Click on New Project.
<img src="images/API-2.jpg" alt="screenshot click on new project" width="800">

3. Make a new project and click `Create`.
<img src="images/API-3.jpg" alt="screenshot click on new project" width="800">

4. On `APIs & Services` > `Dashboard`, click `Enable APIs and Services`. This will bring you to the API Library page.
<img src="images/API-4.jpg" alt="screenshot click on new project" width="800">

5. We'll need 5 APIs enabled in total. Let's start by clicking/search `Places API`.
<img src="images/API-5.jpg" alt="screenshot click on new project" width="800">

6. Enable the API
<img src="images/API-6.jpg" alt="screenshot click on new project" width="800">

7. You should be able see the `Places API` in your enabled APIs. We'll also need `Street View Static API`, `Maps JavaScript API`, `Geocoding API` and `Geolocation API`. You can find click on one of them under `Additional APIs`.
<img src="images/API-6B.jpg" alt="screenshot click on new project" width="800">

**Part B: Let's get our own API key!**
8.


---
## 🎉 Post Session Feedback & Resources
Please fill out the workshop feedback form

## Project References
**Street View Projects**
- ["Clinic"](http://www.lucamolnarart.com/2020/1/15/6b9hnl4likfbbyhtorazfuqguu317d), Luca Molnar
- ["Officer Involved"](https://theintercept.co/officer-involved/), Josh Begley
- ["A Series of Unfortunate Events"](https://www.lensculture.com/articles/michael-wolf-a-series-of-unfortunate-events), Michael Wolf
- ["Travel by Approximation: A Vitrual Road Trip"](https://www.lensculture.com/articles/michael-wolf-a-series-of-unfortunate-events), Jenny Odell
- ["Nine Eyes of Google Street View"](https://anthology.rhizome.org/9-eyes), Jon Rafman
- ["Deep mapping gentrification in a large Canadian city using deep learning and Google Street View"](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0212814), Lazar Ilic, M. Sawada, Amaury Zarzelli

**Street View Tool**
- [Street View Mapper](https://streetview-mapper.org/), Joey Lee

**Google Earth**
- ["Postcards from Goolge Earth"](http://clementvalla.com/work/postcards-from-google-earth/), Clement Valla
- ["How Universities Became the New Battlegrounds in  the Hong Kong Protests"](https://www.nytimes.com/interactive/2019/11/18/world/asia/hong-kong-protest-universities.html), NY Times

---

***Curriculum templates is inspired by [Eyebeam](https://github.com/eyebeam/curriculum/blob/master/TEMPLATE.md)***
