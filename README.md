# Shopping Website Project
This is implementation of simple Database for a shopping website
<br>

## About the project
<ul>
  <li> This Project Provides complete overview to design a database schema of online shops and shopping carts to manage the users, products, reviews, carts and orders.
  <li> It is just like e-commerce websites where customers can place orders and admin can add products.
</ul>

Created by : <br>
Rohan Patil 111803161<br>
Dewashish Wankhade 111803159<br>

## Running the project
To run the project on your local machine, follow these instructions.
<br>

#### Pre-requisites
1. Make sure you have  MySQL installed on your system
2. NodeJS must be installed and running

#### Tech Stack Used
<ul>
  <li>MySql Database
  <li>HTML/ CSS/ JS for Frontend
  <li>Node JS and Express for Backend
</ul>

#### Running the program
Create a sample database and a sample user to access this database

Open mysql in your system and run the following commands
create database shopproject;
create user shopadmin identified by 'shoppass';
use shopproject;
grant all privileges on shopproject to shopadmin;
grant all privileges on shopproject.* to shopadmin;

Your server gets started. By default, it will be started on port 8000

#### Loading Data
Initially the cart will appear empty as there are no products added.<br>
You may add new products along with their description and dummy details by going to 
'localhost:8000/addproduct.html'

<br>
Alternatively, you can use the dummy data provided in seed.js .
To use it, go to <br>
src/db and run file seed.js
