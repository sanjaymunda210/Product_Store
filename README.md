# Project Title: Product Store

## Initial Commit:

This is the initial commit of the Product Store project. Below is a brief overview of the project structure and the steps taken so far.

### Project Structure:

The project is divided into two main folders: backend and frontend. The backend folder will contain all the server-side code, including the API and database connections. The frontend folder will contain the client-side code, including the user interface and any necessary JavaScript files.

### Package Installation:

The following packages have been installed using npm:

- express: a popular Node.js web framework for building the backend API
- mongoose: a MongoDB object modeling tool for interacting with the database
- dotenv: a package for loading environment variables from a .env file
- nodemon: a package for automatically restarting the server during development
- Package.json: The package.json file is located outside of the backend and frontend folders. This is because the package.json file is used to manage dependencies and scripts for the entire project, not just a specific folder.

### Backend Logic:

The backend folder contains the server-side code for the project. Currently, it includes a basic server setup using Express.js and a connection to a MongoDB database using Mongoose. The server is configured to listen on port 5000.

### Database Connection:

A connection to a MongoDB database has been established using Mongoose. The database URI is stored in a .env file to keep it secure.

### Server Setup:

A basic server has been set up using Express.js. The server is configured to respond to GET requests to the root URL (/) and returns a message indicating that the server is ready.
