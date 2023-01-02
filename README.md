# Cowley Pottery: 

This website is being designed for use by Cowley Pottery, the pottery shop of Helen Taylor.

This is an e-commerce store built using the Django framework, Python, HTML, JavaScript and CSS. It features a Stripe payment system, numerous models to contains information regarding products, categories, profile information and commissions. The site aims to be intuitive with simple yet powerful navigation and categorisation with a paint scheme as expected from a pottery website.

This website has been created as the Fifth Milestone project for Code Institute's Full Stack Software Development Diploma. GitPod was used for writing the code for this website, as well as committing and pushing to GitHub. GitHub was then used to store the project after it had been pushed from GitPod. Once all the code had been written, Heroku was then used to deploy the website with ElephantSQL and Amazon S3 used for storage. 

The project was designed with design thinking principles at the core and the customer relationship was managed alongside agile methodologies.

### View the live website [here](https://cowley-pottery.herokuapp.com/)

![Live Website](media/responsive.png)

***
## Table of content: 

***
 
## Site Goals:

The goals for this site are as follows:
* Allow users to view products
* Allow users to add products to a basket
* Allow users to update or delete products from basket
* Allow users to make payments using Stripe
* Allow users to create a user profile
* Allow users to contact the store with any queries 
* Allow user to request commissions 
* Allow users to sign up for a stock newsletter
* Allow authorised users to leave product reviews
* Allow store owner to collect user data to complete orders
* Allow store owners to approve user reviews 


## UX:

### Epics and User stories: 

The user stories are on the projects board and I will copy them over to here at a later date. I have been using Excel to maintain the Moscow working method as I find that GitHub is clunky for a 1 man team. 

#### Epic 1 - Views and Navigation

Website requires web pages containing information regarding the business and the items that are for sale. It also is necessary to have the means in which to traverse the website. User stories that address this Epic are:

*As a customer I can view a list of products so that I can identify what products are available and view their images.
*As a customer I can view individual products so that I can learn more about the item such as price, description, and quantity available.
*As a customer I can quickly identify and traverse the website so that I can reach the desired part of the website.
*As a customer I can quickly identify new stock so that I can purchase before it sells out.
*As a customer I can always see the shopping basket total so that I can be aware of how much money I am spending.
*As a customer I can view information regarding the business so that I can learn more about the artist who makes the items.

#### Epic 2 - Account Registration and Access

Users of the e-commerce website must be able to create personal accounts which are secure as well as following modern email confirmation norms. User stories that address this Epic are:

*As a customer I can create an account so that I can Store personal details, view purchases and view my profile.
*As a customer I can receive a registration confirmation email so that I can tell whether my account registration was successful.
*As a customer I can recover or reset my password so that I can regain access to my account.
*As a customer I can sign in using credentials so that I can gain access to my account whilst knowing that it is safe.
*As a customer I can log out of my account so that I can secure my account.

#### Epic 3 - Products, search, categorisation and notification

Customers of the e-commerce website must be able to search the website by name as well as view items by category. The website will be selling quality over quantity with limited stock and bespoke creations and as such notification of stock changes are essential. User stories that address this Epic are:

*As a customer I can view products by category so that I can quickly view items of a particular type.
*As a customer I can search for products by name or description so that I can find a specific item to buy quickly.
*As a customer I can sign up for a newsletter so that I can keep up to date with stock changes.

#### Epic 4 - Purchasing and Checkout

Customers must be able to view their shopping basket as well as add to it and edit any item within. They must be able to pay for their shopping basket securely and receive confirmation of purchase. User stories that address this Epic are:

*As a customer I can view the shopping basket so that I can identify what is to be purchased and its total cost.
*As a customer I can add items to shopping basket so that I can purchase them.
*As a customer I can edit items in the shopping basket so that I can alter quantity of items in basket.
*As a customer I can pay for items so that I can buy the item.
*As a customer I can feel that my personal and payment information is safe and secure so that I can confidently provide the information needed to make a purchase.
*As a customer I can see an order summary so that I can check my order before I click "pay now".
*As a customer I can receive an email receipt so that I can have evidence of my purchase.

#### Epic 5 - Admin and Store Management

The admin should be able to add new products to the store as well as edit others.

*As a shop owner I can delete products through the admin site so that I can delete items.
*As a shop owner I can add products through the admin site so that I can add new items.
*As a shop owner I can edit products through the admin site so that I can change item prices, images and descriptions.

## Development Planes:
To create a website that is comprehensive and informative for a user, as a developer you need to look at all aspects of the website and how someone who visits your website will use it. You have to consider all the user stories that have been outlined in the above sections.  

## Strategy

The strategy principle looks at user needs, as well as product/service objectives. This website's target audience was broken down into three categories:

### Roles: 

* Admin
* New User
* Existing User  

