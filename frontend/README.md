# 🚀 Real-Time MERN Chat Application 💬

Welcome to **Chattu** — a modern, full-featured real-time chat app built with the MERN stack and Socket.IO!  
Connect, chat, share, and manage conversations with friends and groups — all in real time, with a beautiful and responsive UI.

---

## ✨ Features

- ⚡ **Real-Time Messaging:** Instant 1-to-1 and group chat with Socket.IO.
- 🔒 **Authentication:** Secure sign up & login with JWT and bcrypt.
- 🤝 **Friend Requests:** Send, accept, and manage friend requests.
- 👥 **Group Chats:** Create, rename, and manage group chats and members.
- 📎 **File Sharing:** Upload and share images, videos, and files (Cloudinary integration).
- 🔔 **Notifications:** Real-time alerts for messages and friend requests.
- 🛡️ **Admin Panel:** Manage users, chats, and analytics with charts.
- 📱 **Responsive UI:** Mobile-friendly, modern interface (React + Material UI).
- 🖼️ **Profile Management:** Update your profile and avatar.
- 🔍 **Search:** Find users and chats instantly.
- ✍️ **Typing Indicators:** See when others are typing.
- 🟢 **Online Status:** Know who's online in real time.
- ⏬ **Pagination:** Smooth, infinite scroll for messages.
- 🛡️ **Security:** Hashed passwords, JWT auth, secure cookies.

---

## 🛠️ Tech Stack

- **Frontend:** React ⚛️, Redux Toolkit, Vite, Material UI, Socket.IO Client
- **Backend:** Node.js, Express.js, Socket.IO, MongoDB, Mongoose, Cloudinary
- **Authentication:** JWT, bcrypt
- **File Uploads:** Multer, Cloudinary
- **Admin Dashboard:** Chart.js
- **Dev Tools:** ESLint, Nodemon

---

## 📁 Folder Structure
chatapp/ │ ├── frontend/ # React client (Vite) │ ├── src/ │ ├── public/ │ ├── package.json │ └── ... │ ├── server/ # Express server │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── utils/ │ ├── app.js │ ├── package.json │ └── ... │ ├── README.md └── package.json


---

## 🚦 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishal-kadalagi/Real-Time-MERN-Chat-Application.git
cd Real-Time-MERN-Chat-Application
2️⃣ Setup the Server
cd server
npm install
Copy .sampleEnv to .env and fill in your MongoDB, JWT, Cloudinary, and other secrets.
3️⃣ Setup the Frontend
cd ../frontend
npm install
Create a .env file and set VITE_SERVER=http://localhost:3000
4️⃣ Run the Application
▶️ Start the Server
cd ../server
npm run dev
cd ../server
npm run dev
▶️ Start the Frontend

cd ../frontend
npm run dev
Frontend: http://localhost:5173
Backend: http://localhost:3000

🔑 Environment Variables
Server (server/.env)
MONGO_URI=mongodb://localhost:27017
JWT_SECRET=your_jwt_secret
ADMIN_SECRET_KEY=your_admin_secret
NODE_ENV=DEVELOPMENT
CLIENT_URL=http://localhost:5173
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloud_api_key
CLOUDINARY_API_SECRET=your_cloud_api_secret

Frontend (frontend/.env)
VITE_SERVER=http://localhost:3000

📝 Scripts
Server
npm run dev — Start server with nodemon
npm start — Start server
Frontend
npm run dev — Start React app (Vite)
npm run build — Build for production
npm run preview — Preview production build

📜 License
This project is licensed under the ISC License.

🙏 Credits
Inspired by vishal-kadalagi/Real-Time-MERN-Chat-Application
Built with ❤️ using MERN stack & Socket.IO
Happy Chatting! 🚀 ``````
