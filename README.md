# 🌱 Annapurna Hub - Smart Food Donation & Distribution System 

**Annapurna Hub** is a community-driven food donation platform that connects restaurants and individual donors with NGOs, helping reduce food waste and feed people in need.

---

## 🚀 Features

### 🔐 User Management

- Role-based login system (`Donor`, `NGO`)
- Secure authentication using Passport.js
- Session-based login with auto redirection after login
- User registration, login, and logout

### 🍲 Food Donation System

- Donors can:
  - Fill donation forms with food type, quantity, pickup address, etc.
  - View past donation history in their dashboard
- NGOs can:
  - View available food donations
  - Filter by location and status
  - Accept and manage donations
  - See estimated number of people fed

### 🧑‍💻 Dashboards

- **Donor Dashboard**: Lists all food donations by the logged-in donor
- **NGO Dashboard**:
  - Filter donations by status and pickup address
  - Paginated view of food donations
  - Option to accept donations

### 🛠️ Tech Stack
- Node.js, Express.js
- MongoDB & Mongoose
- Passport.js (authentication)
- EJS (templating engine)
- Tailwind CSS (front-end styling)

---

## 🏗️ Project Setup

### 1. Clone the Repository


git clone https://github.com/AmbikaDhakar/Annapurna.git
cd annapurna-hub

### 2. Install Dependencies

npm install / npm i

### 3. Configure Environment Variables

MONGODB_URI_LOCAL=mongodb://localhost:27017/annapurnaDB
MONGODB_URI_REMOTE=your_remote_mongodb_uri
SESSION_SECRET=your_session_secret
NODE_ENV=development

### 4. Run Locally

npm start

The app will run on http://localhost:3000

## 📁 Folder Structure
.
├── views/            # EJS templates for pages
├── public/           # Static assets (CSS, images)
├── app.js            # Main application logic
├── .env              # Environment variables
└── README.md         # Documentation

## 🌍 How It Works

- Donors and NGOs register and login to the platform.
- Donors fill food donation forms.
- NGOs browse available donations and accept them.
- The system updates donation status and assigns the accepting NGO.
- Dashboards provide tracking of all donations and statuses.



