---
title: Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
gallery:
  - url: /files/images/tripease/landing.png
    image_path: /files/images/tripease/landing.png
    alt: "Landing"
  - url: /files/images/tripease/budget.png
    image_path: /files/images/tripease/budget.png
    alt: "Itinerary"
  - url: /files/images/tripease/itin.png
    image_path: /files/images/tripease/itin.png
    alt: "Budget"
gallery2:
  - url: /files/images/sakuranbot/discord.png
    image_path: /files/images/sakuranbot/discord.png
    alt: "Discord"
  - url: /files/images/sakuranbot/quizDemo.png
    image_path: /files/images/sakuranbot/quizDemo.png
    alt: "Quiz"
  - url: /files/images/sakuranbot/JLPT.png
    image_path: /files/images/sakuranbot/JLPT.png
    alt: "Settings"
  - url: /files/images/sakuranbot/postDemo.png
    image_path: /files/images/sakuranbot/postDemo.png
    alt: "postDemo"
gallery3:
  - url: /files/images/memories/landing.png
    image_path: /files/images/memories/landing.png
    alt: "Landing"
gallery4:
  - url: "/files/images/virtualrealities/othello demo.png"
    image_path: "/files/images/virtualrealities/othello demo.png"
    alt: "Othello"
---

Tripease

A fullstack web application that lets users to perform CRUD operations to develop itinerary for their trips. Built with the Django REST Framework, JavaScript, React, Redux, TailwindCSS, MySQL, and the Google Maps API. Figma was also used to create wireframes and mockups of the site. 

 Users can create an account to create a bare bones itinerary for however many days and use a biased search bar to select a location they want to search around (e.g. you want to look up X thing around Cannes, France). Users can then search for places of interest (pois) which will create an instance of a specialized Google Map where users can click markers to see detailed information about said pois and add them to their itinerary. It's also possible to set budgets for each location a user adds, which will tally up the total amount that will be spent throughout the trip automatically, which makes this app effective for splitting the costs with friends or family.

You can visit the website [https://github.com/johnmarion1126/Tripease](here), but unfortuntely the Google Maps capabilities are offline currently as things cost money.
Login: elijahespiritu93@yahoo.com Pass: Password2332

{% include gallery id="gallery" caption="Images of the landing page, itinerary, and budget breakdown" %}

Sakuranbot

A bot for the popular social platform, Discord. The bot is able to join a server on Discord and can give out Japanese language quizzes or just post popular posts from other social media platforms such as Reddit. Uses an SQLite database to store the settings of the bot as well as the data of Japanese kanji and compound words. Language quiz settings can be tweaked to include only certain kanji/compounds from varying JLPT (Japanese Language Proficiency Test) levels. Also lets users learn more about the kanji/compounds they encounter throughout their quizzes by providing detailed info and even links to the popular Japanese dictionary website, [Jisho](https://jisho.org/)

{% include gallery id="gallery2" caption="This is a sample gallery to go along with this case study.." %}

Memories

A fullstack MERN social media application

{% include gallery id="gallery3" caption="This is a sample gallery to go along with this case study..." %}

Virtual Realities

A program that lets users play Othello, TicTacToe, or Connect Four against each other.

{% include gallery id="gallery4" caption="This is a sample gallery to go along with this case study...." %}
