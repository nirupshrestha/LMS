📚 LMS

LMS is a modern Learning Management System (LMS) built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to browse courses, purchase them via PayPal, and track their learning progress.

🌟 Features

User Registration & Authentication

Secure email verification using Nodemailer.

Password hashing for security.

Course Management

View all courses without login.

Course details page with content preview.

Purchasing & Payments

Users can purchase courses via PayPal integration.

Tracks purchased courses per user.

Student Dashboard

Track course progress.

Access purchased courses anytime.

Media & Storage

All course materials and uploads are stored securely on Cloudinary.

Responsive Design

Works on desktop and mobile devices.

🛠️ Technology Stack

Frontend: React.js, Vite

Backend: Node.js, Express.js

Database: MongoDB

File Storage: Cloudinary

Authentication & Email: Nodemailer

Payment Integration: PayPal API

⚡ Installation & Setup

Clone the repository

git clone https://github.com/nirupshrestha/finalbosslms.git
cd finalbosslms


Install backend dependencies

cd server
npm install


Install frontend dependencies

cd ../client
npm install


Create a .env file in the backend folder with your credentials:

MONGODB_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_client_secret


Run the application

# Backend
cd server
npm run dev

# Frontend
cd client
npm run dev


Open http://localhost:5173 to access the LMS.

🎯 Usage

Browse courses as a guest.

Sign up and verify your email.

Purchase courses securely using PayPal.

Track your learning progress in the dashboard.

📁 Folder Structure
finalbosslms/
├─ client/        # React frontend
├─ server/        # Node/Express backend
├─ server/uploads # (local uploads, optional)
├─ README.md
└─ package.json

💻 Deployment

Can be deployed on Vercel (frontend) and Render/Heroku (backend).

Ensure all environment variables are set in production.

Uploaded files automatically stored on Cloudinary.

📧 Contact

Developer: Nirup Shrestha

GitHub: https://github.com/nirupshrestha

⭐ Notes

This LMS is built as a full-stack project for educational purposes.

For production, ensure you secure your environment variables and payment credentials.
