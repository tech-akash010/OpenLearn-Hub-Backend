<div align="center">
  <h1>⚙️ OpenLearn Hub - Backend</h1>
  <h3>The Robust API Infrastructure for OpenLearn Hub</h3>
  
  <p>
    <a href="#features">Features</a> •
    <a href="#getting-started">Getting Started</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#api-reference">API Reference</a>
  </p>

  <img src="https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-4.x-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Firebase-Admin-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Nodemailer-Email-007ACC?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Nodemailer" />
</div>

<br />

## 🌟 Overview

The **OpenLearn Hub Backend** serves as the backbone of the platform, providing secure, scalable, and real-time APIs. It leverages the power of **Node.js** and **Express**, integrated with **Firebase Admin SDK** for robust authentication and Firestore database management.

## ✨ Features

### 🔐 Secure Authentication & User Management
- **Role-Based Access Control (RBAC)**: Secure middleware to handle permissions for Students, Teachers, and Educators.
- **Firebase Auth Integration**: Seamless and secure user verification.

### 📡 RESTful API Architecture
- **Organized Routes**: Clean architecture with separate routes for users, content, and subscriptions.
- **CORS Enabled**: Configured to securely communicate with the frontend application.

### ☁️ Cloud & Database
- **Firestore Integration**: Real-time NoSQL database connectivity using `firebase-admin`.
- **Scalable Architecture**: Designed to handle growing data needs.

### 📧 Communication Services
- **Email Notifications**: Integrated **Nodemailer** for sending welcome emails, verifications, and updates.
- **Environment Management**: Secure configuration using `dotenv`.

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| **Runtime** | Node.js (>=18.0.0) |
| **Framework** | Express.js |
| **Database** | Firebase Firestore (via Admin SDK) |
| **Authentication** | Firebase Auth |
| **Email Service** | Nodemailer |
| **Environment** | Dotenv, Cors |

## 🚀 Getting Started

### Prerequisites

- **Node.js** >= 18.x
- **npm** >= 9.x

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ayon-coder/OpenLearn-Hub-Backend.git
   cd OpenLearn-Hub-Backend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory and configure your Firebase credentials and other keys:
   ```env
   PORT=5000
   # Add your Firebase Admin SDK credential path and specific keys
   GOOGLE_APPLICATION_CREDENTIALS=./config/serviceAccountKey.json
   ```

4. **Start the server**
   
   **Development Mode (with watch):**
   ```bash
   npm run dev
   ```

   **Production Start:**
   ```bash
   npm start
   ```

## 📄 API Reference

The backend exposes several key endpoints for the frontend application.

- **Auth**: `/api/auth` - User registration and login.
- **Users**: `/api/users` - User profile management.
- **Content**: `/api/content` - Upload and retrieve educational resources.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## ✍️ Authors

- **[@tech-akash010](https://github.com/tech-akash010)**
- **[@Ayon-coder](https://github.com/Ayon-coder)**

## 📄 License

Project is proprietary / open-source (check LICENSE file).
