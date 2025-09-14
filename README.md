# Product Store

A MERN stack project for managing products, featuring a Node.js/Express backend and a React frontend. This project demonstrates CRUD operations, RESTful API design, and MongoDB integration.

## Project Structure

- `backend/` - Node.js/Express server, API routes, controllers, models
- `frontend/` - React application (UI)

## Database Settings

The backend uses MongoDB. Database configuration is located in `backend/config/db.js`.

### Setup MongoDB Connection
1. Create a `.env` file in the `backend/` directory.
2. Add your MongoDB URI:
   ```env
   MONGO_URI=mongodb://localhost:27017/product-store
   ```
3. The server will use this URI to connect to MongoDB.

## Running the Project

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)

### Backend
1. Navigate to the backend folder:
   ```powershell
   cd backend
   ```
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start the server:
   ```powershell
   npm start
   ```
   The server runs on `http://localhost:5000` by default.

### Frontend
1. Navigate to the frontend folder:
   ```powershell
   cd ../frontend
   ```
2. Install dependencies:
   ```powershell
   npm install
   ```
3. Start the React app:
   ```powershell
   npm start
   ```
   The app runs on `http://localhost:3000` by default.

## Environment Variables
- Place your environment variables in `.env` files (not committed to git).
- Example for backend:
  ```env
  MONGO_URI=your_mongodb_uri
  PORT=5000
  ```

## License
MIT
