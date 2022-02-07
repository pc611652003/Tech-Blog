# Tech-Blog

## Description

A CMS-style blog site, allow user to publish articles, blog posts, and my thoughts and opinions.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
* [Credits](#credits)
* [Results](#results)
* [Screenshots](#screenshots)

## Installation

To install necessary dependencies, run the following commands in command line:
npm i

To create the database, run the following commands in mysql shell:
source db/schema.sql

## Usage

To use the application, run the following commands:
npm start

## Features

1. Signup users
2. Login with encrypted password
3. Add, Edit, Delete Posts
4. Add Comments
5. Auto Logout after cookies expiring time

## Credits

Third-Party Assets:
1. dotenv
2. MySQL2
3. Sequelize
4. Session
5. bcrypt
6. JawsDB

## Results

Application: https://frozen-retreat-94147.herokuapp.com/

Repository: https://github.com/pc611652003/E-commerceBackEnd

## Screenshot

User can create the database in mysql by entering following command in mysql shell
![Schema](screenshots/schema.PNG "Database Creation")

User then seed the database with the following command in command line
![Seed](screenshots/seed.PNG "Database Seeding")

User start the server with the following command in command line
![Start](screenshots/start.PNG "Server Start")

User can get all categories by sending a get request to /api/categories/
![GetAllCategories](screenshots/GetAllCategories.PNG "Get All Categories")

User can create category by sending a post request /api/categories/
![CreateCategory](screenshots/CreateCategory.PNG "Create Category")

User can update a category by sending a put request /api/categories/:id
![UpdateCategory](screenshots/UpdateCategory.PNG "Update Category")

User can get a category by sending a get request to /api/categories/:id
The Image also reflects the outcome of the creation and update of the category
![GetOneCategory](screenshots/GetOneCategory.PNG "Get One Category")

User can delete a category by sending a delete request /api/categories/:id
![DeleteCategory](screenshots/DeleteCategory.PNG "Delete Category")

User can get all tags by sending a get request to /api/tags/
![GetAllTags](screenshots/GetAllTags.PNG "Get All Tags")

User can create tag by sending a post request /api/tags/
![CreateTag](screenshots/CreateTag.PNG "Create Tag")

User can update a tag by sending a put request /api/tags/:id
![UpdateTag](screenshots/UpdateTag.PNG "Update Tag")

User can get a tag by sending a get request to /api/tags/:id
The Image also reflects the outcome of the creation and update of the tag
![GetOneTag](screenshots/GetOneTag.PNG "Get One Tag")

User can delete a tag by sending a delete request /api/tags/:id
![DeleteTag](screenshots/DeleteTag.PNG "Delete Tag")

User can get all products by sending a get request to /api/products/
![GetAllProducts](screenshots/GetAllProducts.PNG "Get All Products")

User can create product by sending a post request /api/products/
![CreateProduct](screenshots/CreateProduct.PNG "Create Product")

User can update a product by sending a put request /api/products/:id
![UpdateProduct](screenshots/UpdateProduct.PNG "Update Product")

User can get a product by sending a get request to /api/products/:id
The Image also reflects the outcome of the creation and update of the product
![GetOneProduct](screenshots/GetOneProduct.PNG "Get One Product")

User can delete a product by sending a delete request /api/products/:id
![DeleteProduct](screenshots/DeleteProduct.PNG "Delete Product")