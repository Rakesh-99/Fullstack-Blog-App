# MERN Stack Blog App

Welcome to the MERN Stack Blog App! This is a full-featured blog application built using the MERN stack (MongoDB, Express, React, Node.js) with additional features like Firebase Google login, advanced authentication, and more.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Environment Variables](#environment-variables)

## Features

- **Admin Panel**: Manage users, posts, and comments with an admin panel.
- **User Authentication**: Secure login and signup with JWT and password hashing (bcrypt).
- **Firebase Google Login**: Easy login with Google using Firebase.
- **User Profiles**: Update user profile information.
- **Display Preferences**: Toggle between light and dark themes.
- **Pagination**: Navigate through posts with pagination.
- **Search and Filter**: Search and filter posts by categories or tags.
- **Commenting**: Comment on posts and like comments.
- **Responsive Design**: Fully responsive design for all devices.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: Firebase, JSON Web Tokens (JWT)
- **Styling**: Tailwind CSS
- **State Management**: Redux-Toolkit
- **Deployment**: Vercel

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Rakesh-99/Fullstack-Blog-App
   cd blog-app
   ```

2. Install frontend dependencies:

```
cd client
npm install
```

3. Install backend dependencies:

```
cd server
npm install
```

## Usage

1 .Set up environment variables (see Environment Variables).

Start the backend server:

```
cd server
npm run dev
```

Start the frontend development server:

```
cd ../client
npm start
```

Open your browser and navigate to http://localhost:5173 to view the app.

## Folder structure

```
/blog-app
  /client     # Frontend code (React)
  /server     # Backend code (Node.js, Express)
```

## Environment Variables

Create a .env file in the server directory and add the following environment variables:

```
PORT=your_port
DB_URL=your_db_url
JWT_TOKEN=your_jwt_token

```
