# Express.js API with Sequelize and MySQL

This is a functional Express.js API that connects to a MySQL database using Sequelize. It provides routes for managing categories, products, and tags, and supports basic CRUD operations.

## Getting Started

To set up and run this project on your local machine, follow these steps:

### Prerequisites

You will need the following software installed on your system:

- Node.js
- MySQL Server

### Installation

1. Clone the repository to your local machine:

shell
Copy code
cd express-mysql-api
Install the project dependencies:

shell
Copy code
npm install
Create an environment variable file (.env) in the project root and add the following variables:

env
Copy code
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
Database Setup
Run the following commands to create the development database and seed it with test data:

shell
Copy code
npx sequelize-cli db:create
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all
Running the Application
Start the Express.js server:

shell
Copy code
npm start
The server will be running on http://localhost:3000.

Access the API routes using a tool like Insomnia or Postman:

GET routes for categories, products, and tags will return data in JSON format.

Use POST, PUT, and DELETE routes to create, update, and delete data in the database.

API Endpoints
GET /api/categories: Get a list of all categories.

GET /api/categories/:id: Get a specific category by ID.

POST /api/categories: Create a new category.

PUT /api/categories/:id: Update an existing category.

DELETE /api/categories/:id: Delete a category.

GET /api/products: Get a list of all products.

GET /api/products/:id: Get a specific product by ID.

POST /api/products: Create a new product.

PUT /api/products/:id: Update an existing product.

DELETE /api/products/:id: Delete a product.

GET /api/tags: Get a list of all tags.

GET /api/tags/:id: Get a specific tag by ID.

POST /api/tags: Create a new tag.

PUT /api/tags/:id: Update an existing tag.

DELETE /api/tags/:id: Delete a tag.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Express.js
Sequelize
MySQL

## links

[GitHub](https://github.com/M1TCH3llM/employee)

[Video](https://drive.google.com/file/d/1fxyw3AaDcUfbZ_SsP24VcwGajwW5SxGg/view)
