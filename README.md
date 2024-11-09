# GoFood - Food Ordering Website

GoFood is a food ordering platform built on the MERN stack (MongoDB, Express, React, Node.js), similar to platforms like Zomato. This guide will walk you through setting up and running the project on your local machine.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

## Getting Started

### 1. Clone the Repository

Start by cloning the project repository from GitHub:

```bash
git clone https://github.com/your-username/gofood.git
cd gofood
2. Install Dependencies
Navigate into the project folders and install dependencies for both the backend and frontend:

Backend (API server):

bash
Copy code
cd backend
npm install
Frontend (React app):

bash
Copy code
cd ../frontend
npm install
3. Set Up Environment Variables
Create an .env file in the backend folder with the following environment variables:

env
Copy code
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
Replace your_mongodb_connection_string and your_jwt_secret with your actual MongoDB URI and a secure JWT secret.

4. Start the Development Servers
Start the backend server:

bash
Copy code
cd ../backend
npm run dev
In a new terminal window, start the frontend server:

bash
Copy code
cd ../frontend
npm start
5. Access the Application
Once both servers are running, you can access the GoFood application at:

arduino
Copy code
http://localhost:3000
Additional Scripts
Backend: npm run dev - Starts the backend server with live reloading.
Frontend: npm start - Starts the frontend in development mode.
Technologies Used
Frontend: React, Redux, CSS
Backend: Node.js, Express
Database: MongoDB
