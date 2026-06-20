# Real-Time Collaborative Document Editor

*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ANSH SHARMA
*INTERN ID*:CTIS6655
*DOMAIN*: FULL STACK WEB DEVELOPMENT
*DURATION*: 16 WEEKS
*MENTOR*: NEELA SANTOSH

*OUTPUT*:

![image align](https://github.com/ANSH-SHARMA912/REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR/blob/68c3f4de160aff2da85de6fd569a1d5a25cad44f/Screenshot%202026-06-20%20155627.png)

A **Real-Time Collaborative Document Editor** built using **React.js**, **Node.js**, **WebSockets (Socket.IO)**, and **MongoDB**, allowing multiple users to edit documents simultaneously with instant synchronization.

---

## Overview

The Real-Time Collaborative Document Editor enables multiple users to create, edit, and collaborate on documents in real time. Every change made by one user is instantly reflected across all connected clients using WebSockets, ensuring a seamless collaborative experience.

The application features a modern React-based frontend, a Node.js backend for handling real-time communication, and MongoDB for securely storing document data.

---

## Features

*  Real-time collaborative document editing
*  Multiple users can edit the same document simultaneously
*  Instant synchronization using WebSockets (Socket.IO)
*  Automatic document saving to MongoDB
*  Live updates without refreshing the page
*  Responsive and user-friendly interface built with React.js
*  Reliable backend for handling concurrent connections

---

## Technologies Used

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js
* Socket.IO

### Database

* MongoDB
* Mongoose

---

## Dependencies

### Frontend

* react
* react-dom
* axios
* socket.io-client

### Backend

* express
* socket.io
* mongoose
* cors
* dotenv
* nodemon

---

## Project Structure

```
Real-Time-Collaborative-Editor/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── server.js
│   └── package.json
│
├── README.md
└── .env
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Real-Time-Collaborative-Editor.git
cd Real-Time-Collaborative-Editor
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../client
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the **server** folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 5. Start the Backend

```bash
cd server
npm run dev
```

### 6. Start the Frontend

```bash
cd client
npm start
```

### 7. Open the Application

Navigate to:

```
http://localhost:3000
```

Open the application in multiple browser windows or devices to test real-time collaboration.

---

## How It Works

1. Users open the collaborative editor.
2. The frontend establishes a WebSocket connection with the Node.js server.
3. When a user edits the document, the changes are immediately transmitted through Socket.IO.
4. The server broadcasts the updates to all connected users.
5. MongoDB stores the latest version of the document for persistence.
6. Every connected client receives updates instantly without requiring a page refresh.

---

## Future Enhancements

* User authentication and authorization
* Document sharing via unique links
* Rich text formatting
* Version history and document recovery
* Presence indicators (online users)
* Cursor tracking
* Commenting and suggestions
* File export (PDF, DOCX)

---

## Learning Outcomes

This project demonstrates:

* Real-time communication using WebSockets
* Full-stack application development with the MERN stack
* React component architecture
* Backend API development using Express.js
* MongoDB database integration
* State synchronization across multiple clients

