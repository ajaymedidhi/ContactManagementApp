# Contact Management Application

Contact Managment Application is a web application designed to manage contacts like add , update ,edit and delete. The application consists of a backend built with Django and Sqlite, and a frontend built with React.

## Features
- **User Authentication:** Register and log in users with JWT-based authentication.
- **Event Management:** CRUD operations for managing events.
- **Weather Integration:** Fetch weather data based on event location using an external weather API.
- **Session Management:** Secure session management for authenticated users.

## Project URL
You can access the project at: [EventManager URL](https://66adf47e43ec4d4f7df6f5b1--flourishing-mandazi-57b93f.netlify.app/)

## Sample Credentials
Use the following credentials to log in to the application:

- **Email:** ajay@gmail.com
- **Password:** password123


## Project Setup

### Prerequisites
- Node.js (v14 or later)
- Mongodb

### 1. Initialize a Node.js Project
Create a new folder for your project and initialize it with `npm init` to create a `package.json` file.

### 2. Install Dependencies
Install React for the front end using Create React App and the necessary dependencies for the backend.

```bash
npx create-react-app client
npm install express mongodb mongoose
```

### 3. Database Setup
Setup MongoDB to handle data for users, events, and sessions. You'll need to create collections for each of these entities. Utilize mongoose in Node.js to manage database operations.

## Backend Development
### Express Setup
Set up an Express server that will handle API requests.
