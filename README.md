
# 🏋️‍♀️ Fitness Scheduler

A full-stack fitness scheduling web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It helps users create, manage, and track their workout schedules efficiently.

## 🚀 Features

- User registration and login
- Create, edit, and delete fitness schedules
- View schedules based on dates
- Responsive and user-friendly interface
- RESTful API for frontend-backend communication

## 🛠️ Tech Stack

- **Frontend:** React, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **Version Control:** Git & GitHub

## 🧩 Getting Started

### Prerequisites

- Node.js and npm
- MongoDB

### Installation Steps

1. **Clone the repository**

```bash
git clone https://github.com/shreyareddych/Fitness_Scheduler.git
cd Fitness_Scheduler
```

2. **Install backend dependencies**

```bash
cd backend
npm install
```

3. **Install frontend dependencies**

```bash
cd ../frontend
npm install
```

4. **Set up environment variables**

In the `backend` folder, create a `.env` file and add:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
```

5. **Start the application**

- Start the backend server:

```bash
cd backend
npm start
```

- Start the frontend app:

```bash
cd ../frontend
npm start
```

Visit `http://localhost:3000` to use the app.

