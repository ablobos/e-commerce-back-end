# E-Commerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This application builds the back end for an e-commerce site using the latest technolgies and configures it to use sequelize to interact with a MySQL database. The application allows users to retrieve data for categories, products, and tags using API GET routes in Insomnia and successfully create, update, and delete data using API POST< PUT and DELETE routes.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Preview](#preview)
- [License](#license)

## Technologies Used

- Express
- Node
- MySQL
- Dotenv
- Sequelize

## Installation

- Source the schema.sql files
- `npm run seed`
- `node server.js` to start up the server

## Usage

- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies
---
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Preview

https://user-images.githubusercontent.com/117130907/230463167-5d465e2e-bca7-4678-8ed0-26429599f294.mp4

## License

See LICENSE in repo
