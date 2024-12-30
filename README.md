# Contact Management Application

Contact Managment Application is a web application designed to manage contacts like add , update ,edit and delete. The application consists of a backend built with Django and Sqlite, and a frontend built with React.

## Features
- **User Authentication:** Register and log in users with JWT-based authentication.
- **Event Management:** CRUD operations for managing events.
- **Weather Integration:** Fetch weather data based on event location using an external weather API.
- **Session Management:** Secure session management for authenticated users.

## Project URL
You can access the project at: [Contact Management App URL](https://contactmanagement7.vercel.app/)

## Project Setup

### Prerequisites
- Django
- sqlite

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
