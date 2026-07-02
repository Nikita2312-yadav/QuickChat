# ⭐QuickChat – Real-Time Chat Application

## 🚀Live Demo
https://quick-chat-sand-six.vercel.app


## 📌Project Overview

QuickChat is a full-stack real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It enables users to communicate instantly using Socket.IO, with secure authentication, persistent chat history, and image sharing support.

The application is designed with a client-server architecture and deployed on Vercel.

---

## ⚡Features

- User registration and login (Email & Password)
- JWT-based authentication system
- Real-time one-to-one messaging using Socket.IO
- Persistent message storage in MongoDB
- Unread message notification badge
- Profile image upload via Cloudinary
- Responsive UI for all devices
- Secure environment variable management
- Backend deployed on Vercel

---

## 🛠️Tech Stack

**Frontend**
- React.js
- Vite
- Axios
- CSS

**Backend**
- Node.js
- Express.js
- Socket.IO
- JWT Authentication
- Mongoose

**Database**
- MongoDB Atlas

**Cloud Storage**
- Cloudinary

**Deployment**
- Vercel

---

## ⚙️Project Setup

### Clone Repository
```bash
git clone https://github.com/Nikita2312-yadav/QuickChat.git
cd QuickChat
```
## Install Dependencies

### Backend
```bash
cd server
npm install
```
### Frontend
```bash
cd client
npm install
```

## 🔐Environment Variable
Create .env files in both client and server directories.
### Server.env
```Environment

MONGODB_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```
### Client.env
```Environment
VITE_API_URL=http://localhost:5000
```

## ▶️Run the application
### Start Backend
```bash
cd server
npm run dev
```
### Start Frontend
```bash
cd client
npm run dev
```

## 🧩Design Decision
- MERN stack chosen for scalability and simplicity
- Socket.IO used for real-time messaging
- JWT ensures secure authentication and protected routes
- MongoDB used for flexible message and user storage
- Cloudinary handles image uploads efficiently
- Separation of frontend and backend for modular architecture
  
## 📦Assumptions
- Users register with a valid and unique email
- Authentication uses email & password with JWT
- MongoDB and Cloudinary are properly configured
- Backend runs before frontend
- Stable internet required for real-time messaging
- Message Storage
- All messages are stored in MongoDB with sender, receiver, content, and timestamp, ensuring chat history is persistent across sessions.
### 🔔Unread Messages
Unread message count is shown beside chats to indicate new messages that have not been opened.
## ☁️Deployment
The application is deployed on Vercel:
https://quick-chat-sand-six.vercel.app⁠�

## 🚀Future Improvements
- Group chats
- Voice & video calling
- File sharing
  
## 👩‍💻Author
Nikita Yadav
GitHub: https://github.com/Nikita2312-yadav⁠�





