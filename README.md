# 💬 Real-Time Chat Application

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00BFFF&center=true&vCenter=true&width=750&lines=Full+Stack+Real-Time+Chat+Application;MERN+Stack+%7C+Socket.IO+%7C+Kubernetes;Secure+%7C+Scalable+%7C+Production+Ready;Automated+CI%2FCD+with+Jenkins">

</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00BFFF,100:0066FF&height=120&section=header&text=Real-Time%20Chat%20Application&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>
</p>

<p align="center">

<img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react">
<img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge&logo=node.js">
<img src="https://img.shields.io/badge/Database-MongoDB-darkgreen?style=for-the-badge&logo=mongodb">
<img src="https://img.shields.io/badge/Realtime-Socket.IO-black?style=for-the-badge&logo=socket.io">
<img src="https://img.shields.io/badge/Kubernetes-Deployment-326CE5?style=for-the-badge&logo=kubernetes">
<img src="https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins">

</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,tailwind,nodejs,express,mongodb,socketio,docker,kubernetes,jenkins,nginx,git,github&perline=6" />
</p>

---

# 🚀 Project Highlights

<p align="center">

|    ⚡ Real-Time    |     🔐 Secure    |     ☸️ Scalable     |   🔄 Automated   |
| :---------------: | :--------------: | :-----------------: | :--------------: |
|     Socket.IO     |     JWT Auth     |      Kubernetes     |   Jenkins CI/CD  |
| Instant Messaging | Protected Routes |    Containerized    | Automated Deploy |
|  Online Presence  |    Secure APIs   | Kubernetes Services |  Rolling Updates |

</p>

---

# 🔄 CI/CD Pipeline

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=2"/>
</p>

```text
                     ┌───────────────────┐
                     │   👨‍💻 Developer    │
                     └─────────┬─────────┘
                               │
                            git push
                               │
                               ▼
                     ┌───────────────────┐
                     │   🐙 GitHub Repo  │
                     └─────────┬─────────┘
                               │
                               ▼
                     ┌───────────────────┐
                     │   🔴 Jenkins      │
                     │    CI/CD         │
                     └─────────┬─────────┘
                               │
                ┌──────────────┼──────────────┐
                │              │              │
                ▼              ▼              ▼
           📥 Checkout      📦 Build       🧪 Test
                │              │              │
                └──────────────┼──────────────┘
                               │
                               ▼
                     🐳 Docker Image Build
                               │
                               ▼
                     📦 Container Registry
                               │
                               ▼
                     ☸️ Kubernetes Cluster
                               │
                 ┌─────────────┴─────────────┐
                 │                           │
                 ▼                           ▼
          ⚛️ Frontend Pods              🟢 Backend Pods
                 │                           │
                 └─────────────┬─────────────┘
                               │
                               ▼
                         🌐 Live App
```

---

# ☸️ Kubernetes Architecture

<p align="center">

```text
                         🌐 USER
                           │
                           ▼
                    ┌──────────────┐
                    │   Ingress    │
                    └──────┬───────┘
                           │
              ┌────────────┴────────────┐
              │                         │
              ▼                         ▼
       ⚛️ Frontend Service       🟢 Backend Service
              │                         │
              ▼                         ▼
       ┌──────────────┐         ┌──────────────┐
       │ Frontend Pod │         │ Backend Pod  │
       │   React     │         │ Node + API   │
       └──────────────┘         │ + Socket.IO  │
                                └──────┬───────┘
                                       │
                                       ▼
                                🍃 MongoDB
                                       │
                                       ▼
                              💾 Persistent Data
```

</p>

---

# ⚡ Real-Time Communication

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=700&color=00FF88&center=true&vCenter=true&width=650&lines=User+Connected+%F0%9F%9F%A2;Message+Sent+%F0%9F%92%AC;Socket.IO+Event+Triggered+%E2%9A%A1;Message+Delivered+Instantly+%E2%9C%85;Online+Status+Updated+%F0%9F%9F%A2">
</p>

```text
User A
  │
  │  💬 "Hello!"
  ▼
Socket.IO
  │
  │  ⚡ WebSocket Event
  ▼
Backend Server
  │
  ├──────────────► MongoDB
  │
  ▼
Socket.IO
  │
  ▼
User B
  │
  ▼
💬 "Hello!" received instantly
```

