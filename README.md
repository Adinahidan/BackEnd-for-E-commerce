# BackEnd-for-E-commerce

## Description
This is the back end for an e-commerce website built using the latest technologies. It utilizes Express.js as the web framework, Sequelize as the ORM to interact with a MySQL database, and follows the RESTful API architecture. The application provides API routes for managing categories, products, and tags.

## Installation
To install the necessary dependencies, run the following command:
npm install

## Usage
1. Set up the database by executing the SQL commands in the `schema.sql` file located in the `db` folder.
2. Create a `.env` file in the root directory and add the following environment variables:
DB_NAME=
DB_USER=
DB_PW=

Enter your desired database name, MySQL username, and password.

1. Seed the database with sample data by running the following command:
npm run seed


1. Start the server using the following command:
npm start


1. Open your preferred API testing tool (e.g., Insomnia Core) and access the available API routes for categories, products, and tags.

## Features
- Create, read, update, and delete categories, products, and tags.
- Establish associations between categories, products, and tags.
- Retrieve formatted JSON data for categories, products, and tags.
- Built with the latest technologies and follows RESTful API architecture.

## Technologies
- Express.js
- Sequelize
- MySQL2
- dotenv

## Credits
This project was created as a coding challenge. The starter code was provided by the challenge organizers.

## License
This project is licensed under the [MIT License](LICENSE).




