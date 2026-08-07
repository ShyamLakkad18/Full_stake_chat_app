# 💬 Real-Time Chat Application

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00BFFF&center=true&vCenter=true&width=750&lines=Full+Stack+Real-Time+Chat+Application;MERN+Stack+%7C+Socket.IO+%7C+Docker;Secure+%7C+Scalable+%7C+Production+Ready">

</p>


<p align="center">

<img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react">

<img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge&logo=node.js">

<img src="https://img.shields.io/badge/Database-MongoDB-darkgreen?style=for-the-badge&logo=mongodb">

<img src="https://img.shields.io/badge/Realtime-Socket.IO-black?style=for-the-badge&logo=socket.io">

<img src="https://img.shields.io/badge/Deployment-Docker-blue?style=for-the-badge&logo=docker">

</p>


---

# 📌 Project Overview

A full-stack **real-time messaging application** built with modern web technologies.

The main goal of this project is to create a secure, scalable and responsive chat platform where users can communicate instantly using WebSocket technology.

The application follows a client-server architecture with separate frontend, backend and database layers.


---

# 🏗️ System Architecture


```
                    USER

                     |
                     |
              React Frontend
                     |
          -----------------------
          |                     |
       REST API             Socket.IO
          |                     |
          |                     |
          -------- Backend --------
                   |
            Node.js + Express
                   |
          ----------------
          |
       MongoDB Database

```


---

# 🔄 Application Workflow


## 1. User Interaction

Users interact with the React application through the browser.

Main operations:

- User registration/login
- Sending messages
- Receiving messages instantly
- Updating profile
- Checking online status


---

## 2. Frontend Layer (React)


Responsibilities:

- User interface rendering
- Managing client state
- Handling API requests
- Maintaining WebSocket connection
- Real-time UI updates


Technologies:

- React
- TailwindCSS
- DaisyUI
- Zustand


---

## 3. Backend Layer (Node.js + Express)


Responsibilities:

- Authentication & Authorization
- User management
- Message handling
- API development
- Socket.IO event management


Security:

- JWT based authentication
- Protected routes
- Secure API communication


---

## 4. Database Layer (MongoDB)


MongoDB stores:

- User information
- Profile data
- Chat messages
- Application records


---

# ✨ Features


## 💬 Real-Time Messaging

- Instant message delivery
- WebSocket based communication
- Multiple user support
- Live chat updates


## 🔐 Authentication

- User signup/login
- JWT authentication
- Secure sessions
- Protected resources


## 👤 Profile Management

- Update profile information
- Upload profile picture
- Manage user data


## 🟢 Online Presence

- Real-time online/offline status
- Active user tracking


## 🐳 Containerized Deployment

- Docker based setup
- Easy local deployment
- Environment based configuration


---

# 🛠️ Tech Stack


## Frontend

| Technology | Purpose |
|-|-|
| React | User Interface |
| TailwindCSS | Styling |
| DaisyUI | Components |
| Zustand | State Management |


## Backend

| Technology | Purpose |
|-|-|
| Node.js | Runtime |
| Express.js | API Server |
| Socket.IO | Real-time Communication |
| JWT | Authentication |


## Database & DevOps

| Technology | Purpose |
|-|-|
| MongoDB | Database |
| Docker | Containerization |
| Nginx | Web Server |
| Kubernetes | Future Deployment |


---

# 📂 Project Structure


```
full-stack_chatApp

│
├── frontend
│
│   ├── components
│   ├── pages
│   ├── store
│   └── App.jsx
│
│
├── backend
│
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── socket
│   └── server.js
│
│
├── docker-compose.yml
│
└── README.md

```


---

# ⚙️ Installation & Setup


## Clone Repository


```bash
git clone https://github.com/iemafzalhassan/full-stack_chatApp.git

cd full-stack_chatApp
```


---

# 🔑 Environment Variables


Inside backend folder create:

```
.env
```


Add:

```env
MONGODB_URI=mongodb://mongoadmin:secret@mongodb:27017/dbname?authSource=admin

JWT_SECRET=your_secret_key

PORT=5001
```


---

# 🐳 Run Using Docker


Build and start containers:


```bash
docker-compose up -d --build
```


Application:

```
Frontend:
http://localhost


Backend API:
http://localhost:5001

```


---

# 🔍 Checking Logs


```bash
docker-compose logs -f
```


---

# 🚀 Future Improvements


- [ ] Kubernetes Deployment
- [ ] CI/CD Pipeline
- [ ] Cloud Deployment
- [ ] Group Chat
- [ ] Media Sharing
- [ ] Voice Messages
- [ ] Message Reactions
- [ ] Push Notifications


---

# 🤝 Contribution


Contributions are welcome.

Steps:

1. Fork this repository
2. Create a new branch
3. Make your changes
4. Create a Pull Request


---

# 👨‍💻 Developer


**Afzal Hassan**

Full Stack Developer


GitHub:
https://github.com/iemafzalhassan


---

# ⭐ Support


If you find this project useful, consider giving it a star ⭐


<p align="center">

<b>
Built with React ❤️ Node.js ❤️ MongoDB ❤️ Socket.IO
</b>

</p>
