# E-commerce Back End 

## Descritption
This app is the backend portion of an E-Commerce website. Express.js was used for the server and MySQL for the database along with Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used to make requests and updates from the database which are joined through Sequelize queries.

## Link to Video Walkthrough
https://drive.google.com/file/d/15wqp_VIp3fpDvZVOcZZO9aVyiNEKsp6N/view

## Installation Instructions
<br/> - Open MySQL Shell
<br/> - source db/schema.sql
<br/> - quit
<br/> - npm run seed
<br/> - npm start

## Technologies
<br/> MySQL
<br/> Node.js
<br/> Sequelize 

## User Experience
A client is able to manage/audit/remove products/categories/tags from a database. Viewing is possible through Insomnia interface

## Lessons and musings
This project went as expected. The source file was given had much of the logic required for the project. The main focus of the project was to emphasize the use of ORM (object relational mapping) Sequlize to alleviate the the manual programming of the MySQL database. This worked out swimmingly as sequilize did a great job of organizing material easily. I didn't face many problems outside of a few syntax errors on my part, but throwing the catch err's were able to identify the problems readily. 

