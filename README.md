﻿# MediConnect

MediConnect is a full-stack web application designed to connect patients with doctors, manage appointments, and streamline healthcare communication. The project features a React frontend and a Node.js/Express backend with MongoDB for data storage.

## Features

- User authentication and registration (patients & doctors)
- Doctor application and approval workflow
- Book, view, and manage appointments
- Admin dashboard for managing users and doctors
- Real-time notifications for appointments and approvals
- Secure routes for different user roles (Admin, Doctor, User)
- Responsive and modern UI

## Tech Stack

- **Frontend:** React, Redux, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB instance (local or cloud)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/balkirat0001/MediConnect.git
   cd MediConnect
   ```
2. Install server dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file (see `.env.example` if available).
4. Start the backend server:
   ```bash
   npm start
   ```
5. Set up the client:
   ```bash
   cd client
   npm install
   npm start
   ```

## Folder Structure

- `client/` - React frontend
- `controllers/` - Express controllers
- `models/` - Mongoose models
- `routes/` - API routes
- `middlewares/` - Custom middleware
- `config/` - Database configuration
- `server.js` - Entry point for backend

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