### Demographic:
* Aged between 18 to 100

#### Lifestyle:

* Collectors
* Home Decorators
* Hobbyists


#### The website needs to allow users to:  
* View products by price, category or rating
* Add products to a basket
* Edit product quantities and delete products straight from the basket
* Make secure payments for their products via credit card
* Create a user profile
* Contact the store with enquiries
* Sign up for a newsletter
* Leave reviews for products they bought
* Visit the store's social media accounts straight from the site 

#### The website needs to allow the store owner to:  
* Add, edit and delete products straight from the frontend site 
* Collect information from order forms
* Collect email addresses for a monthly marketing newsletter


## Scope:  

With the structure in place, it was then time to move onto the scope plane. This was all about developing website requirements based on the goals set out in the strategy plane. These requirements are broken down into two categories. 

### Content Requirements:
1. The user will be looking for:
      * A list of products that can be purchased 
      * Information about the store owner
      * Links to the store's social media accounts

### Functionality Requirements:
1. The user will be able to:
      * Learn more about the store and the owner
      * Browse all the store's products
      * Add products to a basket
      * Edit their basket
      * Complete orders using Stripe
      * Create a user account
      * Update information on a user account
      * Contact the store with enquires 
      * Sign up for a newsletter
      * Request a specific commision
      * Learn more about the store and the owner

***

## Skeleton:
Wireframes were created to set out the initial appearance of the website while also making sure to keep the end-user in mind at all times. Wireframes were created using [Balsamiq](https://balsamiq.com/).  

## Surface:

***


### Colour: 
The colours used for this project were white and a grey that looks just like unfired clay! Not only in this in keeping with the product, it matches up with the general approach accross hobbyist websites which generally follow a light coloured clean and simple approach.


### Font:
Fonts used for this site were Chelsea Market and Varta, both of which have been imported from [Google Fonts](https://fonts.google.com/)

Note the "Logo" is currently shown in Rampart One but this is a place holder as the customer is looking to get a graphic designer to create an actual logo.

### Images:
The images for this project are all genuine pieces from the story either taken by me or by the customer.

Please note the landing page is also placeholder as this will be replaced by a nice, high resolution image or better (if I can find the equipment necessary) a 10 second repeating video of potters wheel rotating with clay on top from a vertical perspective.
 

***
 


## Features:
There are several features on this site to help users get the most out of their visit to the site.  

### General:

&nbsp;

### Landing page:

&nbsp;

### Home page:


&nbsp;

### Shop page:  

Here the filtering of products is done through tiles rather than outdated dropdowns.

There is a new filter which returns products that have only been added the database within a certain timeframe.

Note that due to the nature of this website, there is little need for a search bar as at any given time there will only be a handful of items on sale. 

There has been extra functionality added to only be able to buy what is it stock.

Note also when an item runs out of stock, it will remain on the website with a banner (to be added) until it is taken down intentionally. This is to give prospective buyers an idea for commissions as opposed to thinking they cannot purchase

&nbsp;

### View Product page:  

&nbsp;

### Basket: 

&nbsp;

### Checkout:


&nbsp;

### About us page:

&nbsp;

### Commisions page:

&nbsp;

### Sign up page:


&nbsp;

### Login page:


&nbsp;

### My Profle page:
 

&nbsp;

### Logout page:

&nbsp;

### 404 error page:




## Future Features:


***


***

## Bugs:
### jQuery - Toasts:
Issue 
* Fix

&nbsp;


***


## Technologies Used:
For this project, the following technologies were used.  

### Languages:
* HTML
* CSS
* Python
* Javascript
 

### Frameworks, Libraries, Programs & Applications Used:
* Django
* PostgreSQL
* Bootstrap
* AWS

#### Google Font
* Google Font was used to import the chosen fonts for this project.

#### GitPod
* GitPod was used for writing all the code for this project. It was also used to commit and push to GitHub.  

#### GitHub 
* GitHub was used to store this project.

#### Heroku
* Heroku was used to deploy the project.

#### Amazon Web Services
* AWS was used to store some of the images used in this project

#### Balsamiq 
* Balsamiq was used to draw initial Wireframes for this project.

#### Google Development Tools
* Google Dev Tools was used to edit code and check responsiveness before making the changes permanent.

*** 

## Reports and Credits:

### Database Schema:

### Marketing:
Marketting has been extensively done through Instagram. There has been additional marketting through Facebook marketplace. And associate marketing through events. A thorough summary to be written here.

## Testing:


### Validation:

* HTML:

* CSS:

* JavaScript: 

* Python: 

***

### Accessibility:
Lighthouse Reports

***

### Deployment and Development:

***

### Credits:
* The initial setup of the Django project was done following the Code Institutes walkthrough project.  


### Acknowledgements:


*** 
