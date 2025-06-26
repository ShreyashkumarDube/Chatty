# Chatty - Full Stack Chat Application

A real-time chat application built with React, Vite, Zustand, Express, MongoDB, Socket.IO, and Cloudinary.

## Features

- User authentication (signup, login, logout)
- Real-time messaging with Socket.IO
- Image upload for profile and messages (Cloudinary)
- Responsive UI with theme support (DaisyUI + TailwindCSS)
- Online users indicator

## Project Structure

```
.
├── backend/
│   ├── src/
│   ├── package.json
│   └── .env
└── frontend/
    ├── src/
    ├── package.json
    └── .env
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB database
- Cloudinary account (for image uploads)

---

## Backend Setup

1. **Install dependencies:**

   ```sh
   cd backend
   npm install
   ```

2. **Configure environment variables:**

   Create a `.env` file in the `backend` folder:

   ```
   PORT=5001
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   NODE_ENV=development
   ```

3. **Run the backend server:**

   ```sh
   npm run dev
   ```

   The backend will run on [http://localhost:5001](http://localhost:5001).

---

## Frontend Setup

1. **Install dependencies:**

   ```sh
   cd frontend
   npm install
   ```

2. **Run the frontend dev server:**

   ```sh
   npm run dev
   ```

   The frontend will run on [http://localhost:5173](http://localhost:5173).

---

## Usage

- Open [http://localhost:5173](http://localhost:5173) in your browser.
- Sign up for a new account or log in.
- Start chatting with other users!

---

## Scripts

### Backend

- `npm run dev` — Start backend with nodemon

### Frontend

- `npm run dev` — Start frontend dev server
- `npm run build` — Build frontend for production
- `npm run preview` — Preview production build

---

## Technologies Used

- **Frontend:** React, Vite, Zustand, TailwindCSS, DaisyUI, Socket.IO Client
- **Backend:** Express, MongoDB, Mongoose, Socket.IO, Cloudinary, JWT

---
