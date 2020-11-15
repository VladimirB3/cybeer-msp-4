# GameDB

## milestone-project-4

This is my Milestone Project 4 for Full Stack Framework with Django Milestone Project.

## Cybeer - Online Beer and Snack Store

This is a simple Storefront for beer lovers where you can order Beers and Snacks delivered to your home. The app is easy to navigate through and serves two basic functions, which are purchasing and reviewing beers and snacks, as well as subscribing to beer and snack packadges.


# UX

The application is created for a couple types of users – the ones that wish to purchase the best beer and snacks available. The second group is the managment that can manage the store through superuser granted admin access.  Typical users might use the app for:

**Viewing and Navigation:** 
* View a list of products.
* View individual product details.
* Quickly identify deals, clearance items and special offers.
* Easily view the total of purchases at any time.

**Registration and Customer Accounts:**  
* Easily register for an account.
* Easily login or logout.
* Easily recover password.
* Receive an email confirmation after registering.
* Have a personalized Customer profile.

**Sorting and Searching:**
* Sort the list of available products.
* Sort a specific category of product.
* Sort multiple categories of products simultaneously.
* Search for a product by name or description.
* Easily see what I've searched for and the number of results.

**Purchasing and Checkout:**
* Easily select the size and quantity of a product when purchasing it.
* View items in the cart to be purchased.
* Adjust the quantity of individual items in my bag.
* Easily enter payment information.
* View an order confirmation after checkout.
* Receive an email confirmation after checking out.

**Admin and Store Management:**
* Add a product.
* Edit/update a product.
* Delete a product.

