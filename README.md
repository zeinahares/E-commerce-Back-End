# Ecommerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
I wanted to create a back end for an e-commerce website that uses the latest technologies like MySQL and Sequelize. This will help the company keep track of their categories,products, tags and product tags using object relational mapping

## Table of contents
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)
- [License](#license)
- [Contribution](#contribution)
- [Tests](#tests)
- [Questions](#questions)
 

## Installation
You will need to have node js installed on your computer. You will also need a MySQL account and MySQL installed on your computer. After you have both programs installed, you will need to install this program (after cloning it locally) and running 'npm install' in your terminal, inside the relevant file. After that, you will need to initilize the database and the seeds. You can do that by entering the db folder in the terminal and running 'mysql -u root -p', logging into MySQL with your password, and then running in MySQL 'source ./schema.sql'. After that, you need to enter the ‘.env.EXAMPLE’ file, and enter your password of your MySQL account inside the string quotes. Also, rename ‘.env.EXAMPLE’ to just ‘.env’. Now you need to seed the database by running ‘npm run seed’ in your terminal inside the main folder. Now you have installed the program, initialized the database, and enter your MySQL password into the code, and seeded the database. Now you can run 'npm start' in your terminal to start using the program.

You will also need to install Insomnia to be able to see the database in action. 

## Usage
After you start the server using 'npm start', you can begin interacting with the database in Insomnia.

You can make mulitple request types: get (to recieve info), post(to add info to the database), put (to update info by a specific id), and delete (to delete a database entry by a specific id).

You can create these requests for categories, products, and tags.

Use a variation of these URLS to interact with the server:

http://localhost:3001/api/categories
http://localhost:3001/api/categories/1 (for a category with id 1)

http://localhost:3001/api/products
http://localhost:3001/api/products/2 (for a product with id 2)

http://localhost:3001/api/tags
http://localhost:3001/api/tags/3 (for tag with id 3)

follow the syntax from the get routes when making a post or put request in the body to ensure correct variable names are being used.

## Walkthrough Video

https://drive.google.com/file/d/1jJ2juroIE--mywlI2QPucYwX6KF0YtjB/view

## License
MIT License https://opensource.org/licenses/MIT

    Copyright (c) [yyyy] [name of copyright owner]
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contribution
N/A 

## Tests
N/A 
## Questions - 
  
Feel free to reach me for questions at anytime!

  GitHub URL: https://github.com/zeinahares 


  Email Address: zeinahares@gmail.com 
