
<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End 👋</h1>
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/jpd61/e-commerce-backend" />
    <img src="https://img.shields.io/github/languages/top/jpd61/e-commerce-backend"  />
    <img src="https://img.shields.io/github/issues/jpd61/e-commerce-backend" />
    <img src="https://img.shields.io/github/last-commit/jpd61/e-commerce-backend" >
    <a href="https://github.com/jpd61"><img src="https://img.shields.io/github/followers/jpd61?style=social" target="_blank" /></a>
    <a href="https://twitter.com/jpdewoody">
        <img alt="Twitter: jpdewoody" src="https://img.shields.io/twitter/follow/jpdewoody.svg?style=social" target="_blank" />
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
  
💻 Below is the gif showing the functionality of the application:
  
![DB Setup and Start](./animations/DB%20setup%20and%20start.gif)

![GET All](./animations/GET%20all.gif)

![GET All by ID](./animations/GET%20by%20ID.gif)

![POST PUT DELETE Products and Tags](./animations/POST%20PUT%20DELETE%20Tags%20and%20Products.gif)

![POST PUT DELETE Categories](./animations/POST%20PUT%20DELETE%20Categories.gif)
  
🎥 The full movie file showing functionality of the application can be found in the animations directory
  
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
- [Testing](#testing)
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

## Testing
✏️

No testing is currently set up

## Contributing
:octocat: [Joseph DeWoody](https://github.com/jpd61)

## Questions
✉️ Contact me with any questions: [email](mailto:jpd@dewoodyoil.com) , [GitHub](https://github.com/jpd61)<br />
