# FullStack To-Do App

A comprehensive to-do application built using ASP.NET Core, MongoDB, and React. This project serves as a demonstration of a complete FullStack application, from front-end development with React to back-end API creation with ASP.NET Core, integrated with a NoSQL MongoDB database.

## Features:

- User Registration and Authentication
- Create, Read, Update, and Delete tasks
- Filtering and Searching tasks
- User-specific task views
- Sleek and responsive UI

## Getting Started:

### Prerequisites:

- .NET Core SDK
- Node.js and npm
- MongoDB instance (local or cloud like MongoDB Atlas)

### Setting up:

1. **Backend**:
   - Navigate to the backend directory.
   - Adjust the appsettings.json (or better, use environment variables) to point to your MongoDB instance/connection string.
   - Run the following command to start the API:
     ```
     dotnet run
     ```

2. **Frontend**:
   - Navigate to the frontend directory.
   - Install the necessary npm packages:
     ```
     npm install
     ```
   - Start the React app:
     ```
     npm start
     ```

3. Visit `http://localhost:3000` (or wherever your React app is hosted) in your browser.

## Deployment:

- Backend: Deploy the ASP.NET Core API to your preferred cloud provider.
- MongoDB: Ensure the deployed backend can access your MongoDB instance. If using MongoDB Atlas, whitelist necessary IPs.
- Frontend: Deploy the React frontend to platforms like Netlify, Vercel, etc.

## Contributing:

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License:

[MIT](https://choosealicense.com/licenses/mit/)
