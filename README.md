# Event Management System

A full-stack web application for managing event bookings, users, employees, and administrative tasks. Built with React, Node.js, Express, and MongoDB.

## Features

- **User Registration & Login:** Secure authentication for users and employees.
- **Event Booking:** Book weddings, birthdays, corporate, and social events.
- **Role-Based Dashboards:** Separate dashboards for users, employees, and admins.
- **Admin Controls:** Manage users, employees, bookings, logs, and view statistics.
- **Employee Management:** Employees can view/edit profiles and assigned bookings.
- **Payment Integration:** Razorpay integration for secure online payments.
- **Logging & Monitoring:** Backend logs all requests and actions.
- **API Documentation:** Swagger UI available at `/api-docs`.
- **Testing & CI/CD:** Automated tests and builds using Jest, Docker, and GitHub Actions.

## Tech Stack

- **Frontend:** React, Redux, Chart.js, FontAwesome, CSS
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Authentication:** Session-based, role-based access control
- **DevOps:** Docker, GitHub Actions
- **Testing:** Jest

## Getting Started

### Prerequisites

- Node.js (v20 recommended)
- npm
- MongoDB
- Docker (optional, for containerization)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/charanmannem/Event-Management.git
   cd Event-Management
   ```

2. **Install dependencies:**
   ```bash
   npm install
   cd frontend && npm install
   cd ../backend && npm install
   ```

3. **Set up environment variables:**
   - Copy `.env.example` to `.env` in the root, `frontend/`, and `backend/` folders.
   - Update values as needed (MongoDB URI, API URLs, etc.).

4. **Start MongoDB:**  
   Make sure MongoDB is running locally or update the connection string for a remote database.

5. **Run the application:**
   - **Frontend:**  
     ```bash
     cd frontend
     npm start
     ```
   - **Backend:**  
     ```bash
     cd backend
     node server.js
     ```

   Or use Docker Compose:
   ```bash
   docker-compose up --build
   ```

## Running Tests

- **Frontend:**  
  ```bash
  cd frontend
  npm test
  ```
- **Backend:**  
  ```bash
  cd backend
  npm test
  ```
