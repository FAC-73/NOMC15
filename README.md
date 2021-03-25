# E-Commerce Back End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
Application for an e-commerce site back end. Built using Express.js API to use Sequelize to interact with a MySQL database.
<br />

![E-Commerce Back End](https://github.com/FAC-73/NOMC15/blob/main/assets/Application_demo.png?raw=true)
Watch the [video](https://drive.google.com/file/d/1MnX1TKSeZnrkm2WWYOwy_A2LwmL_cR61/view?usp=sharing)
<br />

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
  
## Description

A back end application for an e-commerce site allowing users to view all products, categories and tags, as well as refine by ID. Users can also add, update, and delete products, categories and tags in Insomnia core. API Routes are added to Perform RESTful CRUD Operations
<br><br>
This application is configured with an Express.js API, and uses Sequelize to interact with a MySQL database.
<br><br>
As this application isn't deployed, use this link to watch the [video](https://drive.google.com/file/d/1MnX1TKSeZnrkm2WWYOwy_A2LwmL_cR61/view?usp=sharing) demonstrating the full functionality of the application


## Installation
Clone the repo to your local development environment.

```md
git clone https://github.com/FAC-73/NOMC15.git
```
Navigate to the NOMC15 folder directory using the command prompt.

Run `npm install` to install all dependencies. in terminal or bash
<br><br>
Run `node seeds` to seed the data
<br><br>
Run `npm start` to run the application in terminal or bash
<br><br>
Use http://localhost:3001 [or whatever terminal port you have specified] in Insomnia to run the server requests


## Licence
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br />

## Contributing
[Kay Davis](https://github.com/FAC-73)
<br />

## Built with
- [Javascript](https://www.w3schools.com/jsref/default.asp)
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Sequelize](https://sequelize.org/)
- [mySQL](https://www.mysql.com/)
- [JSON](https://www.json.org/json-en.html)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [InsomniaCore](https://insomnia.rest/products/insomnia)


## Questions?

### GitHub Username:
[FAC-73](https://github.com/FAC-73)

###  ✉️ Email me:
[kaydavis21@googlemail.com](mailto:kaydavis21@googlemail.com)

### 📁 GitHub project repo:
[https://github.com/FAC-73/NOMC15](https://github.com/FAC-73/NOMC15)

