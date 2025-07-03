# Chattu - Real-Time MERN Chat Application

Chattu is a full-stack real-time chat application built with the MERN stack (MongoDB, Express.js, React, Node.js) and Socket.IO. It supports 1-to-1 and group messaging, file sharing, notifications, friend requests, and admin management features.

---

## Features

- **Real-Time Messaging:** Instant 1-to-1 and group chat using Socket.IO.
- **Authentication:** Secure user registration and login with JWT and bcrypt.
- **Friend Requests:** Send, accept, and manage friend requests.
- **Group Chats:** Create, rename, and manage group chats and members.
- **File Sharing:** Upload and share images, videos, and files in chat (Cloudinary integration).
- **Notifications:** Real-time notifications for messages and friend requests.
- **Admin Panel:** Manage users, chats, and messages with analytics and charts.
- **Responsive UI:** Modern, mobile-friendly interface built with React and Material UI.
- **Profile Management:** View and update user profiles and avatars.
- **Search:** Search users and chats.
- **Typing Indicators:** See when others are typing.
- **Online Status:** See who is online in real time.
- **Pagination:** Efficient message loading with infinite scroll.
- **Security:** Passwords hashed, JWT authentication, and secure cookies.

---

## Tech Stack

- **Frontend:** React, Redux Toolkit, Vite, Material UI, Socket.IO Client
- **Backend:** Node.js, Express.js, Socket.IO, MongoDB, Mongoose, Cloudinary
- **Authentication:** JWT, bcrypt
- **File Uploads:** Multer, Cloudinary
- **Admin Dashboard:** Analytics with Chart.js
- **Dev Tools:** ESLint, Nodemon

---

## Folder Structure
chatapp/ │ ├── frontend/ # React client (Vite) │ ├── src/ │ ├── public/ │ ├── package.json │ └── ... │ ├── server/ # Express server │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── utils/ │ ├── app.js │ ├── package.json │ └── ... │ ├── README.md └── package.json


---

