# E-com

## Description

My motivation for this application was to practice using sequelize to create a database for an e-commerce store. I built it to be able to connect different api endpoints to a sql database that was created and seeded using js, express, mysql2, and sequelize. It solves the problem of organizing and being able to retrieve and update information about the products in the online store. I learned a lot about the relationships between the data and how to connect a sql database to an application and utilize it using sequelize.


## Table of Contents (Optional)


- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To install, clone the repo using git clone and set up your connection to your database. You need to change the sequelize sync in server.js to force: true to drop and create the database, when you run node server.js in terminal. Close server then run npm run seed to seed database, if you dont want to add some data to start. Change sequelize sync back to force: false, then you can run node server.js to access your database.

## Usage

After creating the db and opening the server with node server.js. You can Create, Update, Delete and Get information on the products, categories, and tags using the api endpoints /api/categories /api/categories/:id /api/products/ /api/products/:id /api/tags /api/tags/:id. View the link of a demo video showcasing the CRUD for each table. 
[DEMO VIDEO](https://drive.google.com/file/d/1TCdhLNs8FaSw1vPz6FHRxq1NGbvVQv6h/view?usp=sharinghttps://drive.google.com/file/d/1TCdhLNs8FaSw1vPz6FHRxq1NGbvVQv6h/view?usp=sharing)



## Credits

Ed X Bootcamps
Utilized express, node, mysql, and sequelize

## License
N/A

---