---

# 🐳 Containerized Application

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes&perline=2" />
</p>

Each application component runs inside a containerized environment and is orchestrated through Kubernetes.

```text
🐳 Frontend Container
        │
        ▼
☸️ Frontend Pod
        │
        ▼
🌐 Kubernetes Service


🐳 Backend Container
        │
        ▼
☸️ Backend Pod
        │
        ▼
⚡ Socket.IO + REST API


🐳 MongoDB Container
        │
        ▼
☸️ MongoDB Pod
        │
        ▼
💾 Application Data
```

---

# 🔄 Automated Deployment

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=500&color=00BFFF&center=true&vCenter=true&width=700&lines=git+push+%E2%86%92+Jenkins+%E2%86%92+Build+%E2%86%92+Test+%E2%86%92+Docker+%E2%86%92+Registry+%E2%86%92+Kubernetes;Zero+Manual+Deployment+%E2%9C%85;Continuous+Delivery+%F0%9F%9A%80">

</p>

### Deployment Flow

```text
                 🚀 CODE CHANGE
                       │
                       ▼
                  🐙 Git Push
                       │
                       ▼
                 🔴 Jenkins
                       │
              ┌────────┴────────┐
              ▼                 ▼
          📦 Build           🧪 Test
              │                 │
              └────────┬────────┘
                       ▼
                🐳 Docker Build
                       │
                       ▼
                📦 Push Registry
                       │
                       ▼
                 ☸️ Kubernetes
                       │
                       ▼
               🔄 Rolling Update
                       │
                       ▼
                 🌐 LIVE APP
```

---

# 📊 Project Workflow

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00BFFF,100:0066FF&height=3"/>

</p>

```text
        👤 USER
          │
          ▼
     ⚛️ React UI
          │
     ┌────┴─────┐
     │          │
     ▼          ▼
  REST API   Socket.IO
     │          │
     └────┬─────┘
          ▼
   🟢 Node.js API
          │
     ┌────┴─────┐
     │          │
     ▼          ▼
 🍃 MongoDB   ⚡ WebSocket
     │          │
     └────┬─────┘
          ▼
   💬 Real-Time Chat
```

---

# 🏆 DevOps Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,docker,kubernetes,jenkins,nginx&perline=6" />
</p>

### 🔧 DevOps Workflow

**GitHub → Jenkins → Docker → Container Registry → Kubernetes → Production**

* 🔴 **Jenkins** — Automated CI/CD
* 🐳 **Docker** — Application containerization
* ☸️ **Kubernetes** — Container orchestration
* 📦 **Container Registry** — Docker image storage
* 🌐 **Nginx / Ingress** — Application routing
* 🔄 **Rolling Updates** — Zero/minimal-downtime deployments

---

# 📈 Deployment Benefits

| Feature                    | Implementation         |
| -------------------------- | ---------------------- |
| ⚡ Fast Deployment          | Jenkins Automation     |
| 🔄 Continuous Delivery     | Automated CI/CD        |
| 📦 Consistent Environment  | Docker                 |
| ☸️ Scalability             | Kubernetes             |
| 🩺 Self-Healing            | Kubernetes             |
| 🔁 Rolling Updates         | Kubernetes Deployments |
| 🔐 Secrets Management      | Kubernetes Secrets     |
| 🌐 Traffic Routing         | Ingress / Nginx        |
| 💬 Real-Time Communication | Socket.IO              |

---

<p align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&color=00BFFF&center=true&vCenter=true&width=650&lines=Built+for+Real-Time+Communication+%F0%9F%92%AC;Automated+with+Jenkins+%F0%9F%94%B4;Containerized+with+Docker+%F0%9F%90%B3;Orchestrated+with+Kubernetes+%E2%98%B8%EF%B8%8F;Ready+for+Production+%F0%9F%9A%80">

</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0066FF,100:00BFFF&height=100&section=footer"/>
</p>

<p align="center">
  <b>⚛️ React ❤️ 🟢 Node.js ❤️ 🍃 MongoDB ❤️ ⚡ Socket.IO ❤️ ☸️ Kubernetes ❤️ 🔴 Jenkins</b>
</p>
