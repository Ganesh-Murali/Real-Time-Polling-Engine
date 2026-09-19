# ⚡ Real-Time Polling Engine

A full-stack real-time polling application that allows users to create polls, share them instantly, vote live, and view results without refreshing the page.

Built using React, Node.js, MongoDB, Express, and Socket.IO for real-time communication.

---

## 🚀 Live Demo

https://real-time-polling-engine-navy.vercel.app/

---

## 📌 Features

### Poll Management
- Create polls with multiple options
- Share polls using a unique link
- Open and close polls manually
- Delete closed polls
- View recently created polls

### Real-Time Voting
- Live vote updates using Socket.IO
- No page refresh required
- All connected users receive instant updates

### Voting Security
- One vote per user/IP
- Duplicate vote prevention
- Input validation on both frontend and backend

### Poll Analytics
- Live vote count
- Vote percentage calculation
- Progress bar visualization
- Leading option display
- Total vote statistics

### Auto Poll Expiry
- Configure poll duration during creation
- Options include:
  - 5 Minutes
  - 30 Minutes
  - 1 Hour
  - 1 Day
- Polls automatically close after expiry time

### User Experience
- Responsive interface
- Loading spinner for API requests
- Clean dashboard view
- Shareable poll links
- Poll status indicators

---

## 🛠 Tech Stack

### Frontend

- React.js
- React Router DOM
- Axios
- Socket.IO Client
- CSS

### Backend

- Node.js
- Express.js
- Socket.IO
- MongoDB
- Mongoose

### Deployment

- Vercel (Frontend)
- Render (Backend)
- MongoDB Atlas (Database)

---

## 📂 Project Structure

```text
Real-Time-Polling-Engine
│
├── client
│   ├── src
│   │   ├── components
│   │   │   ├── Header.jsx
│   │   │   └── Loader.jsx
│   │   │
│   │   ├── pages
│   │   │   ├── CreatePoll.jsx
│   │   │   └── PollPage.jsx
│   │   │
│   │   ├── services
│   │   │   └── api.js
│   │   │
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server
│   ├── Controllers
│   │   └── pollController.js
│   │
│   ├── models
│   │   ├── Poll.js
│   │   └── Vote.js
│   │
│   ├── routes
│   │   └── pollRoutes.js
│   │
│   ├── db.js
│   └── server.js
│
└── README.md
```

