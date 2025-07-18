# 🛵 2Wheleeee – Peer-to-Peer Bike Rental Marketplace

A full-stack bike rental platform where users can book bikes listed by hosts, complete with secure payments, document verification, and real-time communication.

## 🚀 Features

- 🔐 **Role-Based Authentication** using JWT (Admin, Host, User)
- 📸 **Cloudinary Integration** for host document & bike uploads
- ✅ **Admin Verification** for listed bikes
- 💬 **Real-Time Chat** between host and user (Socket.IO)
- 💳 **Razorpay Payment Gateway** integration
- 📍 **Geoapify Location Autofill** for intuitive booking
- 🌐 **Responsive UI** built with Tailwind CSS

## 🧱 Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB
- **Authentication:** JWT
- **Payments:** Razorpay
- **Maps & Location:** Geoapify
- **Chat:** Socket.IO
- **File Uploads:** Cloudinary

## 🛠️ Setup Instructions

### Prerequisites

- Node.js and npm installed
- MongoDB Atlas or local URI
- Razorpay API keys
- Cloudinary credentials
- Geoapify API key

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/2wheleeee.git
cd 2wheleeee

### 2. Setup Backend
```bash
cd backend
npm install
# Create a .env file as per the example below
npm run dev
