# E-commerce Back End

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
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

## Dificulties
I had problems working out how to seed the db to the routes. But I eventually figured it out! I needed to create a .env file to get everything correct. Also I had to skim through the modules and do a lot of documentation research to figure out why some of my npm packages werent working.

## Screenshot



## Installation

1.) Download zip or clone git to local pc
2.) npm install
3.) mysql -u root -p
4.) source db/schema.sql
5.) quit
6.) npm run seed
7.) npm run
8.) open in local host and/or insomnia

## Links

github repo: https://github.com/SyrusFarris/e-commerce-backend

video: https://drive.google.com/file/d/1wAqlPEzFYqKpYOKlPyN76LQlc-6eV9_v/view