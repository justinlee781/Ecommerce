# EcommerceTable of Contents 📑

Description
Application Preview
Installation
Usage
Links
Criteria
Technologies
Questions
License
Description

Build the back end for an e-commerce site by modifying starter code. Configure a working Express.js API to use Sequelize to interact with a MySQL database.

Application Preview

E Commerce Back End Demo 1

E Commerce Back End Demo 2

Installation

Copy the repository to your system
Create .env file
SET DB_NAME to 'ecommerce_db'
SET DB_USER to 'YOUR-MYSQL-USERNAME'
SET DB_PASSWORD to 'YOUR-MYSQL-PASSWORD'
npm install
Load schema.sql via MySQL command line:
source schema.sql
npm run seed
node server.js
Usage

Back End application using CRUD API routes with a MySQL database

Links

Use a .env file
Connect to MySQL Database via Sequalize
Create Dev Database via schema and seed commands
API GET Routes display JSON formatted data
GET will return ALL data in the sections below:
GET Will return SINGLE data in the sections below:
Categories
Products
Tags
API POST, PUT, DELETE Routes
Successfully Create, Update, and Delete data in Dev Database
Associations
Products BELONGS-TO Category
Category HAS-MANY Product
Prodcut BELONGS-TO Tag
Tag BELONGS-TO-MANY Product
Technologies

MySQL2
Sequelize
dotenv
Questions

Questions? Concerns? Contact Me Below:

Github Username: brianalegre
Github Link: https://github.com/justinlee781
Email: lee.justin@gmail.com
License

Copyright 2022 Justin Lee
Licensed under the: MIT License
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
