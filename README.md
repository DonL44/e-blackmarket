
<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End</h1>
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/jpd61/e-commerce-backend" />
    <img src="https://img.shields.io/github/languages/top/jpd61/e-commerce-backend"  />
    <img src="https://img.shields.io/github/issues/jpd61/e-commerce-backend" />
    </a>
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>
   
## Description

🔍 A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
  
💻 Below are two gif showings the functionality of the application:
  
![The NPM Test, Seed, and Start](https://github.com/DonL44/e-blackmarket/blob/43cf3b3775e265249a80be868c2dd06c7619cced/images/NPM_test-seed-start.gif)

![Insomnia Database](https://github.com/DonL44/e-blackmarket/blob/43cf3b3775e265249a80be868c2dd06c7619cced/images/node-server_demo.gif)

## Screenshots

![GET_POST_PUT_DELETE-Tags](https://github.com/DonL44/e-blackmarket/blob/43cf3b3775e265249a80be868c2dd06c7619cced/images/tag-screenshot.png)

![GET_POST_PUT_DELETE-Categories](https://github.com/DonL44/e-blackmarket/blob/43cf3b3775e265249a80be868c2dd06c7619cced/images/category-screenshot.png)

![GET_POST_PUT_DELETE-Products](https://github.com/DonL44/e-blackmarket/blob/43cf3b3775e265249a80be868c2dd06c7619cced/images/product-screenshot.png)
  
🎥 The link to the full movie file showing functionality of the application can be found below: 
<br>

- [NPM Test, Seed, and Start](https://drive.google.com/file/d/1bvqV7ZctUfLJMiobtK20Ob-Bc7E8wn2q/view)
- [Insomnia_Databases](https://drive.google.com/file/d/1Sjw_no8ZjbZH9kfufqh51LP9bE3vqHje/view)
 
<br>

## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
💾   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
💻   
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## Contributing
[DonL](https://github.com/DonL44)

## Questions
✉️ Contact me with any questions: [email](Donovan1478@yahoo.com) , [GitHub](https://github.com/DonL44)<br />
