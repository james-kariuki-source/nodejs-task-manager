# Task Manager Web App

This is a simple Task Manager web application built with Node.js, Express, and MongoDB.

## Features

- Create, Read, Update, and Delete tasks.
- RESTful API for task management.
- MongoDB for data storage.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MongoDB installed and running locally or remotely.

## Installation

1. Clone the repository:

   https://github.com/james-kariuki-source/nodejs-task-manager.git

2. Navigate to the project directory:

   cd task-manager

3. Install dependencies:

   npm install

4. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add the following variables:

     PORT=3000
     MONGODB_URI=your_mongodb_connection_string

5. Start the application:

   npm start

## Usage

- Access the application through your browser or API client at `http://localhost:3000`.
- Create, view, update, and delete tasks through the user interface or API endpoints.

## API Endpoints

- `POST  /api/v1/tasks`: Get all tasks.
- `GET  /api/v1/tasks`: Get all tasks.
- `GET /api/v1/tasks/:id`: Get a specific task by ID.
- `PATCH /api/v1/tasks/:id`: Update a task.
- `DELETE /api/v1/tasks/:id`: Delete a task.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the [MIT License](LICENSE).
