# REST API Project 🚀

## Description
This project is a RESTful API built using [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/), and [MongoDB](https://www.mongodb.com/). It provides CRUD (Create, Read, Update, Delete) functionality for managing resources. The API follows REST principles and communicates using JSON.

## File Structure 📁
- `public/`: 🖼️ Directory for static files such as CSS, images, etc.
  - `style.css`: 🎨 CSS file for styling the application.
- `views/`: 📝 Directory containing the EJS templates for rendering HTML views.
  - `edit.ejs`: 🖋️ EJS template for editing a resource.
  - `index.ejs`: 📋 EJS template for listing all resources.
  - `new.ejs`: ➕ EJS template for creating a new resource.
  - `show.ejs`: 👁️‍🗨️ EJS template for displaying details of a resource.
- `index.js`: 🚀 The main JavaScript file containing the server logic for the REST API.
- `node_modules/`: 📦 Directory containing all the npm packages installed for this project.
- `package.json`: 📄 File containing metadata about the project and the list of dependencies.
- `package-lock.json`: 🔒 File automatically generated for any operations where npm modifies either the `node_modules` tree or `package.json`.

## Installation and Setup 🛠️
- [Install Node.js](https://nodejs.org/): Node.js is required to run this project.
- Run `npm install` to install all dependencies.
- [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/): Install and set up MongoDB on your machine.
- Configure the MongoDB connection in `index.js`.

## Usage ℹ️
1. Clone the repository to your local machine.
2. Follow the installation and setup steps above.
3. Start the server by running `node index.js`.
4. Use an API testing tool like Postman to interact with the endpoints.

## Endpoints 🛤️
- `GET /resources`: Retrieve all resources.
- `GET /resources/:id`: Retrieve a specific resource by ID.
- `POST /resources`: Create a new resource.
- `PUT /resources/:id`: Update a specific resource by ID.
- `DELETE /resources/:id`: Delete a specific resource by ID.

## Technologies Used 💻
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [EJS](https://ejs.co/): (Embedded JavaScript) for templating
- RESTful API principles

## Contributing 🙌
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.
