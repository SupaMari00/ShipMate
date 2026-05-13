# ShipMate 🚚📦

ShipMate is a full-stack shipment tracking and logistics management web application built with React, Node.js, Express, and SQL. It allows users to create shipments, track delivery statuses in real time, manage orders, and view shipment history through a modern responsive dashboard.

---

## Features

* User authentication
* Create and manage shipments
* Real-time shipment tracking
* Order management
* Tracking history updates
* REST API integration
* Responsive modern UI

---

## Tech Stack

### Frontend

* React
* Axios
* Bootstrap / CSS

### Backend

* Node.js
* Express.js

### Database

* SQL / SQLite

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/shipmate.git
cd shipmate
```

### Install frontend dependencies

```bash
cd frontend
npm install
```

### Install backend dependencies

```bash
cd backend
npm install
```

---

## Run the Application

### Start backend server

```bash
npm start
```

### Start frontend

```bash
npm run dev
```

---

## API Endpoints

| Method | Endpoint       | Description        |
| ------ | -------------- | ------------------ |
| GET    | /shipments     | Get all shipments  |
| GET    | /shipments/:id | Get shipment by ID |
| POST   | /shipments     | Create shipment    |
| PUT    | /shipments/:id | Update shipment    |
| DELETE | /shipments/:id | Delete shipment    |

---

## Project Structure

```bash
ShipMate/
│
├── frontend/
├── backend/
├── routes/
├── controllers/
├── database/
└── README.md
```

---

## Future Improvements

* Admin dashboard
* Live map tracking
* Email notifications
* Payment integration
* Role-based authentication

---

## Author

Built by Peter Jacob.
