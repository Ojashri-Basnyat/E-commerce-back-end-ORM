## E-commerce-back-end-ORM

My Solution to Week 13 Challenge

## Table of Contents

- Description
- User Story
- Installation
- Usage
- License
- Contributing
- Tests
- Questions

Back end for an e-commerce website built using MySQL2, Express, Sequelize and dotenv so that a company can compete with other e-commerce companies.

When the manager of the internet retail company, GIVEN a functional Express.js API, adds database name, MySQL username and password to an environment variable, then the manager is able to connect
to a database using Sequelize.
When the manager enters schema and seed commands, then a development database is created and is seeded with test data.
When the manager enters the command to invoke the application, then the server is started and the Sequelize models are synced to the MySQL database. 
When the manager opens API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON. 
When the manager tests API POST, PUT, DELETE routes in Insomnia, then the manager is successfully able to create, update, and delete date in the database. 

## Installation
Install npm, mysql2, sequelize, dotenv and express.js. 

## Usage
Run the following command at the root of your project and answer the prompted questions: 
mysql -u root -p 
Enter PW when prompted
source db/schema.sql
quit
npm run seed
npm start

## Tests
Please use insomnia to GET, POST, PUT and DELETE rows.

## Questions
Please don't hesitate to contact me with any questions: [email](mailto:basnyat.ojashri@gmail.com), [GitHub](https://github.com/Ojashri-Basnyat)<br />

