# 📱 We-Chat — Real-Time Chat App (MERN + Socket.io)

We-Chat is a fully functional real-time chat application inspired by WhatsApp, built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.io for real-time communication.

🔗 Live Demo: https://we-chat-seven.vercel.app/  
📦 GitHub Repository: https://github.com/ethyne2666/We-Chat.git  

✨ Contributions are welcome!

---

## 🚀 Features

- User Authentication (Sign Up / Login)
- Real-Time One-to-One Messaging using Socket.io
- Online / Offline User Presence
- Persistent Chat History with MongoDB
- Image Sharing in Chats
- User Profile Picture and Bio
- Right Sidebar showing user details and shared media
- Logout functionality
- Fully Responsive WhatsApp-like UI
- Deployed on Vercel

---

## 🧠 Tech Stack

Frontend:
- React.js
- Context API
- Tailwind CSS
- Socket.io Client

Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JWT Authentication

---

## 📁 Project Structure

We-Chat/
├── client/                  # React Frontend  
├── server/                  # Node + Express Backend  
├── README.md  
├── package.json  

---

## ⚙️ Getting Started (Local Setup)

### Prerequisites

- Node.js (v14+)
- npm or yarn
- MongoDB (Local or Atlas)

---

## 📥 Clone the Repository

git clone https://github.com/ethyne2666/We-Chat.git  
cd We-Chat  

---

## 🛠 Backend Setup

cd server  
npm install  

Create a .env file inside the server folder:

PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret_key  

Start the backend server:

npm run dev  

---

## ⚛️ Frontend Setup

cd ../client  
npm install  

Create a .env file inside the client folder (if required):

REACT_APP_BASE_URL=http://localhost:5000  

Start the frontend:

npm start  

---

## 🌐 Live Deployment

The application is deployed on Vercel:

https://we-chat-seven.vercel.app/

Make sure backend API URLs are correctly set in production environment variables.

---

## 🤝 Contributing

Contributions are always welcome!

To contribute:
- Star the repository
- Fork the project
- Create a new branch
- Commit your changes
- Push to your fork
- Open a Pull Request

Please follow clean code practices and meaningful commit messages.

---

## 📌 Future Improvements

- Group Chats
- Message Reactions
- Read Receipts
- Emoji Support
- Chat Search
- Push Notifications
- Dark / Light Theme Toggle

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

Inspired by modern chat applications and open-source MERN + Socket.io projects.

---

Happy Coding 🚀💬