## Wireframes: 
* The Wireframes plan can be found in the Wireframes Folder in my github repository:
[My Wireframe](https://github.com/VladimirB3/cybeer-msp-4/tree/master/wireframes/Screenshot 2020-09-08 at 17.04.31)



# UI structure

After understanding the requirements and taking into consideration best design practices the structure of the application was clear.

## GameDB

•	The User comes to find detailed and structured information about available stock in the store.

•	The Manager/Owner can add, edit and delete any entry in the webstore.

•	The navigation through the app is responsive and clear to understand.



# Features

## Existing Features

•	Search Bar - to easily find any item presented in the Store.

•	Account Profile Creator - to save customer account details for future purchases.

•	Shopping Cart - to calculate and store what the customer wants to purchase from the webstore.

•	Stripe Payments - to accept customer payments.

•	Admin Backoffice of the Store - for the managment to effectively manage the webstore.

•	Edit/Delete buttons - so that the managment can change information directly from the storefront.

•   Toasts Popups - Help to be informed of all changes made by users throughout the store.

•   Product Rating - a review score for each product to let customers know what product is the best.



## Features Left to Implement

•	Beer Subscription – so that the customer can pay a monthly subscription on the beers and snacks packadge they chose.

•	Beer origin Map - with each product there should be a map showing exactly where does the beer come from and which brewery.

•	User Review Scores - 5 star rating for the customers to rate the products in the store.

•	Add a comments section for each product so the users can leave comments and communicate between each other.


# Technologies Used

Several technologies have been used in the development of this personal profile website:

•	HTML5 and CSS3 for structure and styling of the pages.

•	<a href="https://fonts.google.com/">Google Fonts</a> where used for text editing and styling

•	<a href="https://fontawesome.com/start">Font Awesome</a> was used to implement the icons

•	<a href="https://jquery.com/download/">jQuery</a> was used to write a more efficient and clean JavaScript

•	<a href="https://github.com/">GitHub</a> repository was used to store the code and site deployment

•	<a href="gitpod.io">Gitpod</a> was used for development and version control

•	<a href="https://validator.w3.org/">W3C Markup Validation Service</a> was used for HTML validation

•	<a href="https://jigsaw.w3.org/css-validator/">Jigsaw W3</a> css validator was used to validate CSS

•	<a href="https://en.wikipedia.org/wiki/JavaScript">Java Script</a> was used for interactive features in the App

•	<a href="https://getbootstrap.com/">Bootstrap</a> was used to build the app (Ver. 4.5, by advice of the Code Institute video tutorial).

•	<a href="https://www.python.org/">Python</a> was used to write the logic.

•	<a href="https://flask.palletsprojects.com/en/1.1.x/">Flask</a> was used as a programming language.

•	<a href="https://aws.amazon.com//">Amazons AWS</a> was used as a static files database for the project.

•	<a href="https://www.djangoproject.com/">Django</a> was used as the main app building Framework for the project.

•	<a href="https://heroku.com/">Heroku</a> was used to successfully deploy live project.

•	<a href="https://stripe.com/">Stripe API</a> was used to create a payment system for the webstore.

•	<a href="https://sqlite3.com/">SQlite3</a> was used as a main database structure for the project.

# Testing

## Functional testing of the application

Functional testing is designed to ensure that each function of the application works in accordance with the requirements of the specification. Testing the functionality of the website shows "What the system does."
For this a checklist for testing application functionality is created and tested with a “<span style="color:green">Passed</span>” or “<span style="color:red">Failed</span>” status with a brief description of the outcome if necessary.

## Links Testing


•	The correctness of internal links – <span style="color:green">Passed</span> – all navigation links between pages work as intended

•	Missing links leading to one page – <span style="color:green">Passed</span> – none

•	Are there any non-linked pages? – <span style="color:green">Passed</span> – none

•	Are there any broken links – <span style="color:green">Passed</span> – none



## Testing Database connectivity


•	Validity of input; – <span style="color:green">Passed</span> – Information is posted to MongoDB with no issues

•	Information is displayed correctly in app – <span style="color:green">Passed</span> – works as intended

•	Categories are displayed correctly – <span style="color:green">Passed</span> - works as intended

•	Input methods when adding information – <span style="color:green">Passed*</span>- Works as intended

•	Delete button – <span style="color:green">Passed</span> – Works as intended

•	Edit button – <span style="color:green">Passed</span> – Works as intended

•	Add buttons – <span style="color:green">Passed</span> – Work as intended

•	Adding and retrieving information from database – <span style="color:green">Passed</span> – Works as intended

•	Admin Page in Backoffice – <span style="color:green">Passed</span> – Works as intended

•	Payment System using Stripe – <span style="color:green">Passed</span> – Works as intended

•	Amazon AWS host for static files – <span style="color:green">Passed</span> – Works as intended

•	SQlite3 host as database – <span style="color:green">Passed</span> – Works as intended


## HTML/CSS Validation

•	HTML syntax errors – <span style="color:green">Passed</span> – none (validated using <a href="https://validator.w3.org/">W3C Markup Validation Service</a>)

•	CSS syntax errors – <span style="color:green">Passed</span> – none (validated using <a href="https://jigsaw.w3.org/css-validator/">Jigsaw W3</a> css validator)

# Usability testing of the site

Usability testing is designed to evaluate the application from the perspective of the end user (UX Testing). This helps to determine whether the product meets user expectations, identifies problem areas in the interface.

Navigation testing of the application is performed with following checks:

•	Application is easy to navgate – <span style="color:green">Passed</span>

•	Buttons, icons, forms and fields are convenient to use – <span style="color:green">Passed</span>

•	Transitions work as intended - <span style="color:green">Passed</span>

•	Product range is clear and visible - <span style="color:green">Passed</span>


## Content Testing

•	No grammar, spelling errors – <span style="color:green">Passed</span>

•	Forms are sized and placed correctly – <span style="color:green">Passed</span>

•	Website color palette optimization and font sizes – <span style="color:green">Passed</span>

•	Content is informative, understandable, structured and logically connected – <span style="color:green">Passed</span>

•	The displayed categories are clear and contain the correct information - <span style="color:green">Passed</span>


Upon evaluatin the usability of the application it can be said that the structural integrity is in place.
The application is understandable and convenient. The navigation is intuitive and easy to understand for all types of users. 
The impressions it makes are visually striking and stylish with no unnecessary clutter. 
It is easy to understand what the application intends to achieve.- <span style="color:green">Passed</span>


# UI Testing


User Interface testing is performed to verify that site’s graphical user interface conforms to specifications.

•	GUI Compliance – <span style="color:green">Passed</span>

•	Assessment of design elements: layout, colors, fonts, font sizes, labels, text fields, text formatting, titles, buttons, lists, icons, links – <span style="color:green">Passed</span>

•	Testing with different screen resolutions – <span style="color:green">Passed</span>

•	Testing the graphical user interface on target devices: smartphones – <span style="color:green">Passed</span> – Testing made using http://www.responsinator.com/

•	Testing the graphical user interface on target devices: smartphones Landscape view – <span style="color:green">Passed</span> – Testing made using http://www.responsinator.com/Testing made using http://www.responsinator.com/

•	Testing the graphical user interface on target devices: tablets – <span style="color:green">Passed</span>


## Compatibility Testing

Compatibility testing is performed to verify the operation of the site with various software and hardware configurations. 

Cross-platform testing of the site allows to evaluate the performance of the site under different operating systems (both desktop and mobile):

•	Widows – <span style="color:green">Passed</span>

•	Mac OS - <span style="color:green">Passed</span>

•	iOS – <span style="color:green">Passed</span>

•	Android – <span style="color:green">Passed</span>


Cross-browser testing of the site helps to verify the correct operation of the site in different browser configurations:

•	Google Chrome (Ver. 84.0.4147.135) – <span style="color:green">Passed</span>

•	Mozilla Firefox (Ver. 80.0.1) – <span style="color:green">Passed</span>

•	Internet Explorer (Ver. 11.0) - <span style="color:green">Passed</span>


## Tests Summary


Fixes shall be implemented and documented accordingly for the identified issues.

In conclusion, the application is of sound structure and is ready to be deployed.

# Deployment

Cybeer app is located on GitHub and the databases used for this project is Sqlite3 and Amazon AWS. The repository for this site can be found at VladimirB3/cybeer-msp-4

Gitpod was used for development – to run the site locally python3 -m http.server command needs to be run on the terminal inside the repository VladimirB3/cybeer-msp-4.

The application is live here: https://cybeer-app.herokuapp.com/

To deploy this project on your own IDE, folow the steps below:

 Firstly, ensure of the following:
    - You have an IDE, such as GitPod
    - The following must be installed locally on your computer:
            - git
            - PIP
            - Python 3
            - Django
            - AWS Account
            - Stripe Account
            - Gmail Account

Instructions for Installation:

1.  Make your own folder and navigate to it on the terminal. Then enter the following in the terminal:

```
$ pip3 install --upgrade pip
$ pip3 install -r requirements.txt
```
2.  To run the app locally:

```
$ python3 manage.py runserver
```

### Heroku Deployment

The code was also pushed from git to heroku for live deployment: https://www.heroku.com/ 

To Deploy using Heroku Git, use git in the command line:

1.  Install the Heroku CLI. If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

```
$ heroku login -i
```

2.  Clone the repository. Use Git to clone the projects source code to your local machine.

```
$ heroku git:clone -a cybeer-msp-4
$ cd cybeer-msp-4
```
3.  create your requirements.txt file

```
$ pip freeze --local > requirements.txt

```
4.  create your procfile file

```
$ echo web: python app.py > Procfile

```

5.  Deploy your changes. Make some changes to the code you just cloned and deploy them to Heroku using Git.

Connect to Heroku app via Git use: $ heroku git:remote -a cybeer-app

```
$ git add .
$ git commit -m "commit message"
$ git push heroku master
```
6.  In the heroku dashboard for the application, click on "Settings" > "Reveal Config Vars".

7.  Set the following config vars:
```
IP : 0.0.0.0
PORT: 5000

To set the environment variable you have to have:

* All PUBLIC and SECRET Keys available to you


•	Control+X to exit – followed by “Y” to save changes – close the terminal and open a new one.
```

8. In the heroku dashboard, click on the button "Open App".

The app should open in a new tab.

# Credits

## Content

•	Basic functionality was sourced from FULL STACK FRAMEWORKS WITH DJANGO MODULE – Code institute.

•	Some  templatecode was copied from Bootstrap (Ver. 4.5) Documentation and modified.

•	Icons used where sourced from Font Awesome (http://fontawesome.com)

•	jQuery was used to create clean and easy to understand JavaScript.

•	JavaScript was provided by Code Institute Video Tutorial and Code Institute.

•	Database structure and location was provided by SQlite3 and Amazon AWS.

•   CSS was created with help of Code Institute Video Tutorial.

•   Basic Python code was drafted and modified from Code Institute Video tutorial (Full Stack Frameworks With Django)

•	This README file was drafted up using MS Word following the giudelines provided by Code Institute.

## Media

•	Images on this project are sourced from the product producers and are not used to misrepresent the brands or create monetary gain for the user - STUDY PURPOSES ONLY


## Acknowledgements

•	My friends and family motivated me to complete the project.



