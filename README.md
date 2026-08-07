# 💬 Full Stack Real-Time Chat Application

<p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js" />
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb" />
  <img src="https://img.shields.io/badge/Socket.IO-Realtime-010101?style=for-the-badge&logo=socket.io" />
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker" />
</p>

<p align="center">
A modern <b>Real-Time Chat Application</b> built using the MERN stack with <b>Socket.IO</b> for instant messaging, <b>JWT Authentication</b>, and <b>Docker</b> for seamless deployment.
</p>

---

# 📖 Overview

This project is a scalable and secure real-time chat application designed with modern web technologies.

It provides users with an interactive messaging experience featuring instant communication, authentication, profile management, and online user tracking.

The application is fully containerized with Docker, making local development and deployment straightforward.

---

# 🚀 Features

- 💬 Real-time messaging with Socket.IO
- 🔐 JWT Authentication & Authorization
- 👤 User Registration & Login
- 🟢 Real-time Online/Offline Status
- 📷 Profile Picture Upload
- 🎨 Responsive UI using React + TailwindCSS + DaisyUI
- ⚡ Zustand for Global State Management
- 📦 Dockerized Development Environment
- 🛡️ Secure Backend Architecture
- 📈 Designed for Scalability

---

# 🏗️ System Architecture

```
                +----------------------+
                |    React Frontend    |
                +----------+-----------+
                           |
          HTTP APIs + WebSocket (Socket.IO)
                           |
                           ▼
          +-------------------------------+
          |  Node.js + Express Backend     |
          | Authentication (JWT)           |
          | REST APIs                      |
          | Socket.IO Server               |
          +---------------+---------------+
                          |
                          |
                    MongoDB Database
```

---

# ⚙️ Workflow

### 👤 User Interaction

Users interact with the React application through their browser.

They can:

- Register/Login
- Send messages
- Receive messages instantly
- Update profile
- View online users

---

### 🌐 Frontend (React)

Responsible for:

- Rendering the UI
- Managing application state
- Sending API requests
- Maintaining Socket.IO connection

Communicates using:

- REST APIs
- WebSockets

---

### 🚀 Backend (Node.js + Express)

Responsible for:

- Authentication
- Authorization
- User Management
- Message Storage
- Real-time Events
- Socket.IO Communication

---

### 🍃 MongoDB

Stores:

- Users
- Messages
- User Profiles
- Authentication Data

---

# 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Frontend | React |
| Styling | TailwindCSS + DaisyUI |
| Backend | Node.js + Express |
| Database | MongoDB |
| Real-Time | Socket.IO |
| Authentication | JWT |
| State Management | Zustand |
| Containerization | Docker |
| Reverse Proxy | Nginx |
| Orchestration | Kubernetes *(Planned)* |

---

# 📋 Prerequisites

Make sure you have installed:

- Node.js (v14+)
- Docker
- Docker Compose
- Git

---

# 📂 Clone Repository

```bash
git clone https://github.com/iemafzalhassan/full-stack_chatApp.git

cd full-stack_chatApp
```

---

# 🔑 Environment Variables

Navigate to the backend folder.

```bash
cd backend
```

Create a `.env` file.

```env
MONGODB_URI=mongodb://mongoadmin:secret@mongodb:27017/dbname?authSource=admin

JWT_SECRET=your_super_secret_key

PORT=5001
```

> Replace `JWT_SECRET` with a strong secret key.

---

# 🐳 Quick Start (Recommended)

Build everything with Docker Compose.

```bash
docker-compose up -d --build
```

Application will be available at

```
http://localhost
```

---

# 🐳 Manual Docker Setup

## 1. Create Docker Network

```bash
docker network create full-stack
```

---

## 2. Start MongoDB

```bash
docker run -d \
-p 27017:27017 \
--name mongo \
mongo:latest
```

---

## 3. Build Frontend

```bash
cd frontend

docker build -t full-stack_frontend .
```

Run Frontend

```bash
docker run -d \
--network=full-stack \
-p 5173:5173 \
--name frontend \
full-stack_frontend
```

Frontend

```
http://localhost:5173
```

---

## 4. Build Backend

```bash
cd backend

docker build -t full-stack_backend .
```

Run Backend

```bash
docker run -d \
--network=full-stack \
--add-host=host.docker.internal:host-gateway \
-p 5001:5001 \
--env-file .env \
full-stack_backend
```

Backend API

```
http://localhost:5001
```

---

# 📊 Verify Containers

```bash
docker ps
```

View logs

```bash
docker-compose logs -f
```

---

# 📸 Screenshots

> Add your project screenshots here.

```
📁 screenshots/

login.png

chat.png

profile.png
```

Example

```markdown
![Login](screenshots/login.png)

![Chat](screenshots/chat.png)

![Profile](screenshots/profile.png)
```

---

# 📁 Project Structure

```
full-stack_chatApp
│
├── backend
│   ├── controllers
│   ├── middleware
│   ├── routes
│   ├── socket
│   └── server.js
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── store
│
├── docker-compose.yml
├── nginx
└── README.md
```

---

# 🤝 Contributing

Contributions are always welcome!

### You can contribute by:

- 🐞 Reporting Bugs
- ✨ Suggesting Features
- 🔧 Improving Documentation
- 🚀 Opening Pull Requests

Steps:

```bash
Fork Repository

Create Branch

Commit Changes

Push Branch

Open Pull Request
```

---

# 🌟 Support

If you like this project, please consider giving it a ⭐

It helps others discover the project and motivates further development.

---

# 🔮 Roadmap

- [ ] Kubernetes Deployment
- [ ] CI/CD Pipeline (GitHub Actions)
- [ ] Group Chat
- [ ] Media Sharing
- [ ] Voice Messages
- [ ] Message Reactions
- [ ] Read Receipts
- [ ] Push Notifications
- [ ] Cloud Deployment (AWS/GCP/Azure)

---

# 👨‍💻 Author

**Afzal Hassan**

GitHub

https://github.com/iemafzalhassan

---

<p align="center">
Made with ❤️ using React, Node.js, MongoDB, Socket.IO & Docker
</p>
