#  Build a CRUD API with Node.js and Sequelize

In this api project, I am going to build a complete CRUD API with Node.js and Sequelize. The REST API will run on an Express.js server and have endpoints for performing CRUD operations against a PostgreSQL database.

## Key Points:

- Prerequisites
- Run the Node.js Sequelize CRUD API Locally
- Run the Sequelize CRUD API with React.js
- Setup the Node.js Project
- Setup the Database
- Create the Sequelize Model
- Create Validation Schemas with Zod
- Create the CRUD Route Handlers
    - Create New Record
    - Edit Existing Record
    - Find One Record
    - Find All Records
    - Delete a Record
- Create the API Routes
- Setup CORS and API Router
- Test the CRUD API
    - Perform Create Operation
    - Perform Update Operation
    - Perform Read Operation
    - Perform Delete Operation

## Prerequisites:

- Ensure you have the latest or LTS version of Node.js installed on your machine. If not visit the official [Node.js website](https://nodejs.org/) to download and install the binary.

- Ensure you have Docker installed on your system. It’s needed to run the Postgres server in a Docker container.

- Basic knowledge of Express.js and Node.js will be beneficial

## Run the Node.js Sequelize CRUD API Locally:

- Download or clone the Sequelize CRUD API project from https://github.com/Arsenethierry/nodejs-postgresql-crud-oprations and open the source code in an IDE.

- In the console of the root directory, run yarn or yarn install to install all the required dependencies.

- Run docker-compose up -d to start the Postgres server in the Docker container.

- Run yarn start to sync the Sequelize schema with the Postgres database and start the Express.js HTTP server.

- Finally, open an API testing software like [Postman](https://www.postman.com/) to test the endpoints. Alternatively, you can set up the React CRUD application to interact with the API.