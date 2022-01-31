
  <h1 align="center">SneakerGame</h1>

# Purpose:
"SneakerGame" is a wavy fashion e-commerce website that allows shoppers to browse, search for and purchase the most popular sneakers and accessories.

The object of this project is to utilize the Django framework in order to implment an e-commerce website that aids swift development without compramising on security. This allows the user to register an account and log in to confirm the order. In addition, the website records the customer's shopping cart so that the customer can see the next potential purchase. In addition, the site uses the Stripe API  to enable customers to complete their purchases and securely store payment information for future orders
# User Experience (UX)

## Stratergy: 
This website will allow users to browse and purchase the latest sneakers. The sneaker reseller market has exploded within the last few years due to the increased capabilities of bots that purchase sneakers on release dates. These bots are designed to purchase sneakers quciker then a human can navigate through the retailers website, as it's first come first served basis, these bots beat humans to the purchase. This has lead to resellers taking advatage of this new technology and selling sneakers that retail stores cannot get a hold of. The purpose of this site is for resellers to advertise and sell their sneakers.

A user can register an account to set there user profile. There is also an Admin profile which acts as a super user and can view all orders and also has the ability to add/remove items from the database. The navigation bar has been seperated out to specific items to allow the user to view products in a swfitly manner. There is also a search bar included within the nav bar which will search the whole site for any related keywords. When viewing products, a filter has been included to view items within a specifc criteria.  

-	### User stories
-	User (Customer)
	-	As a user, I would like to view latest sneakers
	-	As a user, I would like to filter sneakers by brand 
	-	As a user, I would like to filter by price
	-	As a user, I would like to filter by rating 
	-	As a user, I would like to view product details
	-	As a user, I would like to place items into shopping basket
	-	As a user, I would like to purchase items in my shopping basket
	-	As a user, I would like to confirm deletion of items from basket
	-	As a user, I would like to place to increace/decrease quantitiy 
	-	As a user, I would like to register an account
	-	As a user, I would like to log into my account
- Admin (Super User)
	-	As a admin, I would like access to Product Management page
	-	As a admin, I would like to ability to delete a user account
	-	As a admin, I would like the ability to perofrm CRUD operation on Products, Brands and Categories 
		-	CRUD - Create, Read, Update, Delete

## Scope:
The application has a set of categories and brands that are restricted by the admin user. This is to ensure when adding a product that only relevant items are assigned to the product. In the event of a new product being added to the site, the relevant category/brand will have to stored within the database in order to store the product correctly. For exmaple, if the admin wanted to add a new product 'Nike Air Max 90' (mens sneaker), the admin user will have to ensure that the drop down items on the admin form has the correct category and brand options that suit the sneaker. Category/Brand can be added manually through the admin panel. Once added, the items would be included within the products drop down fields.
## Structure:
To enable consistancy throughout the applicatuon, the Python template engine of "Jinja" was used to help structure the HMTL pages. Jinja is a modern day templating language for Python developers. Jinija templates include inheritance which is used to prevent repeated code. This saves a lot of time and reduces work. A base template contains the basic layout which is common to all the other templates. This is beneficial as it provides a level of consistency throughout the application structure.

## Skeleton:
Prior to the development of the project, I sketched out my initial idea in Balsamiq Wireframes to provide a visual representation of how the application will look like. This has helped when creating the application as it allowed for guide to follow during development. 

## Surface:
My initial thoughts when designing the surface of the website was to theme the quiz to match an arcade type game. This meant including live backgrounds, funky fonts and a qwerky colour scheme. Here is how i went about achieving this:


### Front-end Framework -  [Bootstrap](https://getbootstrap.com/)
-	The front-end framework of Bootstrap was used to build the styling components of the application. Materialize does alot of the heavy lifting for you and provides  default stylings that speed up the development process.

### Custom Font -  [Google Fonts](https://fonts.google.com/specimen/Permanent+Marker)
-  

### Glass Cards-  [Glassmorphism](https://hype4.academy/tools/glassmorphism-generator)
-   This generator was used to create the background styling for the card components on the application. It was simple to use and provided CSS that's required for the desired effect.

## Features
-	Responsive UI/UX
-   Website purpose immediately communicated and understood
-   Navigation bar
-   Side-Nav Sorting functionality
-   Registration & Login functionality
-   Search functionality
-   Log out functionality
-   Sorting functionality
-   Product details
-   Checkout functionality
## Technologies Used

### Languages/Frameworks Used
 1. HTML <img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />

 2. CSS <img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />
 3. Bootstrap <img align="left" alt="Bootstrap" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bootstrap/bootstrap.png" /> 

 4. <img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" /> JavaScipt

 5.   <img align="left" alt="MongoDV" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" /> Python
 6.    <img align="left" alt="MongoDV" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/django/django.png" /> Django
 

### Frameworks, Libraries & Programs Used

1.  [Django:](https://www.djangoproject.com/)
-   Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design with the use of templates.

2.  [Google Fonts:](https://fonts.google.com/)

-   Google fonts were used to import the 'Ubuntu Condensed' font into the style.css file which is used on all pages throughout the project.

3.  [Font Awesome:](https://fontawesome.com/)

-   Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

4.  [jQuery:](https://jquery.com/)

-   jQuery came with Materialize to aid the frameworks interactive features.

5.  [Git](https://git-scm.com/)

-   Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

6.  [GitHub:](https://github.com/)

-   GitHub is used to store the project's code after being pushed from Git.

7.  [Balsamiq:](https://balsamiq.com/)

-   Balsamiq was used to create the  [wireframes]()  during the design process.






# Testing




## Deployment




## Credits

### Sources 


### Acknowledgements

