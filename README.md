<img src="static/images/mock-up-responsive.jpg">

# BouquetBlooms

*Subscribe to have fresh BouquetBlooms everyday*

*Deployed to [Heroku](https://flask-saute-and-skewers.herokuapp.com/) and stored in [Github](https://github.com/)*

<hr>

## Contents

- [Introduction](#introduction)
- [Aim](#aim)
- [Purpose](#purpose)
- [UX](#ux)
- [Planes](#planes)
- [Features](#features)
- [Technologies](#technologies)
- [Testing](#testing)
- [Evaluation](#evaluation)
- [Deployment](#deployment)
- [Credits](#credits)
- [Acknowledgements](#acknowledgements)

<hr>

## Introduction

................................................

<hr>


### Aim

To create a full stack website that allows users to purchase a product or service.

Technologies to be used in the project are HTML/CSS/Javascript/Python/Django.


### Purpose

BouquetBlooms is a floristry website in which users can subscribe have fresh bouquets of flowers delivered to them.

All users to the site will see the websites services. However only registered users can subscribe.


<hr>


## UX

## User stories

There are three types of users for this website, 'User Stories' for each user are discussed below:

### Guest User

As a guest user I want to:
 - navigate around the site easily.
 - find a navigation bar that links to other pages when clicked. 
 - understand the sites purpose upon landing.
 - be able to view various content on the site.
 - be able to click social media icons to link out to other BouquetBlooms pages.
 - have the option to register to the site to be able to interact with the site and to see more.

### Registered Account

As a registered user I want to:
 - see all site content.
 - log into the site easily.
 - log out successfully.
 - have buttons to click to login, log out and submit data.
 - review the services before purchasing.
 - be able to add services to my basket.
 - recieve and email when ive purchased something.
 - be able to cancel a subsription if I change my mind.
 - be notified of all my interactive actions.

### Admin User

As an admin user I want to:
- have full access to the site to ensure all content is viable.
- have access to be able to add more subscription offers to the site.
- edit any content posted by me.


### Website Owner

The website owner would like users of the website to:
-  Interact with the site.
-  Enjoy the site.
-  Find the site easy to register to and purchase services.
-  Contribute to the site to create a vast selection of interesting data.

The website owner would like the website design to: 
- be clean and crisp with visuals that use the ......
- have professional images that creates an instant attraction to the site.
- have whitespace to create flow.
- be easy to navigate.
- have a footer containing social media icon links.
- show the sites headquarters address.

<hr>


## The 5 Planes of content strategy

### Strategy

- BouquetBlooms is an e commerce website. It allows users to purchase a service. 
  This service in in the form of a subscription.
- It features the 3 core languages of web development HTML, CSS and Javascript, as well as Python and Django. 
- The project uses a ...................... database. 
- There is a clear brand to the site that draws users and entices further interaction.
- Users who discover BouquetBlooms, ........................
- BouquetBlooms has the potential of not only being a content sharing site, it could potentially become a business site. 
  Adding a few additional features and marketing the site well could mean BouquetBlooms could generate more revenues.
- During research there were other sites found that had the same 'subscription' concept, but most offered a full inventory of products. 


### Scope 

- The site was developed with the intention of allowing users to build a database of their own recipes.
- The database of choice to build with was NoSQL - MongoDB.
- It was scoped to provide ease of use.
- Needed to have the CRUD functionality.
- Must house a home page, registration page, log in page, log out page.
- Be responsive on all devices.
- Be visually appealing that incorporated Greek culture in the front-end design.


### Structure

- BouquetBlooms site structure was created from the UX user stories - therefore developed with pages that were required to enable users to sign up and add data.
- All pages are designed identically with 3 sections - a navbar, content area and a footer.
- The Home page has 'Welcome' text that introduces the site. An 'About Us' section that gives instruction to join. A main image and 3 smaller images. 
- The Highlights page shows a selection of recipe content and images for all users to view. This can be updated and/or changed - as and when the owner wants.
- The Register page has a basic registration form with a button and a link to login if already registered.
- The Login page has a basic login form with a button and a link to register if not already a member. 
- Once logged in the Login page opens a Profile page, this shows a 'Welcome Back' text, a few enticing words and a links to the 'Add Recipe' 'Highlights' 'Recipes' Pages.
- The Add Recipe page is where users can add their own recipes. There is a form to complete and a 'Add Recipe' button to submit their recipe. 
  Once the recipe is submitted the user is redirected to the Recipes page with a flash message 'Recipe Successfully Added' here the user can see their new entry.
- The Recipes page is the home of user recipes already added. This is data stored in the MongoDB database.
- If logged in, a user can see all recipes in the database, with functionality to 'edit' or 'delete' their own.
- If the user wants to 'Edit' a recipe they created, they can click on the edit button and it will take them to the 'Edit Recipe' Page.
- The Edit Recipe page mirrors the Add Recipe page, however this has an additional 'Cancel' button in case the user changes their mind.
- If the user wants to 'Delete' an entry, they can click the 'Delete' button and the recipe will be deleted. The user is advised with a flash message 'Recipe has been deleted'.
- Users can only Edit or Delete their own recipes, buttons are not active on other users entries.
- Finally the Log Out page displays, a 'You have been logged out message' and the returns to the Log In page view.

### Skeleton

- Initially four wireframes where created - the three main pages of the site and a subscription page.
- These Desktop and Mobile wireframes demonstrate the basic design and structure of the site and the required elements each page needed. 
- All wireframes were created using [Balsamiq](https://balsamiq.com/wireframes/).

Desktop:

[Home](wireframes/base-desktop.png)
[Register](wireframes/register-desktop.png)
[Login](wireframes/login-desktop.png)
[Subscription](wireframes/subscription-desktop.png)

Mobile:

[Home](wireframes/base-mobile.png)
[Register](wireframes/register-mobile.png)
[Login](wireframes/login-mobile.png)
[Subscription](wireframes/subscription-mobile.png)

### Surface 

Front-end visuals where based on:
 - A great brand design.
 - .............. colours.
 - ......... images.
 - Enlightening and positive text.
   It is anticipated that the user would feel positive on landing on the site ......

The typography colours and fonts where important to promote ............, with a tempting, feel good reaction.
With flowers....... symbolic colours ....., the sites aim was to incorporate this into its design. 

BouquetBlooms chose a simplistic design with ample whitespace so to not overpower the user.

 - colour: rgb(2, 32, 114)  - from Colorcodehex 
 - font: '........' - from Google Fonts

<hr>

## Features 

### Existing Features

**Multiple pages:** The site has multiple responsive pages, using the mobile first approach. 

**User friendly:** Each page has its own purpose and uses a simple mouse movement on desktop and scroll movement on mobiles and tablets to provide easy navigation. 

**Fonts and Colours:** Simplistic design incorporating only minimal colour and text.

**Navbar:** A Bootstrap fixed Navbar at the top on desktop and a side navbar on mobiles and tablets. The navbar links to the site pages, this changes dependent on the users status: Logged in, Logged out.

**Button:** Chosen from Bootstrap the buttons when clicked do something and confirm user actions. Buttons are big and small an over different colours and provide 'word' instruction. 

**Forms:** Code from Bootstrap. The Register, Log In, Add Recipe and Edit Recipe pages all have forms on that are required to be completed. The forms are self explanatory.
They have a drop down, so the user can select a recipe category. They also have input fields and textareas that are set with min-length and max-length classes.

**Icons:** Font Awesome icons are used on the form fields to provide instructions aswell as for design. 

**Images:** Bold and relevant images are used in the design. Selected images provide a luxury feel.

**Hyperlinks:** There is a hyperlink on the 'Register page', 'Login page' and 'Profile page' to redirect users to an alternative area dependent on their next wanted action.

**Flash Messages:** Flash messages provide feedback to users. Users that have an unsuccessful login will receive the message "Incorrect Username and/or Password".
The 'Registered users' will see, "Welcome, USERNAME" on login and on logging out user will receive the message "You have successfully logged out".
Flash messages are also used for confirming a recipe has been added, edited and deleted.

**Favourites Toggle:** A Favourites Toggle for the user to highlight if a recipe is a user favourite.

**Footer:** The footer provides a clear indication of the end of the page.

**Social Media Links:** BouquetBlooms has various Social Media accounts therefore icons for these are found in the footer that will direct to the social site.

**Copyright:** Copyright logo - hosts the website owners own work.

### Future Features

BouquetBlooms - Future features could include:

- Having a larger database of subscription packages for guest users to view and purchase.
- The subscriptions could be seasonal, have different price points ........
- An image field on Add Recipe page where users can upload images of their own Greek foods to their recipes.
- User profile to be extended to allow users to upload images and information about themselves that other registered users can view.
- Have a logo, that takes the BouquetBlooms text into something more memorable.
- Add a favicon so the sites logo is displayed in the browser tab for ease of navigation.
- Have a 'Search' bar, so users can search for specific recipe using key words.
- A badge or icon level that registered users of the site could achieve, when 'X' number of entries have been added - i.e - Top Top Contributor.
- A review score or like element that the community of users can click on, if they like or have tried a recipe posted by others.
- Response section to provide users with feedback on added recipes.
- Forgotten password feature, so passwords can be reset.
- A blog that gives advise and learnings on floristry.
- A messenger area where registered users can chat to a company employee live on the site.
- Expand the e commerce shop where users could order one time products and merchandise.

<hr>

## Technologies and Frameworks 


#### Technologies
- [HTML](https://www.w3schools.com/whatis/whatis_html.asp)
- [CSS](https://www.w3schools.com/css/css_intro.asp)
- [Javascript](https://www.w3schools.com/whatis/whatis_js.asp)
- [Python](https://www.python.org/doc/essays/blurb/)
- JSON

#### Frameworks
- [Django](https://...................../)
    - The web application framework used in the project to ...........................

- [Werkzeug](https://palletsprojects.com/p/werkzeug/)
    - A web application library in Flask that was used to for secure authentication using password hashing.

- [Bootstrap](https://.............com/)
    - A web based front-end framework that assists in responsiveness and styling that was used throughout the project.

- [JQuery](https://jquery.com/)
    - The JavaScript library used within the Materialize framework.

#### Database
- [........](https://www................../)
    - A document based database and the type of database used when developing this project

#### Text Editor
- [Gitpod](https://gitpod.io/)
    - A cloud based IDE, that uses prebuilt workspaces.

#### Version Control
- [Git](https://git-scm.com/)
    - Version control system that works within the Gitpod terminal. Used to commit and push recent code to GitHub.

#### Hosting Platform
- [Heroku](https://https://dashboard.heroku.com/)
    - The application platform used for the live deployed site.

- [Github](https://github.com/)
    - A repository store, used to house the sites repository.

#### Developer Tools
- [Google Dev Tools](https://developers.google.com/web/tools/chrome-devtools)

#### Colorcodehex
- [Colorcode](https://www.colorcodehex.com/022072.html)

#### Font Awesome
- [Font Awesome](https://fontawesome.com/)
    - A popular site that provides icons for developers to use for UX.

#### RandomKeygen
- [RandomKeygen](https://www.randomKeygen.com/)
  - Site to select a secure SECRET_KEY password.

#### Validation sites
- [W3C Markup Validation](https://validator.w3.org/)
- [Jshint](https://jshint.com/)
- [PEP8](http://pep8online.com/)


<hr>

## Defensive Design

*Defensive design is the practice of planning for contingencies in the design stage of a project or undertaking. Essentially, it is the practice of anticipating all possible ways that an end-user could misuse a device, and designing the device so as to make such misuse impossible, or to minimize the negative consequences.*
[Wikipedia](https://en.wikipedia.org/wiki/Defensive_design/)

Defensive design was used in the projects 'Form' elements. When entering text to the sites form areas the defensive design can be seen in action.
To ensure the user inputs are correct they are validated by the class 'validate' and the inputs 'minlength', 'maxlength' and 'pattern'.

### Testing

Manual Testing was undertaken during the creation of this site. 
Testing included tests on various devices for responsiveness and UX aswell as testing code for bugs.
Code was validated for best practice.

 - Validation sites used:
   - W3C Markup Validator
   - Jshint
   - Pep8 Compliance

Below highlights the main issues, bugs and validation errors found during the development and how if possible the issues were rectified.
Some errors where not rectified, this was due to either lack of developer knowledge or due to time constraints for further reading of validation documentation and/or testing.


#### Issue 1

Initial issues occurred when working on app.py file. It was difficult to clear the errors Gitpod advised on. 
It was realised this was mostly due to the 2 line spacing rule and using the tab key instead of spaces.

#### Issue 2

Edit and Delete routing was the developers main issue. It was found to be difficult to resolve and threw many Jinja errors. 
Errors where cleared when it was found that Flask routing, route decorators and Pymongo had typo's.   

#### Issue 3

env.py file - the file kept advising on 'lines being to long', with notes referring to flakes and cornflakes. These errors where not all fixed due to lack of knowledge on developers part.

#### Issue 4

app.py file - the file errors with 'env imported but unused' and 'over indented' flake8. Again these errors are not fixed due to lack of developers knowledge.

#### Issue 5

All html templates except base.html return 'Doctype must be declared first' errors. As noted during module exercises prior to development this is acceptable due to the linter Gitpod uses not understanding the template language Jinja. 

*When you save the file you might see a warning on the first line, 'Doctype must be declared first'. We can ignore this as the linter doesn't know how to properly read templating languages like Jinja*
Video: Flask Mini-Project 20 | 01 - Putting The Basics In Place (1e - Template Inheritance) 
[Code Institute](https://codeinstitute.net/)

#### Issue 6

The Recipes page, doesn't error but the developer failed to solve the issue of coding images that where different for each individual recipe. The idea not initially planned for
was to have an image that matched the recipe. Therefore a placeholder image was added for better UX, however this placeholder is the same for every recipe inputted.

#### Issue 7

It was found during development that the site definitely needed more pages adding. The initial four created an inception and wireframing wasn't going to be enough. 
This was to allow for guest users to see more than just the home page and register pages. It was realised the guest user needed to be enticed more. Therefore the Highlights page was created.
Furthermore the registered user required a profile page for when they logged in, and an add recipe, edit recipe and logout page. All additional pages have been created and are suitable for its purpose.

#### Issue 8

The navbar and footer background should have been the same colour. However the developer could not get the colours to match using the Materialize
colour #2196f3 blue. Therefore it was decided to use a deeper blue in CSS file, using ColourPicker :rgb(2, 32, 114). 

#### Issue 9

The inital plan was to utilize a Carousel on the home page (as referenced on the 'base' wireframe), so the site could house a selection of images that had automatic movement. 
The developer chose the Materialize framework for this project, however this feature wasn't loading well and was slow to show images and the links kept breaking therefore it was decided to remove the carousel after various tests that the developer couldn't fix.
In its place one main image was used above 3 small ones. 

#### Issue 10

The image on the Home page is a little large and doesn't sit nicely on the page. On opening the site the bottom of the image is cut off. 
However as the user can scroll further down to see other content it is acceptable. However something for the developer to look into in the future.
The same applies on the Highlights page the images are far too big and need to be reduced in size. Due to time constraints this was not able to be rectified.

#### Issue 11

A Favourites toggle was a feature that was considered at midpoint of the project. The idea being that the registered user could 'mark_favourite' a recipe.
The code was written and the idea was implemented. Unfortunately the developer was unable to get the function to work correctly, one issue was that it upset the alignment on the recipes page (it added the name of the recipe a second time on the page. Not only did it look out of place it also moved the delete button to the right).
Therefore this and due to time constraints to continue to develop and test the code in recipes.html was removed. but left in the add_recipe.html and in edit_recipe.html ready for implentation in the future.
The favourite toggle it still visable on the Add recipe and Edit recipe pages and it can be moved, however it doesnt have a function attached.

#### Issue 12

Google fonts where used throughout development with the CSS font family, set to Arial.
At the end of the project it was decided to use Google font 'import' to use the font 'Texturina' so it had a more Greek text styling, however it was found during final testing that the font wouldn't change. 
Google Dev Tools shows the font is set to *font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;*.
It is believed to be due to a Materialize override, however cannot be concluded due to the lack of knowledge on Materialize documentation. Something the developer will look into in the future.


### Validation sites

- When validating the code for HTML and CSS using [W3C Markup Validation](https://validator.w3.org/), errors where found and some were rectified, rectified errors included simple code errors and typos.
  However there were some errors the developer was unable to fix. Below shows a few examples.
  
  base.html
  - 21 errors found
  
  Error: Parse Error.
    At line 81, column 14
  
  add_recipe.html
  - 6 errors found.
    
  Error: Text not allowed in element select in this context.
    From line 32, column 1; to line 32, column 37    


- [Jshint](https://jshint.com/) for JS validation found error warnings, however many was of the same error. Unfortunately a fix wasn't implemented due to lack of understanding on how to resolve them and to time constraints. 
  Here are the errors for highlight.html
  - 4 errors found.

  Expected a string and instead saw %.
  Expected ':' and instead saw 'extends'.
  Expected '}' and instead saw '%'.
  Unrecoverable syntax error. (1% scanned).

- [PEP8](http://pep8online.com/) was used for testing Python errors.
  There were many errors on most pages, mostly referencing tabs and indentation. Again due to time constraints these errors were not rectified.
  Below are some common examples
    - missing whitespace around operator
    - trailing whitespace
    - indentation contains tabs


### Browsers tested

- Chrome: Using Google Developer Tools - Chrome was used for testing on Laptop, Tablet and Android devices.

- Safari: Safari wasn't used for testing on an I phone or Mac, due to not having physical access to these type of devices. However they were viewed on Google Dev Tools.

### Devices tested

On the final testing session the below devices where used to check if responsive, here are the outcomes.

Mobile:
- Android - Samsung Galaxy A40 - Outcome: All is responsive.
- Android - Samsung Galaxy A20 - Outcome: All is responsive.
- Android - Samsung Galaxy S10 - Outcome: All is responsive.

Laptop:
- Toshiba Satellite C850 - Outcome: All is responsive.
- HP Model I5 - Outcome: All is responsive.

The only responsive bug the developer found was on the [Techsini](https://techsini.com/multi-mockup/) - Responsive Mock up.
On the mock up it shows on I pad that the footer is half way up the page, however in Google Dev Tools this is not the case.
However due to not having an Apple Ipad to physically, it cannot be concluded the site is not responsive.   

<hr>


## Evaluation

- Overall the design and development of this site is suitable for its intended purpose.
- It has all the basic requirements of a functional website and meets CRUD functionality of the project criteria.
- Due to do external commitments additional features have been left out. The developer is aware of aspects that don't function as intended or are not yet could be added.        
- Most of the user stories where met, with the exception of editing user content as an Admin User. In the future this can be looked into and implemented along with the option to delete or block user if required.
- Images on the site are not all suitable for the sites look. It was found to be an issue to find a good selection of free stock professional images of Greek Cuisine.
  This is something that can be changed so it gives the site a better visual. For now some Mediterranean images were used. 
- Many future features could be added to provide more interactive activity, functionality and imagery.
- Branch testing - No branch testing was undertaken, something that the developer was intending to do - however was just overlooked.
- Manual Testing was undertaken and this was found to be successful. It is noted that there are many validation errors that needs to be looked into by the developer at a later date.
- [Werkzeug](https://palletsprojects.com/p/werkzeug/) was used in this project for authentication and secure passwords. This was new to the developer and was found to be interesting and a great tool to be aware of for future projects.
- Some front-end design changes were made during the build due to varying factors:
    - Materialize image carousel, looked good and fitted the sites initial idea but didnt load well. Also the developer found it difficult to change the prebuilt images and the image links kept breaking.
    - The site was to have 4 pages initially but it was discovered early in development that more pages would be required.

<hr>


## Deployment

#### Heroku:

The project is deployed to Heroku. It uses the automatic deployment method via Github, using your Github repository.
Below shows the steps to deploy on Heroku:

1. Heroku requires certain dependencies and applications to run our application. There we need to tell it what is required. 
   In the terminal type 
   - $ pip3 freeze --local > requirements.txt
   - $ echo web: python app.py > Procfile
2. Register on the Heroku website - [Heroku](https://www.heroku.com/) or Log in for existing users.
3. From the dashboard click 'New' and 'Create new app'.
4. Enter your unique 'App name' (Heroku practice is for it to be lowercase and to use hyphen (-) instead of spaces).
5. Select your region, then click 'Create App'.
6. Create app directs to Heroku's 'Deploy' tab, select the deployment method of 'GitHub'.
7. Your Github profile should be displayed, enter your repository name here and click 'Search'. (Idealy your Heroku app name and your repository name should be the same).
8. Your repository should display here and a 'Connect' button appears to connect to your app.
9. Before you click 'Connect', head over to 'Settings' tab and scroll down to the 'Config Vars' section. As we have contained our Environment Variables
   in our env.py file we need to tell Heroku these in a secure manner.
   Add your variables to the below Key/Value pairs:
    - IP
    - PORT
    - SECRET_KEY
    - MONGO_URI
    - MONGO_DBNAME

10. Final step before we connect to Heroku is to push our new files 'requirements.txt' and 'Procfile' to the repository.
    Back in the terminal have a check of the workspace status, type: git status. this will show your new pending files.
    Continue in the terminal and type:
    - $ git add requirements.txt
    - $ git commit -m "Added requirements.txt"
 
   - $ git add Procfile
   - $ git commit -m "Added Procfile"

   - $ git push

11. Go back to Heroku 'Deploy' tab, click 'Enable Automatic Deploys' in the section Automatic Deploys. Finally under Manual Deploy section click 'Deploy Branch'.
    Heroku will now receive the code from GitHub and start building the app using the required packages.
    Once built you will receive the message 'Your app was successfully deployed' then can click 'View' to launch your new app.

12. Your deployed app is now available and should update automatically everytime you push to the Github repository.



#### Github:

In [GitHub](https://github.com/) we can view the repository. 

Should you want to 'Fork' or 'Clone' this repository to use as a base template for your own projects you can do so.
 - To 'Fork':
1. Head to the repository, on the top right click 'fork' button.
   You now have your own copy of the forked repository in your Github account.

If you want to run this project locally, we must clone the project.
- To 'Clone':
1. Under the repository name, click the 'Code' button on the right.
2. A dropdown 'Clone with HTTPs' section appears, here copy the clone URL for the repository.
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone' and paste the URL you copied.

- Example: git clone  = https://github.com/VMBlakelock/saute-and-skewers-greekfood

6. Press Enter. Your local clone is now created.


<hr>


## Credits

Personal credits go out to the following people:
- Spencer Barriball the developer's mentor who guided in the development of the project at inception stage. 

Tutor Support
- Tim Nelson from tutor support who clarified issues within Cloud 9 videos and Gitpod usage.
- Samantha from student support who tried to assist with the routing issues although the issue wasnt solved during the session.
  Samantha guided the developer to look at the areas needed to rectify.
- Michael and Igor for assisting on final housekeeping and security questions prior to submitting.


Web References
- [Wikipedia](https://en.wikipedia.org/wiki/Defensive_design/)
    - Used to determine the exact meaning of defensive design.

<hr>


#### Websites reviewed

Websites reviewed and used during the creation of this project.

- [Balsamiq](https://balsamiq.com/)
  - Used for creating the wireframe mocks.
  
- [Bootstrap](https://getbootstrap.com/)
  - Researching carousel functionality, although wasn't used in the project.

- [Codeacademy](https://www.codeacademy.com/articles/what-is-crud/)
  - Article referring to "..................".

- [Google Fonts](https://www.fonts.google.com/basic-syntax/)
  - Used for choosing the sites font.

- [Jshint](https://jshint.com/)
  - Validation testing of Javascript.

- [Markdownguide](https://www.markdownguide.org/basic-syntax/)
  - This website was used to refresh knowledge on how to write Markdown.

- [Pexels](https://www.pexels.com/)
  - Website flower images were selected from this source.

- [Python](https://www.python.org/doc/essays/blurb/)
    - Reviewed for gaining additional understanding of the language.

- [RandomKeygen](https://www.randomKeygen.com/)
  - Used for Fort Knox password.

- [StackOverflow](https://stackoverflow.com/)
  - Various research and questions throughout.

- [Techsini](https://techsini.com/multi-mockup/)
  - Used for Mock Up Images.

- [Tech with Tim](https://www.youtube.com/watch?v=mqhxxeeTbu0&list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
    - A series of You Tube tutorial videos to gain greater understanding of Flask.

- [Werkzeug](https://palletsprojects.com/p/werkzeug/)
    - Used to gain knowledge in authentication and secure passwords.

- [W3Schools](https://www.w3schools.com/basic-syntax/)
  - Reviewed and used frequently throughout the design of this project.

- [W3C Markup Validation](https://validator.w3.org/)
  - Validation testing of HTML and CSS.

<hr>


## Acknowledgements

[Slack](https://slack.com/intl/en-gb/) , the entire community of students past and present for their motivation and concern.

My mentor Spencer Barriball for initial guidance on the development of the website.

[Code Institute](https://codeinstitute.net/) Tutor Support for assistance when facing difficulties.

The developer's ability to get this project created with very little time to ensure this final milestone was submitted before subscription ended.



*Created for education purposes only*



