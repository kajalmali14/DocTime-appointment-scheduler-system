# DocTime Appointment Scheduler

The **DocTime Appointment Scheduler** is a full-stack web application designed to streamline appointment booking for clinics, hospitals, and individual practitioners. Built using **Node.js, Express.js, MongoDB, and React.js**, this project supports secure login, role-based access, appointment CRUD, and admin controls.

## 🔧 Tech Stack

### Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- bcrypt.js (for password hashing)
- dotenv (for environment variables)
- CORS & body-parser

### Frontend:
- React.js
- Axios
- React Router
- Tailwind CSS (optional styling)
- Calendar & Date Picker Libraries

## ✨ Features

### User:
- Signup/Login (JWT-secured)
- Book appointments
- View, reschedule, or cancel appointments
- Profile management

### Doctor/Admin:
- View all appointments
- Update appointment status (Approved/Rejected)
- Delete appointments
- View patients by date/doctor

### System:
- Email notifications (Optional)
- Appointment conflict checks
- Admin dashboard
- Mobile responsiveness

## 📁 Project Structure

```
root/
│
├── client/               # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.js
│
├── models/               # Mongoose models
├── routes/               # Express routes
├── controllers/          # Controller logic
├── middleware/           # Auth & error handling
├── server.js             # App entry point
├── .env                  # Environment variables
└── .gitignore
```

## 🚀 How to Run Locally

### 1. Clone Repository

```
git clone https://github.com/your-username/DocTime-Appointment-Scheduler.git
cd DocTime-Appointment-Scheduler
```

### 2. Setup Backend

```
npm install
npm run server
```

### 3. Setup Frontend

```
cd client
npm install
npm start
```

App will run on `http://localhost:3000` (frontend) and `http://localhost:5000` (backend).

## 📂 .gitignore Example

```
node_modules/
.env
client/node_modules/
```

## 📌 Deployment
1. Push this project to GitHub.
2. Add repository link to your LMS portal submission.

## 👤 Author

**Kajal Kailas Mali**  
Intern at Celebal Technologies  
Project: DocTime Appointment Scheduler
