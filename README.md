# E-Commerce Back End

## Description
This project provides the back end for an e-commerce website. It uses Express.js for API development and Sequelize as an Object-Relational Mapping (ORM) tool to interact with a MySQL database. The goal is to enable an internet retail company to compete with other e-commerce companies by utilizing the latest technologies.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this application locally, you need to follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>

2.Install Dependencies:
```npm install```

3. Create a MySQL Database:
```mysql -u <username> -p
source db/schema.sql```


4. Set up Environment Variables

- Create a `.env` file in the root of your project.
- Add the following information to the `.env` file:
DB_NAME=ecommerce_db
DB_USER=<your-mysql-username>
DB_PW=<your-mysql-password>

5. Seed the Database

```bash
npm run seed

## 6. Start the Application

```bash
npm start

