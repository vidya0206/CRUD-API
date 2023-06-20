**Project Name - CRUD API with MongoDB**

**Description**

This project implements a CRUD (Create, Read, Update, Delete) API connected to a MongoDB database. It provides endpoints to perform basic CRUD operations on data stored in the MongoDB database.

**Requirements**

**Node.js:** Make sure you have Node.js installed on your machine. You can download it from the official Node.js website: https://nodejs.org
**MongoDB:** Ensure that you have a MongoDB server running or access to a MongoDB database for connection.

**Installation**

1.Clone the repository:

    git clone hhttps://github.com/vidya0206/CRUD-API.git

2.Navigate to the project directory:

    cd crud-api-mongodb

3.Install dependencies:

    npm install

4.Configure MongoDB connection:

    Open the config.js file in the project's root directory.
    Update the MongoDB connection string with your MongoDB server details.

5.Start the server:

    npm start

6.The  api will now be running on http://localhost:3000.

    The following endpoints are available:

**API Endpoints**

   GET   /products - Get all products
   GET   /products/:id - Get a specific product by ID
   POST  /products - Create a new product
   PUT     /products/:id - Update a product by ID
   DELETE  /products/:id - Delete a product by ID

**Usage**

To use the API, you can make HTTP requests to the specified endpoints using a tool like Postman, or any other API testing tool.

Make sure to replace :id in the endpoints with the actual ID of the resource you want to retrieve, update, or delete.

**Contributing**

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please create a new issue or submit a pull request.
