# Hangman - Game

# Introduction
Project milestone 3 for Code Institute Full-stack development program: JavaScript Essentials.

Hangman is a Python terminal game, with runs in the Code Institute mock terminal on Heroku. 
The main goal of the game is to guess letters or the full word that the computer randomly selects.

[Live Project Here](https://portfolio-project-3.herokuapp.com/)


<p align="center"><img src="./assets/images/readme/hangman-cover.png" alt="Hangman game webpage on multiple devices"></p>

## README Table Content

* [Introduction](#introduction)
* [User Experience UX](#user-experience---UX)
* [Design](#Design)
    * [Flow](#Wireframe)
    * [Typography](#typography)
  
* [Features](#features)  
    * [Logo and Intro Message](#logo-and-intro-message) 
    * [Navigation Menu](#navigation-menu)
    * [Quiz Game 1 - Sports](#quiz-game-1---sports)
    * [Quiz Game 2 - History](#quiz-game-2---history)
    * [Quiz Game 3 - Geography](#quiz-game-3---geography)
    * [Game End Page](#game-end-page) 
    * [Trophy Gold Page](#trophy-gold-page)
    * [Trophy Silver Page](#trophy-silver-page)
    * [Trophy Bronze Page](#trophy-bronze-page)
    * [High Scores Page](#hign-scores-page)
* [Future Features](#future-features)
* [How to Play](#how-to-play)
* [Technologies Used](#technologies-used)
    * [Languages Used](#languages-used)
    * [Frameworks - Libraries - Programs Used](#frameworks---libraries---programs-used)
* [Testing](#testing)
* [Deployment](#deployment-this-project)
    * [Deployment This Project](#deployment-this-project)
    * [Forking This Project](#forking-this-project)
    * [Cloning This Project](#cloning-this-project)
* [Credits](#credits)
* [Content](#content)

## User Experience - UX

 ### User Stories

* As a website creator, I want to:
  
1. Build an easy app for the users to play the game.
2. Build a game that is both enjoyable and challenging for the players.
   
* As a new visitor, I want to:

1. Be able to understand the main purpose of the App and start a new game. 
2. Be able to follow along the score, wrong and right letters already guessed and the remaining of available tries while I am playing the game.
3. Be able to watch my results and other players results on the Leaderboard.
   
* As a returning visitor, I want to:

1. Be able to guess a different word choose by the computer. 
2. Be able to challenge myself and try to improve on my scores and compare with other users on the leaderboard
   
## Design

### Flowcharts 
 ![Color Scheme](./assets/images/readme/hangman-flowcharts.jpg)<br>
I spent time planning and thiking about the logic behind the game to ensure I had a general idea of how it should be built. I created flowcharts to allow me to follow the logic through the application. The charts were generated using https://lucid.app/ Integration and are shown below.<br>
[Flowcharts ](https://cutt.ly/oIkZsAW)

#### Colours
* The colours in the game are supplied by using the the Python Colorama Model.

#### Typography
* The Arial is used as the main font for the whole website.
      
## Features

### Logo and Intro Message

![Logo and Intro Message](./assets/images/readme/hangman-feature-1.jpg)

* When the users reach the website, they will see this feature where it will be displayed the game logo and the intro message.<br>

### Ask Player Name and City

![Ask Player Name and City](./assets/images/readme/hangman-feature-2.jpg)
* After the player see the intro feature the computer will ask the user's name and city to be adding by input.<br>

#### Empty Input for Name and City
![Empty Input for Name and City](./assets/images/readme/hangman-feature-3.jpg)
* If the player is trying to submit an empty input for name and city will see  this alert.<br>

### Welcome Message and Game Rules
![Welcome Message and Game Rules](./assets/images/readme/hangman-feature-4.jpg)
* After the user input the name and city the program will display the welcome message and the game rules. The player just need to press any key to start the game.<br>

## Game Features
### Hangman Stage 1
![Game Feature](./assets/images/readme/hangman-feature-5.jpg)<br><br>
This feature is where the main scene happens. Here the user can play and see information about the game: 
* Numbers of letters choose by the computer. 
* Stage of the hangman 
* Letters guessed right
* Letters guessed wrong
* Curenntly score
* Curently number of attempts
* Input to guess a letter or a full word
* Stage of the hangman 
* Letters guessed right 
* Letters guessed wrong 
* Currently score 
* Currently number of attempts 
* Input to guess a letter or a full word

### Hangman Stage 2 

![Hangman Stage 2 ](./assets/images/readme/hangman-feature-6.jpg)<br><br>
  Any time the player guess a wrong letter the hangman begin building step by step. 
* 1 letter guessed wrong and the player will see the hangman and a rope in green.

### Hangman Stage 3

![Hangman Stage 3](./assets/images/readme/hangman-feature-7.jpg)
* 2 letters guessed wrong and the player will see the hangman, rope and the head in green.

### Hangman Stage 4

![Hangman Stage 4](./assets/images/readme/hangman-feature-8.jpg)
* 3 letters guessed wrong and the player will see the hangman, rope, head and torso in yellow.

### Hangman Stage 5

![Hangman Stage 5](./assets/images/readme/hangman-feature-9.jpg)
* 4 letters guessed wrong and the player will see the hangman, rope, head, torso and the right arm in yellow.

### Hangman Stage 6

![Hangman Stage 6](./assets/images/readme/hangman-feature-10.jpg)
* 5 letters guessed wrong and the player will see the hangman, rope, head, torso and both arms in red. Also an alert with the message "Danger Zone" will be displayed.

### Hangman Stage 7

![Hangman Stage 7](./assets/images/readme/hangman-feature-11.jpg)
* 6 letters guessed wrong and the player will see the hangman, rope, head, torso, both arms and left leg in red. Also an alert with the message "Danger Zone" will be displayed.

### Hangman Stage 8 / Lose

![Hangman Stage 8 / Lose](./assets/images/readme/hangman-feature-12.jpg)
* 7 letters guessed wrong and the player will see the full hangman and the game is over. 

### Hangman Stage 9 / Win

![Hangman Stage 9 / Win](./assets/images/readme/hangman-feature-13.jpg)
* If the player guessed the full word letter by letter will see this feature and will win the game and get 200 points

### Hangman Stage 10 / Win

![Hangman Stage 10 / Win](./assets/images/readme/hangman-feature-14.jpg)
* If the player guessed the full word at once or at least no more that 3 letters guessed right before try to guess the full word will see this features and will win the game and get 500 extra points.

### Menu Options

![Menu Options](./assets/images/readme/hangman-menu.jpg)
* In the end of the game users will have access to the menu where they can choose from this options: 
[A] - Play Again 
[B] - Leaderboard
[C] - Exit Game

### Leaderboard
![Leaderboard](./assets/images/readme/hangman-leaderboard.jpg)
* The players can check the 15 best scores made by others users on the leaderboard.

### Exit Game
![Exit Game](./assets/images/readme/hangman-exit-game.jpg)
* The players will see this message if the will chose exit the game by typing [C].

## Future Features
  

## How to Play
![How to Play](./assets/images/readme/hangman-explanation-1.jpg)<br>
 The player will have to guess the the right word by inputting letters or the full word, chosen by the computer randomly from a list. 
* When the game starts the player can see how many letters is in the word [1] and the computer will ask the player to input a letter or a word [7].
* If the player guesses a right letter will see the letter displayed in the word length[3], the hangman stage will remain the same[2] and the score will increase by 25 point[5]
* If the player guesses a wrong letter will see the letter displayed in the wrong letters guesses[4], the hangman stage will turn to the next stage[2] and the number of attempts will decrease by 1 [6]

#### Right Answer
![Right Answer](./assets/images/readme/quiz-land-right-answer.png)
* When the user answers the question right the message "Right Answer" will appear on the top center [7] and the background color of their choice answer will turn green [8].

#### Wrong Answer
![Wrong Answer](./assets/images/readme/quiz-land-wrong-answer.png)
* When the user answers the question wrong the message "Wrong Answer" will appear on the top center [9] and the background color of their choice answer will turn red [10].

## Technologies Used
### Languages Used 

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
* [javaScript](https://www.javascript.com/)

### Frameworks - Libraries - Programs Used

* [Google Fonts](https://fonts.google.com/)
   * Google fonts were used to import the 'Roboto' font throughout the style.css.
* [Font Awesome](https://fontawesome.com/)
    * Font Awesome are used as an icons for user UX purposes.
* [Git](https://git-scm.com/)
    * Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
* [GitHub](https://github.com/)
    * GitHub is used to store the project's code after being pushed from Git.
* [VSCode](https://code.visualstudio.com/)
    * VSCode was used to create and edit the website.
* [Mobile Simulator](https://chrome.google.com/webstore/detail/mobile-simulator-responsi/ckejmhbmlajgoklhgbapkiccekfoccmk)
    * Mobile Simulater was used to test the website on a mobile device.
* [PIXLR](https://pixlr.com/pt/)
    * PIXLR was used to create, modify and resize all images on this website.
* [Canva](https://www)
   * Canva was used to create wireframe, the 3 background images and also the Favicon.
  
## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

### [W3C Markup Validator](https://validator.w3.org)
#### Results:
* [HomePage](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Findex.html)
* [Game 1](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Fgame-1.html)
* [Game 2](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Fgame-2.html)
* [Game 3](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Fgame-3.html)
* [Game End](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Fgame-end.html)
* [Trophy Gold](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Ftrophy-gold.html)
* [Trophy Silver](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Ftrophy-silver.html)
* [Trophy Bronze](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Ftrophy-bronze.html)
* [High Scores](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fpages%2Fscores.html)
  

### [W3C CSS Validator](https://jigsaw.w3.org/css-validator) 
#### Results:
* [Main CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fassets%2Fcss%2Fmain.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
* [Responsive CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpedrocristo.github.io%2Fportfolio_project_2%2Fassets%2Fcss%2Fresponsive.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### [Jshint](https://jshint.com/)

![Jshint Result](./assets/images/readme/jshint_result.jpg).
  

The testing was done using the Google Chrome Browser. Chrome Developer Tools was used extensively, particularly to check responsiveness on different screen sizes. Testing was also done using Firefox on desktop, and again on Google Chrome and Opera on the Huawei P20.

* Responsive on all device sizes between 320px - 2600px wide

* Devices tested using the Google Developer Tools emulator

    * BlackBerry Z30 (360px x 640px)  
    * BlackBerry PlayBook (600px x 1024px)  
    * Samsung Galaxy Note 3 (360px x 640px) 
    * Samsung Galaxy S3 (360px x 640px) 
    * Samsung Galaxy S8 (360px x 740px)   
    * Samsung Galaxy S9+(320px x 658px) 
    * Samsung Galaxy Tab S4(712px x 1138px) 
    * LG Optimus L70 (384px x 640px)
    * Microsoft Lumia 550 (640px x 360px) 
    * Microsoft Lumia 950 (360px x 640px) 
    * Motorola G4 (360px x 640px)
    * Nexus 4 (384px x 640px) 
    * Nokia Lumia 520 (320px x 533px) 
    * Nokia N9 (480px x 854px) 
    * Pixel 3 (393px x 786px)
    * Apple iPad Mini (468px x 4024)
    * Apple iPhone 4 (320px x 480px)
    * Apple iPhone 5/S (320px 568px)
    * Apple iPhone 6/7/8 (375px x 667px)
    * Apple iPhone 6/7/8 Plus (414px x 736px)
    * Apple iPhone X (375px x 812px)
  
### Lighthouse 

 Lighthouse was used to test Performance, Best Practices, Accessibility and SEO on both Desktop and Mobile devices. 

* Desktop Results:

  ![Lighthouse Destop Result](./assets/images/readme/lighthouse_desktop_result.jpg).

* Mobile Results:

  ![Lighthouse Mobile Result](./assets/images/readme/lighthouse_mobile_result.jpg).

## Functionality
* All links have been hovered and clicked to ensure accessibility.
* Pages all load correctly on all device screen sizes.
* All social media links work correctly and open a new tab.
* All the buttons are working correctly and bring the users to the function that they were built for.
* The game is working correctly the question comes at the right time and it gives a reply back to the user when answered. 
* The score has no issues and it increases by 25 points any time the user gives a right anwser. 
* The progress bar and question counter have also no issues, the background color increases (from 0% to 100%) and the number of questions also increases any time the user chooses an anwser.


## Bugs 
### Text Overlaping Mobile Devices
![Text Overlaping Mobile Devices](./assets/images/readme/quiz-land-mobile-issue.jpeg)
* I had this issue with my project when I built the layout for the Quiz Page as they are many elements in the same page.<br>

### Fix Bug
![Fix Bug](./assets/images/readme/quiz-land-bug-mobile-fixed.png)
* I had to add media queries for portrait and landscape to avoid this issue happening.<br>

## Deployment of This Project

The website development was created in the "main" branch. This branch was deployed using GitHub Pages.

* This site was deployed by completing the following steps:

1. Open [GitHub](https://github.com/).
2. Click on the project to be deployed.
3. Navigate to the "Settings".
4. Navigate down to the "GitHub Pages".
5. Click on "Check it out here!".
6. Select the "main" branch and select "Save".
7. The link to the live website was ready on the top.

## Forking This Project

* Fork this project following the steps:
-
1. Open [GitHub](https://github.com/).
2. Click on the project to be forked.
3. Find the 'Fork' button at the top right of the page.
4. Once you click the button the fork will be in your repository..

## Cloning This Project

* Clone this project following the steps:

1. Open [GitHub](https://github.com/).
2. Click on the project to be cloned.
3. You will be provided with three options to choose from, HTTPS, SSH or GitHub CLI, click the clipboard icon in order to copy the URL.
4. Once you click the button the fork will be in your repository.
5. Open a new terminal.
6. Change the current working directory to the location that you want the cloned directory.
7. Type 'git clone' and paste the URL copied in step 3.
8. Press 'Enter' and the project is cloned.

## Credits

### Information Sources/Resources

* [W3Schools](https://www.w3schools.com/)

* [Stack Overflow](https://stackoverflow.com/)
  
* The JavaScript code for the Fancy Text Animation used in the Homepage was taken from the following tutorial:<br>[Dev ED](https://www.youtube.com/watch?v=GUEB9FogoP8)

## Content

* All the questions provided in the game were taken from 2 online quizzes.
* [Lovatts & Puzzles](https://lovattspuzzles.com/).
* [Britannica Quiz](https://www.britannica.com/).

  
## Special Thanks

 * Special thanks to my mentor Sandeep Aggarwal, my colleagues at Code Institute, Kasia Bogucka and Mairéad Gillic for their assistance throughout this project.
