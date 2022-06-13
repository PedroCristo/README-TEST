# Tasty Blog

# Introduction
Project milestone 4 for Code Institute Full-stack development program: Django Framework.
This project is a Full Stack website built using the Django framework. Tasty Blog is a recipe book where users can look or search for a recipe to prepare and if they are login they can also like/unlike, comment on a post and upload or update their user image and details. As a user admin, they can post new recipes, approve comments and add new authors.


[Live Project Here](https://tasty-blog-portfolio-project-4.herokuapp.com/)


<p align="center"><img src="./assets/images/readme/features/tasty_blog_responsiveness.jpg" alt="Tasty Blog webpage on multiple devices"></p>

## README Table Content

- [Tasty Blog](#tasty-blog)
- [Introduction](#introduction)
  - [README Table Content](#readme-table-content)
  - [User Experience - UX](#user-experience---ux)
    - [User Stories](#user-stories)
  - [Design](#design)
      - [Colours](#colours)
      - [Typography](#typography)
      - [Imagery](#imagery)
    - [Wireframes](#wireframes)
  - [Database Diagrama](#database-diagrama)
  - [Features](#features)
    - [Home Page](#home-page)
    - [Home Page - Highilights Posts](#home-page---highilights-posts)
      - [About Page](#about-page)
    - [Blog Page](#blog-page)
    - [Post Detail Page - Top](#post-detail-page---top)
    - [Post Detail Page - Steps](#post-detail-page---steps)
    - [Post Detail Page - Comments](#post-detail-page---comments)
    - [Contact Page](#contact-page)
    - [Categories Page](#categories-page)
    - [Categories **Results**](#categories-results)
    - [Search Page](#search-page)
    - [Search Results Page](#search-results-page)
    - [Search Results - Input Empty](#search-results---input-empty)
    - [Search Results - No Results Found](#search-results---no-results-found)
    - [Signup Page](#signup-page)
    - [Login Page](#login-page)
    - [Logout Page](#logout-page)
    - [User Profile Page](#user-profile-page)
    - [Navbar](#navbar)
    - [Footer](#footer)
    - [Messages and Interaction With Users](#messages-and-interaction-with-users)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
      - [Django Packages](#django-packages)
    - [Frameworks - Libraries - Programs Used](#frameworks---libraries---programs-used)
  - [Testing](#testing)
    - [PEP 8 Online](#pep-8-online)
    - [Lighthouse](#lighthouse)
  - [Functionality](#functionality)
  - [Bugs](#bugs)
    - [Python Lines too Long](#python-lines-too-long)
    - [Fixed Bug](#fixed-bug)
  - [Creating the Django app](#creating-the-django-app)
  - [Deployment of This Project](#deployment-of-this-project)
  - [Final Deployemt](#final-deployemt)
  - [Forking This Project](#forking-this-project)
  - [Cloning This Project](#cloning-this-project)
  - [Credits](#credits)
    - [Content](#content)
    - [Information Sources / Resources](#information-sources--resources)
  - [Special Thanks](#special-thanks)

## User Experience - UX

### User Stories
A list of my user stories and their tasks can be found
[here](https://github.com/PedroCristo/portfolio_project_4/issues)

* As a website user, I can:
1. Navigate around the site so that I can easily view desired content.
2. View a list of recipes so that I can choose one to read.
3. Search recipes so that I can find specific recipes I'm looking for.
4. Click on a recipe so that I can read the recipe details.
5. Register for an account so that I can begin to use the services afforded to members

* As website user login, I can:
1. Like/unlike recipes so that I can mark which recipes I enjoyed.
2. View the number of likes on a recipe so that I can see which is most popular.
3. View comments on recipes so that I can read other user's opinions.
4. Comment on recipes so that I can give my opiniom about the posts.
5. log in/out so that I can like recipes, comment on recipes and manage my profile.
  
## Design

#### Colours
* The colours in the game are supplied by the Python Colorama Model

#### Typography
* The Lato font is used as the main font for the whole project  and the Kaushan font is used to show the word enjoy in the Post Details and About pages.
  
#### Imagery
* All the imagery will be related to recipes and website design with only 7 images being static. The rest will be uploaded by the author in the database.

### Wireframes
Wireframes for this project [here](WIREFRAMES.md)

## Database Diagrama
![Database Diagrama](./assets/images/readme/extras/tasty_blog_database_diagrama_1.jpg)<br>

## Features

### Home Page

![Home Page](./assets/images/readme/features/tasty_blog_home-page.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>

### Home Page - Highilights Posts

![Home Page - Highilights Posts](./assets/images/readme/features/tasty_blog_home_page_highilights-.jpg)
* In the highlighted posts, users can watch a selection of 6 recipes, chosen by the site admin by clicking the featured box in the post database.<br>

#### About Page
![About Page](./assets/images/readme/features/tasty_blog_about_page.jpg)
* On the About Page, users can read information about the Tasty Blog website as the main purpose and the main goal of the blog. This is basically a way to introduce the website to the users.<br>

### Blog Page
![Blog Page](./assets/images/readme/features/tasty_blog_page.jpg)
* On the Blog Page, users can have access to the whole recipes posts available on the website and choose anyone to see the recipe detail by clicking on the card.<br>
  
### Post Detail Page - Top
![Post Detail Page - Top](./assets/images/readme/features/tasty_blog_post_detail_1_page.jpg)
* At the top of the Post Details Page, users can see the post's main image and have access to information about the post such as category, recipe name, rating stars, time to prepare, author name and image, and posted date, like unlike the post and how many likes and comments.<br>
  
### Post Detail Page - Steps
![Post Detail Page - Steps](./assets/images/readme/features/tasty_blog_post_detail_2_page.jpg)
* In this page section, users can read the ingredients and follow the steps to conclude the recipe.<br>
  
### Post Detail Page - Comments
![Post Detail Page - Comments](./assets/images/readme/features/tasty_blog_post_detail_comments_page.jpg)
* At the bottom of this page, users can read the comments posted by other users and if they are login they are allowed to comment and delete comments posted by themselves.<br>

### Contact Page
![Contact Page](./assets/images/readme/features/tasty_blog_contact_page.jpg)<br><br>
* On the Contact Page, users can have access to the Tasty blog contact and also send an email by sending a contact form available on this page.

### Categories Page
![Categories Page ](./assets/images/readme/features/tasty_blog_categories_page.jpg)<br><br>
* On the Categories Page, users can see the categories available in the blog and filter the posts by category.

### Categories **Results**
![Categories Results Page](./assets/images/readme/features/tasty_blog_categories_results_page.jpg)
* On the Categories Results Page, users can access to the post filtered by the category chosen.

### Search Page
![Search Page](./assets/images/readme/features/tasty_blog_search_page.jpg)
* In this box, the users can do a search by inputting a keyword in the input and trying to find the recipe they are looking for.
  
### Search Results Page
![Search Results Page](./assets/images/readme/features/tasty_blog_search_results_page.jpg)
* On the Search Results Page, users can see the recipes found by their search and go to the Post Details Page by clicking on the card result.
  
### Search Results - Input Empty
![Search Results - Input Empty](./assets/images/readme/features/tasty_blog_search_results_empty_page.jpg)
* On the Search Results Page - Input Empty, users will see this message if they do a search with an empty input.
  
### Search Results - No Results Found
![Search Results - No Results Found](./assets/images/readme/features/tasty_blog_search_results_null_page.jpg)
* On the Search Results Page - No Results Found, users will see this message if there is nothing found for the search.
  
### Signup Page
![Signup Page](./assets/images/readme/features/tasty_blog_signup_page.jpg)
* On the Signup Page, a new user can sign up for the Tasty Blog website by filling out the form and submit.
  
### Login Page
![Login Page](./assets/images/readme/features/tasty_blog_login_page.jpg)
* On the Login Page, users can log in to the website and have access to their Profile Page, upload a user image, comment on a post, delete a comment and like/unlike a recipe.
  
### Logout Page
![Logout Page](./assets/images/readme/features/tasty_blog_logout_page.jpg)
* 3O the Logout Page, users can confirm that they wanna exit the website.
  
### User Profile Page
![User Profile Page](./assets/images/readme/features/tasty_blog_user_profile_page.jpg)
* On the Profile Page, users can have access to their own information and update their user name, email and profile image.
  
### Navbar
![Navbar](./assets/images/readme/features/tasty_blog_navbar.jpg)
* The navigation bar is present at the top of every page and houses all links to the various other pages.
* The options to Register or Log in will change to the option to log out once a user has logged in.
* Once a user has signed in, more options such as profile page and user image will be available in the navbar.
* A search icon is nested in the navbar and once clicked it will open the search box.
* The navbar is fully responsive, collapsing into a hamburger menu when the screen size becomes smaller.
  
### Footer
![Footer](./assets/images/readme/features/tasty_blog_footer.jpg)
*On the website footer, users can see basic information about the blog such as contact, social media, copyright, and quote about food recipes.

### Messages and Interaction With Users

![Sign up](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_signup.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Login](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_login.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Logout](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_logout.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Profile Update](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_profile_update.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Loke Post](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_like_post.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Unlike Post](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_unlike_post.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Comment](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_comment_sent_1.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Comment](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_comment_sent_2.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Delete Comment](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_comment_delete_1.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Delete Comment](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_comment_delete_2.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Delete Comment](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_comment_delete_3.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Email Sent](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_email_sent.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Email Sent](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_email_sent_2.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![Empty Search](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_profile_empty_search.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>
* 
![No Search Found](./assets/images/readme/features/interactive_messages/tasty_blog_user_interaction_profile_no_search_found.jpg)
* The hero image welcomes the user with a short message advertising what the website is about. These are 3 images of a carousel with a button that once is pressed brings the user down to the highlighted recipes.<br>

## Technologies Used
### Languages Used 

* [HTML 5](https://en.wikipedia.org/wiki/HTML/)
* [CSS 3](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://www.javascript.com/)
* [Django](https://www.python.org/)
* [Python](https://www.djangoproject.com/)

#### Django Packages

* [Gunicorn](https://gunicorn.org/) as the server for Heroku
* [Cloudinary](https://cloudinary.com/) was used to host the static files and media
* [Dj_database_url](https://pypi.org/project/dj-database-url/)to parse the database URL from the environment variables in Heroku
* [Psycopg2](https://pypi.org/project/psycopg2/) as an adaptor for Python and PostgreSQL databases
* [Summernote](https://summernote.org/) as a text editor
* [Allauth](https://django-allauth.readthedocs.io/en/latest/installation.html) for authentication, registration, account management
* [Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/) to style the forms
  
### Frameworks - Libraries - Programs Used

* [Bootstrap](https://getbootstrap.com/)
    * Was used to style the website, add responsiveness and interactivity
* [Jquery](https://jquery.com/)
    * All the scripts were written using jquery library
* [Git](https://git-scm.com/)
    * Git was used for version control by utilizing the Gitpod terminal to commit to Git and push to GitHub
* [GitHub](https://github.com/)
    * GitHub is used to store the project's code after being pushed from Git
* [Heroku](https://id.heroku.com)
    * Heroku was used to deploy the live project
* [PostgreSQL](https://www.postgresql.org/)
    * Database used through heroku.
* [VSCode](https://code.visualstudio.com/)
    * VSCode was used to create and edit the website
* [Lucidchart](https://lucid.app/)
    * Lucidchart was used to create the database diagrama
* [PEP8](http://pep8online.com/)
    * PEP8 was used to validate all the Python code
* [W3C - HTML](https://validator.w3.org/](https://validator.w3.org/))
    * W3C- HTML was used to validate all the HTML code
* [W3C - CSS](https://jigsaw.w3.org/css-validator/)
    * W3C - CSS was used to validate the CSS code
* [Fontawesome](https://fontawesome.com/)
    * To add icons to the website
* [Google Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)
    *  To check reponsiveness and contrast and JS errors in the console
* [Google Fonts](https://fonts.google.com/)
    * To add the 2 fonts using in the project
* [Balsamiq](https://balsamiq.com/)
    * To build the wireframes for the project
  
## Testing

### PEP 8 Online

The [PEP8](http://pep8online.com/) Validator Service was used to validate every Python file in the project to ensure there were no syntax errors in the project.

![PEP8](./assets/images/readme/features/hangman-pep8-results.jpg).
* No errors or warnings were found during the testing of the code in PEP8
  
### Lighthouse 

 Lighthouse was used to test Performance, Best Practices, Accessibility and SEO on Desktop. 

* Desktop Results:

  ![Lighthouse Result](./assets/images/readme/features/hangman-lighthouse.jpg).


## Functionality 
* The terminal has no issues and is working properly 
* The typewriter starts typing at the right time and is working correctly 
* The input for name and city have the right behaviour and shows the user an alert if the input is empty
* The game rules appear without any issues after the player submits their name and city
* The option to press any key to start a game is running well
* The game runs without any issues and as expected 
* At the end of the game the Leaderboard is updating correctly
* All the menu options are working without any fails

## Bugs 
### Python Lines too Long
![Lines to long](./assets/images/readme/features/hangman-issue.jpg)
![Lines to long](./assets/images/readme/features/hangman-issue-result.jpg)

* When I first built the ASCII art for the logo I got the warning "line too long (126 > 79 characters)" from PEP8.<br>

### Fixed Bug
![Fix Bug](./assets/images/readme/features/hangman-issue-fixed.jpg)
* I had to rebuild the logo using the program  Patorjk (ASCII Art Generator) to avoid these issues.

## Creating the Django app
* Go the the Code Institute Gitpod Full Template [Template](https://github.com/Code-Institute-Org/gitpod-full-template)
* Clik on Use This Template
* Once the template is available in your repository click on Gitpod
* When the image for the template and the Gitpod are ready open a new terminal to start a new Django App
* Install Django and gunicorn: pip3 install django gunicorn
* Install supporting database libraries dj_database_url and psycopg2 library: pip3 install dj_database_url psycopg2
* Create file for requirements: in the terminal window type pip freeze --local > requirements.txt
* Create project: in the terminal window type django-admin startproject your_project_name 
* Create app: in the terminal window type python3 manage.py startapp your_app_name
* Add app to the list of installed apps in settings.py file: you_app_name
* Migrate changes: in the terminal window type python3 manage.py migrate
* Run the server to test if the app is installed, in the terminal window type python3 manage.py runserver
* If the app has been installed correctly the window will display The install worked successfully! Congratulations!
## Deployment of This Project

* This site was deployed by completing the following steps:

1. Log in to [Heroku](https://id.heroku.com) or create an account
2. On the main page click the button labelled New in the top right corner and from the drop-down menu select Create New App
3. You must enter a unique app name
4. Next select your region
5. Click on the Create App button
6. Click in resources and select Heroku Postgres database
7. Click Reveal Config Vars and add a new record with SECRET_KEY
8. Click Reveal Config Vars and add a new record with the CLOUDINARY_URL
9. Click Reveal Config Vars and add a new record with the DISABLE_COLLECTSTATIC = 1
10. The next page is the project’s Deploy Tab. Click on the Settings Tab and scroll down to Config Vars
11. Next, scroll down to the Buildpack section click Add Buildpack select python and click Save Changes
12. Scroll to the top of the page and choose the Deploy tab
13. Select Github as the deployment method
14. Confirm you want to connect to GitHub
15. Search for the repository name and click the connect button
16. Scroll to the bottom of the deploy page and select the preferred deployment type
17. Click either Enable Automatic Deploys for automatic deployment when you push updates to Github

## Final Deployemt
1. Create a runtime.txt "python-3.8.13"
2. Create a Procfile "web: gunicorn your_project_name.wsgi"
3. When development is complete change the debug setting to: DEBUG = False in settings.py
4. In this project the summernote editor was used so for this to work in Heroku add: X_FRAME_OPTIONS = 'SAMEORIGIN' to settings.py.
5. In Heroku settings config vars delete the record for DISABLE_COLLECTSTATIC

## Forking This Project

* Fork this project by following the steps:

1. Open [GitHub](https://github.com/PedroCristo/portfolio_project_4)
2. Find the 'Fork' button at the top right of the page
3. Once you click the button the fork will be in your repository

## Cloning This Project

* Clone this project by following the steps:
  
1. Open [GitHub](https://github.com/PedroCristo/portfolio_project_4)
2. You will be provided with three options to choose from, HTTPS, SSH or GitHub CLI, click the clipboard icon in order to copy the URL
3. Once you click the button the fork will be in your repository
4. Open a new terminal
5. Change the current working directory to the location that you want the cloned directory
6. Type 'git clone' and paste the URL copied in step 3
7. Press 'Enter' and the project is cloned

## Credits

### Content

* All other food images were taken from [BBC Goodfood](https://www.bbcgoodfood.com/recipes)
* Most of the images were taken from [Unsplash](https://unsplash.com/)
* The Tasty Blog logos and favicon were designed and build by myself

### Information Sources / Resources

* [W3Schools - Python](https://www.w3schools.com/python/)
* [Stack Overflow](https://stackoverflow.com/)
* [Scrimba - Pyhton](https://scrimba.com/learn/python)


## Special Thanks

  * Special thanks to my mentor Sandeep Aggarwal, my colleagues at Code Institute, Kasia Bogucka, and Mairéad Gillic for their assistance throughout this project.
