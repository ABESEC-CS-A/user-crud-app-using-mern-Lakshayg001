# User Management System

A MERN (MongoDB, Express.js, React.js, Node.js) stack application for managing users with CRUD operations.

## Features

- Create new users with email, name, and role
- Read/List all users
- Update existing users
- Delete users
- Responsive design with Bootstrap
- Form validation
- Real-time updates

## Tech Stack

- **Frontend**: React.js, Bootstrap, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Additional Libraries**:
  - cors (for handling CORS)
  - dotenv (for environment variables)
  - mongoose (for MongoDB object modeling)

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/ABESEC-CS-A/user-crud-app-using-mern-Lakshayg001.git
cd user-crud-app-using-mern-Lakshayg001
```

2. Install dependencies:

```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
   - Create a `.env` file in the backend directory
   - Add the following variables:

```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/user-management
```

4. Start the application:

```bash
# Start backend server (from backend directory)
npm start

# Start frontend development server (from frontend directory)
npm start
```

5. Access the application:
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## API Endpoints

- GET `/api/users` - Get all users
- POST `/api/users` - Create a new user
- PUT `/api/users/:id` - Update a user
- DELETE `/api/users/:id` - Delete a user

## Contributing

Feel free to submit issues and enhancement requests.
