# UniStay — University Hostel Management System (MERN)

UniStay is a full-stack **University Hostel Management System** developed using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The system enables students to explore university hostels, check room availability, and book hostel rooms online through an intuitive interface. The backend provides RESTful APIs while MongoDB stores hostel, room, student, and booking information.

---

# Features

## Student Side

- Browse available hostels
- Search hostels by name
- Filter hostels by:
  - Rent Range
  - Room Availability
  - Room Type (Single / Double / Triple)
- View complete hostel details
- View hostel facilities and infrastructure
- View warden information
- Interactive room availability grid
- Book available hostel rooms
- Booking summary with rent and security deposit
- View personal bookings using Student ID
- Cancel bookings with automatic room availability updates

---

## ⚙️ Backend Features

- RESTful API architecture
- MongoDB database integration using Mongoose
- Hostel management APIs
- Booking management APIs
- Student booking records
- Database seeding script for sample data
- CORS support
- Morgan request logging

---

# Tech Stack

## Frontend

- React.js
- Vite
- Axios
- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Morgan
- CORS

---

# Project Structure

```
UniStay/
│
├── client/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── services/
│       ├── App.jsx
│       ├── main.jsx
│       └── index.css
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── seed/
│   ├── app.js
│   └── server.js
│
├── README.md
└── package.json
```

---

# Database Collections

- Hostels
- Rooms
- Students
- Bookings

---

# Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/UniStay.git
cd UniStay
```

---

## 2. Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd server
npm install
```

---

## 3. Configure Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

---

## 4. Seed the Database (Optional)

```bash
npm run seed
```

---

## 5. Start the Backend

```bash
npm run dev
```

---

## 6. Start the Frontend

```bash
npm run dev
```

---

# 📡 API Endpoints

## Hostels

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/hostels` | Get all hostels |
| GET | `/api/hostels/:id` | Get hostel details |

---

## Bookings

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/bookings` | Create booking |
| GET | `/api/bookings/:studentId` | Get student bookings |
| DELETE | `/api/bookings/:id` | Cancel booking |

---

# Key Functionalities

- Hostel Search
- Advanced Filtering
- Room Availability Tracking
- Online Hostel Booking
- Booking Cancellation
- Dynamic Room Status Updates
- Responsive User Interface
- REST API Integration

---

# Future Improvements

- Student Authentication (JWT)
- Admin Dashboard
- Hostel Management
- Payment Gateway Integration
- Email Notifications
- Booking History
- Student Profile Management
- Image Uploads for Hostels
- Role-based Authorization

---

# Author

**SM Developer**

BS Computer Science Student

---

# License

This project is developed for learning and academic purposes.
