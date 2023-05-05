# Under construction

[Client](https://github.com/CodeCommunityHub/task-management-client)

# MERN Task Management App - Backend API

This is the backend API for the MERN Task Management App, built with Node.js, Express, and MongoDB. It provides the necessary endpoints for user authentication, task management, and project management.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js (version 14.x or higher)
- MongoDB (version 4.x or higher)

### Installation

1. Clone the repository:
   git clone <https://github.com/CodeCommunityHub/task-management-api>

2. Navigate to the project directory:
   cd test-task-management-api

3. Install dependencies:
   npm install

4. Create a `.env` file in the root directory of the project, and add the following environment variables:

```
 MONGODB_URI=mongodb://localhost:27017/your-db-name
 JWT_SECRET=your-secret-key
 PORT=3001
```

5. Start the development server:
   The server will be running on `http://localhost:3001`.

## API Endpoints

### User Routes

- Register a new user: `POST /api/users/register`
- Log in an existing user: `POST /api/users/login`
- Reset user password: `POST /api/users/reset-password`

### Task Routes

- Get all tasks: `GET /api/tasks`
- Get a specific task: `GET /api/tasks/:id`
- Create a new task: `POST /api/tasks`
- Update an existing task: `PUT /api/tasks/:id`
- Delete a task: `DELETE /api/tasks/:id`

### Project Routes

- Get all projects: `GET /api/projects`
- Get a specific project: `GET /api/projects/:id`
- Create a new project: `POST /api/projects`
- Update an existing project: `PUT /api/projects/:id`
- Delete a project: `DELETE /api/projects/:id`

## Testing

To run the test suite, execute the following command:
npm test

## Deployment

Instructions for deploying the backend API to a production environment can be found in the `DEPLOYMENT.md` file.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
