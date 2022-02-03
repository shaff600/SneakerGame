
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

### Custom Font -  [Google Fonts](https://fonts.google.com/specimen/Orbitron?query=Orbitron)
-  The font class from google called "Orbitron", Designed by Matt McInerney was used for page headings.

### Glass Cards-  [Glassmorphism](https://hype4.academy/tools/glassmorphism-generator)
-   This generator was used to create the background styling for the card components on the application. It was simple to use and provided CSS that's required for the desired effect.

### Soft UI (Footer)-  [Glassmorphism](https://neumorphism.io/#e0e0e0)
-   This CSS generator was used to create a simple footer with shadow effects

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
Testing was done throughout the project via chrome development tools. I also used various code validators to make sure my code was free of errors.
    
###	Testing User Stories from User Experience (UX) Section

-	User (Customer)
	-	As a user, I would like to locate different site pages through the navigation panel
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

## Manual Testing

 ### As a user, I would like to locate different site pages through the navigation panel 

TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
All Products| Filtering options are diaplyed, filter by Price, Rating, Category and All Products| PASS
Brands | Filtering options are diaplyed, filter by Nike, Jordan, Off-White, Bearbrick and All Brands | PASS
Accessories| Filtering options are diaplyed, filter by Shoe Care, Collectables, Caps and Bags | PASS
Categories| Filtering options are diaplyed, filter by Mens, Womens, Kids, All| PASS
My Account| Product Management (Super User access), Register and Login options are visible | PASS
Text|Checked if all fonts and colors used are consistent or not|PASS

 ### As a user, I would like to register an account

TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "Register" | on click page is redirected to Register page | PASS
Form Validation| Submit form with partial entries | PASS
Enter valid data| On form submission, verfication e-mail is produced| PASS

 ### As a user, I would like to log into my account

TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "Login" and enter invalid credentials| on click, error message is displayed | PASS
Form Validation| Submit form with partial entries | PASS
Enter valid data| On form submission, page is redirected to homepage| PASS

###	As a user, I would like to view latest sneakers
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "All Products"| All Products are displayed | PASS
 
###	As a user, I would like to filter sneakers by brand 
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "Brands" on navbar | options avaiable for different brands| PASS
Enter specfic brand in search bar| Number of results listed  | PASS

###	As a user, I would like to filter by price
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "All Products"| All Products are displayed | PASS
Select Price(Low to High) | Filter is applied to products | PASS
Select Price(High to Low) | Filter is applied to products | PASS

###	As a user, I would like to filter by rating 
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "All Products"| All Products are displayed | PASS
Select Rating (Low to High) | Filter is applied to products | PASS
Select Rating (High to Low) | Filter is applied to products | PASS

###	As a user, I would like to view product details
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "All Products"| All Products are displayed | PASS
Select a Product| Page is redirected to Product Detail page| PASS

###	As a user, I would like to place items into shopping basket
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Select a Product| Page is redirected to Product Detail page| PASS
Click "Add To Bag" | Item is placed in basket | PASS

###	As a user, I would like to purchase items in my shopping basket
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "Secure Checkout"| Page is redirected to checkout entry page | PASS
Form Validation| Submit form with partial entries | PASS
Enter valid data (Sample Stripe Data)| On form submission, page is redirected to order confirmation page| PASS

###	As a user, I would like to confirm deletion of items from basket
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click "Delete" on basket item | button does not work | FAIL
Update J Query Version| Item can now be removed| FAIL

###	As a user, I would like to place to increace/decrease quantitiy 
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Click + on bag item| Quanitity for item is updated| PASS
Click - on bag item| Quanitity for item is updated| PASS

###	As a admin, I would like access to Product Management page
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Login with SuperUser credentials| "Product Management" page is displayed under "My Account"| PASS

###	As a admin, I would like to ability to delete a user account
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Naviagte to the admin URL ("/admin/")| Admin login page is populated | PASS
Locate user account and click "delete"| Confirmation message pop up generated, user deleted | PASS

###	As a admin, I would like the ability to perform CRUD operation on Products, Brands and Categories 
TEST            | OUTCOME                          | PASS / FAIL  
--------------- | -------------------------------- | ---------------
Navigate to "Product Management" on Nav Bar| On click, page is redirected| PASS
Form Validation| Submit form with partial entries | PASS
Enter valid data| On form submission, page is redirected to products page| PASS
On admin screen, update product details| Product is updated | PASS
On admin screen, delete product | Product is deleted | PASS
On admin screen, add new brand item via form | Brand is added | PASS
On admin screen, add new category item via form | Category is added | PASS
On admin screen, update category item via form | Category is updated | PASS

## Validators

The code included for this project has been inputted into W3C HTML Validator, W3C Validator, JSHint Validator and a PEP8 Validator. Within the HTML Validators there where some fails regarding the django templating that's been used however there where no HTML errors. 
# Summary
   -   As a result of running the validator for the HTML, it was shown that the jinja templating language was causing issues however this is expected as the tool is not recognising the templating lanugage. When carrying out testing there was an issue with the product delete button when at basket view, a new JQuery URL was used which worked, I believe i was using the "slim" version of which dosen't include the full functionaility JQuery offers.
   




## Deployment




## Credits

### Sources 


### Acknowledgements

