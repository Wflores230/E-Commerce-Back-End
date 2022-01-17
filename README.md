# E-Commerce Back End

## Link
Your walkthrough video showing all the routes for products and tags being tested in Insomnia Core.
https://drive.google.com/file/d/1AnQYpWbdJ51vNOPc10KQ89-WbGSbHvl6/view

## Installation
You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

Make sure to edit and enter your own root and password. Run command lines in terminal such as:

```
npm i
```

and

```
npm run seed
```

## Description
This is the back end for an e-commerce site and it uses a working Express.js API to use Sequelize to interact with a MySQL database. It contains three routes: products, tags, and categories; offering the user to perform CRUD operations on each one.

## Screenshots

![Screenshot (84)](https://user-images.githubusercontent.com/76802722/116801665-dbf7b000-aad9-11eb-9f27-350196c6a584.png)
![Screenshot (82)](https://user-images.githubusercontent.com/76802722/116801667-dd28dd00-aad9-11eb-9f50-aa25961459dc.png)
![Screenshot (83)](https://user-images.githubusercontent.com/76802722/116801668-de5a0a00-aad9-11eb-95dc-6d9faed9eda0.png)
