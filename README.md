# 🎟️ EventHub – Event Management System

A full-stack Event Management System built with the MERN stack that enables users to discover events, book tickets, and manage bookings while providing administrators with event management, analytics, and QR-based ticket verification.

<p align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js\&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite\&logoColor=white)

</p>

---

## 📖 About the Project

EventHub is a web application designed to simplify event organization and management. Users can explore events, book tickets, and access their bookings, while administrators can manage events, monitor booking activity, and verify tickets.

This project demonstrates full-stack web development using the MERN stack.

## ✨ Features

### 👤 User Features

* User registration and login
* Browse and explore available events
* View event details
* Book tickets and validate seat availability
* Generate QR-based tickets
* Download tickets as PDF
* Responsive user interface

### 🛠️ Administrator Features

* Role-based access control
* Create, update, and delete events
* Publish and unpublish events
* Upload event images
* Verify tickets using QR codes
* Prevent duplicate check-ins
* View booking and revenue analytics

## 🛠️ Technologies Used

| Category       | Technologies                                     |
| -------------- | ------------------------------------------------ |
| Frontend       | React.js, Vite, React Router, Axios, Context API |
| Backend        | Node.js, Express.js                              |
| Database       | MongoDB, Mongoose                                |
| Authentication | JWT, bcrypt                                      |
| File Upload    | Multer                                           |
| Charts         | Chart.js                                         |
| Utilities      | React Toastify, html5-qrcode, jsPDF              |

## 📸 Screenshots

Add screenshots of your application in the `images` folder and use the following examples if the filenames match your actual files.

### Landing Page

![Landing Page](images/landing-page.png)

### Login Page

![Login Page](images/login.png)

### Events Page

![Events Page](images/events.png)

### Event Details

![Event Details](images/event-details.png)

### Ticket Booking

![Ticket Booking](images/booking.png)

### QR Ticket

![QR Ticket](images/qr-ticket.png)

### Admin Dashboard

![Admin Dashboard](images/admin-dashboard.png)

### Analytics Dashboard

![Analytics Dashboard](images/analytics.png)

## 📂 Project Structure

```text
Event-Management-System/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── context/
│       ├── pages/
│       ├── services/
│       └── utils/
├── images/
└── README.md
```

## 🚀 Getting Started

### Prerequisites

* Node.js and npm
* MongoDB instance or MongoDB Atlas account
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/Dharavathu-Sowndarya/EventManagementSystem.git
cd EventManagementSystem
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the backend folder and configure the required variables:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
CLIENT_URL=http://localhost:5173
```

Start the backend using the script defined in `backend/package.json`, for example:

```bash
npm run dev
```

### 3. Frontend Setup

Open a second terminal:

```bash
cd frontend
npm install
```

Create a frontend `.env` file if required:

```env
VITE_API_URL=http://localhost:5000/api
```

Start the frontend:

```bash
npm run dev
```

Use the local URL displayed in your terminal to open the application.

**Note:** Environment variable names, scripts, and ports must match your actual project configuration. Never commit real passwords, API keys, or database credentials.

## 🔮 Future Enhancements

* Online payment gateway integration
* Email notifications
* Google authentication
* Real-time notifications

## 👩‍💻 Author

**Dharavathu Sowndarya**

GitHub: [Dharavathu-Sowndarya](https://github.com/Dharavathu-Sowndarya)

## ⭐ Support

If you find this project useful, consider giving the repository a star on GitHub.
