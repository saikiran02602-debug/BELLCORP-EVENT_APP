
# BELLCORP-EVENT_APP
# Bellcorp Event Management Application

## 1. Project Objective
A full-stack MERN application for users to discover, view, and manage event registrations. Built with dynamic data fetching and JWT authentication.

## 2. Tech Stack
- **Frontend**: React.js (Hooks, Context API).
- **Backend**: Node.js & Express.js.
- **Database**: MongoDB Atlas.
- **Authentication**: JSON Web Tokens (JWT) & Bcryptjs.

## 3. Features
- User Authentication (Signup/Login).
- Event Discovery: Search by text and filter by category/location.
- Real-time Availability: Check seat capacity before registration.
- Dashboard: View upcoming and past registered events.

## 4. How to Run Locally

### Prerequisites
- Node.js installed
- MongoDB connection string

### Steps
1. **Clone the repository**
2. **Setup Backend**:
   - Go to `server` folder: `cd server`
   - Install dependencies: `npm install`
   - Create a `.env` file with `MONGO_URI`, `JWT_SECRET`, and `PORT`.
   - Start server: `npm start`
3. **Setup Frontend**:
   - Go to `client` folder: `cd client`
   - Install dependencies: `npm install`
   - Start React app: `npm start`

## 5. Database Schema
- **User**: Name, Email, Password.
- **Event**: Name, Organizer, Location, Date, Capacity, Category.
- **Registration**: Links UserID and EventID.

 ## 6.Video Link:
 https://drive.google.com/file/d/15p-0a81M5laf-W1R76oYafEtoU8qo8iY/view?usp=drive_link


