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

```bash
git clone https://github.com/AmbikaDhakar/Annapurna.git
cd annapurna-hub


