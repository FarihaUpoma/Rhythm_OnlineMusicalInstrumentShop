# Rhythm Online Musical Instrument Shop
E-Commerce and Web Engineering Lab Project

#### Project Overview:

Our project is an Online Musical Instrument Store that allows music enthusiasts from all over the country to buy musical instruments of their preference sitting at home. The users are able to browse products, search for their favourite, add to cart and place order. Every user maintains a customer profile where they can view the progress of their order and keep their personal information. There is also an admin panel, where the admin can insert new product,category,subcategory and brand, view all products, all customers, orders, complete orders and update products. We will learn detailed about this project further in his proposal.

#### Purpose of this project:

The purpose of this project is to teach us various aspects of web engineering. We get a deeper knowledge of HTML, CSS, Javascript, Php and MySql. We also gain a basic knowedge about 3 tier architecture and how the layers interact with each other .

#### Overall Description

##### Product Perspective:

1. We provide a large variety of instruments so that music enthusiasts can freely choose their desired instruments.
2. The products are organized according to categories like Guitars, Ukulele, Flute, Amplifier etc. There are also various subcategories of each category so that there is a variety of classification.
3. Customers have to register with their own user email. They can add products to cart when not logged in but must login to buy the product.
4. They can maintain their own cart for ordering products .
5. Customers have to pay Cash On Delivery.
6. There is a search function which can provide results based on keywords.
7. There is an admin panel for management of the whole site.

##### Hardware Interface:

The system does not require any special hardware specifications. Computers, Tablets, Smart Phones etc. with an active internet connection can run it.

#### 3 Tier Architecture

We have implemented 3 tier architecture locally. It is described as follows.

#####  Presentation Layer:

The presentation layer lies at the client side. Here are all the pages that the client can view. This is written in HTML, Css, bootstrap and php. When the presentation layer needs data it calls the business logic layer.

##### Business Logic Layer:

This layer lies at the server side. Here the functions are written that call the database access functions in data access layer. This layer is mainly written in php.

##### Database Access Layer:

In this layer, we write all the sql query functions that access retrieve or put data into the database. This is written mostly in php and mysql. The data from the database access layer is returned to the business logic layer and then it is passed from there to the presentation layer. We have done this locally. If t was done globally then each layer would interact with each other using http requests and data would be passed through XML.

#### Structure of database:

##### Homepage:

Options in the homepage-

##### Category:

There is a category option menu on the left which is actually another dropdown menu each containing subcategories.

###### Best Selling Products:

At the bottom there are best selling products which are retrieved from the database based on the most ordered products within the last month.

###### Details:

Clicking on any category and then subcategory will bring about the products in that section. Now if we click on the details button, the product details will be shown in another page.

###### Cart:

If we click on the add to cart button then the number of items then the total items on the top right of the page will be increased.Clicking on the Cart will take us to the cart page.

###### Search:

There is a search option that allows users to search products based on category, subcategory or brand.

###### Cart Page:

The cart page contains name and quantity of each ietm n the cart. The number of products can be increased by updating the cart. Then we proceed to checkout.

##### Checkout Page:

On clocking checkout if the user is logged in then we are taken to payment page. Here the user may input the shipping address and by clicking order, the order will be placed. A mail about this order will be sent to the user vial email. If not logged in, the user will be taken to login page.

##### Customer Account:

###### Customer Register:

The customer can register an account on the register page by giving appropriate information.

###### Customer Login:

The customer can login into account by providing their email and password. If they forget password there is a forgotten password option. When clicked this sends an email to the user's email. There is a link which when clicked takes them to the retrieve password page. Here they can provide a new password every time.

###### View Orders:

The customer can view his/her orders on this page and keep tab on their progress. After completion of each order it shows that the order is completed.

###### Update Account:

The customer can update any information about their account on this page. There is also an option for deletion of account.

##### Admin Panel:

The Admin Panel gives the admin authority to overlook the whole site.

###### Insert New Product:

Here there is a form where the admin can insert various products with their title, category, brand, picture, price, description and a few keywords for search function.

###### Insert category:

This allows the admin to insert category, subcategory and brand of products.

###### View Products:

Here all the products in the database are shown to the admin.

###### Edit Products:

In the view products page there is a link beside each product that takes the admin to an update product page where he can update the information about each product.

###### Delete Products:

There is also an option of deletion of products in the view products page for the admin.

###### View Customers:

In this page all the customers registered to the website are shown.

###### Delete Customer:

The admin also has the authority to delete any customer if malicious actions are observed from that account.

###### View Orders:

In this page all the orders are shown from the database. And at the completion of each order the admin can enter the order to be completed.

#### Security:

We have provided both salting and hashing for the user passwords to provide maximum security. Also, we use session for everything, so without being logged in nobody can access the admin pages. And one user cannot access pages of another.


We have tried to make this website very user friendly and provide it with an elegant interface. And being the first one in Bangladesh it can surely be a very good platform for music enthusiasts to get their favourite products and do what they love.
