# 🌐 SMAPP – Social Media Application

A **full-stack social media web application** built with the **MERN Stack (MongoDB, Express.js, React, Node.js)**.  
This app allows users to share posts, interact through comments, and communicate privately in real-time — all in a sleek, responsive design.

---

## 🚀 Features

### 📝 Posts & Interactions
- Create, read, update, and delete posts  
- Like and unlike posts  
- Sort posts by likes, comments, or creation date  
- Infinite scrolling for smooth feed loading  
- Search posts by title or keywords  
- View users who liked a post    

### 💬 Comments
- Nested (threaded) comments with replies  
- Markdown support for posts and comments  
- Profanity filtering and comment cooldown  
- Edit and delete comments 

### 👤 User System
- JWT-based signup and login authentication  
- View and edit profile bios  
- Display user’s posts, liked posts, and comments  
- Profile avatars and cover images (upload support)  

### 💌 Messaging
- Real-time **private chats** powered by **Socket.io**  
- Message notifications and unread message badges  
- Online/offline status indicators  

### 🧠 Additional Enhancements
- Light & dark mode toggle 🌗  
- Mobile-friendly and fully responsive UI  
- Post analytics (likes, comments, views count)  
- Follow / Unfollow users system  
- Notifications for likes, replies, and messages  
- Save or bookmark posts  
- Admin dashboard (optional)  

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| 💻 Frontend | React.js (Vite) |
| ⚙️ Backend | Node.js + Express.js |
| 🧩 Database | MongoDB (Atlas) |
| 🔐 Authentication | JWT (JSON Web Tokens) |
| 💬 Real-time | Socket.io |
| 🎨 Styling | Tailwind CSS / Custom CSS |
| ☁️ Deployment | Vercel (Frontend) & Render (Backend)

---

## 📦 Installation & Setup Guide

Follow these steps to run the project locally 👇

### 1️⃣ Clone this repository
```
git clone https://github.com/leonrock128/Social_App.git
cd Social_App
```

### 2️⃣ Install dependencies
```
npm install
cd client
npm install
```

### 3️⃣ Create an .env file in the root directory
```
cd ..
touch .env
```

### 4️⃣ Configure environment variables
Edit your .env file and add the following:
```
MONGO_URI=<YOUR_MONGO_URI>
TOKEN_KEY=<YOUR_TOKEN_KEY>
PORT=4000
```

### 5️⃣ Run the backend server
```
npm run server
```

### 6️⃣ Run the frontend (in a new terminal)
```
cd Social_App/client
npm start
```
---

### 🌐 Live Demo 

[Live Demo Click Here!](https://social-app-three-chi.vercel.app/)





