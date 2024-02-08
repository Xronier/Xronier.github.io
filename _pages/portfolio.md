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
  - url: /files/images/tripease/itin.png
    image_path: /files/images/tripease/itin.png
    alt: "Itinerary"
  - url: /files/images/tripease/budget.png
    image_path: /files/images/tripease/budget.png
    alt: "Budget"
gallery2:
  - url: /files/images/sakuranbot/discord.png
    image_path: /files/images/sakuranbot/discord.png
    alt: "Discord"
  - url: /files/images/sakuranbot/QuizDemo.png
    image_path: /files/images/sakuranbot/QuizDemo.png
    alt: "Quiz"
  - url: /files/images/sakuranbot/JLPT.png
    image_path: /files/images/sakuranbot/JLPT.png
    alt: "Settings"
  - url: /files/images/sakuranbot/PostDemo.png
    image_path: /files/images/sakuranbot/PostDemo.png
    alt: "Posts"
gallery3:
  - url: /files/images/memories/landing.png
    image_path: /files/images/memories/landing.png
    alt: "Landing"
gallery4:
  - url: "/files/images/virtualrealities/othello demo.png"
    image_path: "/files/images/virtualrealities/othello demo.png"
    alt: "Othello"
  - url: "/files/images/virtualrealities/connectfour demo and show history.png"
    image_path: "/files/images/virtualrealities/connectfour demo and show history.png"
    alt: "ConnectFour"
  - url: "/files/images/virtualrealities/tictac demo and undo.png"
    image_path: "/files/images/virtualrealities/tictac demo and undo.png"
    alt: "TicTacToe"
---

 <font size="15">Tripease</font> 

&emsp;&emsp;A fullstack web application that lets users to perform CRUD operations to develop an itinerary for their trips. Built with the Django REST Framework, JavaScript, React, Redux, TailwindCSS, MySQL, and the Google Maps API. Figma was also used to create wireframes and mockups of the site. 

&emsp;&emsp;Users can make an account to create a bare bones itinerary for however many days and use a biased search bar to select a location they want to search around (e.g. you want to look up places of interest (pois) only around Cannes, France). Users can then search for pois which will create an instance of a specialized Google Map where users can click markers to see detailed information about said pois and add them to their itinerary. It's also possible to set budgets for each poi a user adds. This will tally up the total amount that will be spent throughout the trip automatically, making this app effective for splitting the cost with friends or family.

You can visit the website [here](https://github.com/johnmarion1126/Tripease), but unfortuntely the Google Maps capabilities are offline currently as things cost money.  

{% include gallery id="gallery" caption="Images of the landing page, itinerary, and budget breakdown" %}

<font size="15">Virtual Realities</font> 


&emsp;&emsp;A program that lets users play Othello, TicTacToe, or Connect Four against each other. Implemented purely with C++. This project uses the MVC design architecture and object oriented programming.

&emsp;&emsp;Integration of a new game is possible because polymorphism can easily take the shape of these games as they all share similar characterstics. Namely, a game should involve placing a piece (rather than start with pieces, like chess), having an observable change in one of the cardinal directions after placing a piece (e.g. checking if the user just connected four), and having a square or rectangualar board.

&emsp;&emsp;When implementing a game, you are tasked with building several algorithms. Building the algorithm can range from easy to exceedingly difficult. For example, making a move in TicTacToe requires you to simply check if the space is empty and if there's a winner after placing the piece. In Othello though, it requires you to scour each cardinal direction of the piece you're placing down in search for a friendly piece so it can then flip each enemy piece leading to that friendly piece while making sure to not double count pieces that were already observed in another cardinal direction and yada yada. Other algorithms that can be created are undoing n moves, showing the game's current history, and showing the current value of the board.

The code can be found [here](https://github.com/Xronier/CECS-282/tree/master/VirtualRealities/VirtualRealities)

{% include gallery id="gallery4" caption="Images of Othello, ConnectFour, TicTacToe, and various utilities of the app" %}

<font size="15">Sakuranbot</font> 

&emsp;&emsp;A bot for the popular social platform, Discord. The bot is able to join a server on Discord and can give out Japanese language quizzes or just post popular posts from other social media platforms such as Reddit. The bot uses an SQLite database to store the settings as well as the data of Japanese kanji and compound words. Language quiz settings can be tweaked to include only certain kanji/compounds from varying JLPT (Japanese Language Proficiency Test). The bot also lets users learn more about the kanji/compounds they encounter throughout their quizzes by providing detailed info and even links to the popular Japanese dictionary website, [Jisho](https://jisho.org/).

The code can be found [here](https://github.com/Xronier/Sakuranbot)

{% include gallery id="gallery2" caption="Images of Discord, the quiz function, settings function, and post function" %}

<font size="15">Memories</font> 

&emsp;&emsp;A fullstack MERN social media application that allows users to perform CRUD operations on a MongoDB database. Developed a REST API using Node.js, Express.js, and MongoDB. The REST API allows the client side of the application to communicate with the server side of the application (which is decoupled). The client side of the application is done with React to create a responsive UI.

The code can be found [here](https://github.com/Xronier/memories_project)

{% include gallery id="gallery3" caption="Image of the landing page" %}
