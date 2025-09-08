# 📱 chitChat

A **real-time chat application** built to simulate core features of WhatsApp. This project demonstrates **system design, scalability, and full-stack development skills** using modern web technologies.  

---

## 🚀 Tech Stack
- **Backend:** Node.js, Express.js  
- **Real-Time Communication:** Socket.io (WebSockets)  
- **Database:** MongoDB (for storing messages, users, groups)  
- **Caching & Pub/Sub:** Redis (for message queues, presence management)  
- **Frontend:** React.js (optional, planned)  
- **Authentication:** JWT / OAuth2 (planned)  
- **Deployment:** Docker, Kubernetes (future scope)  

---

## ✨ Features (Planned & Implemented)
- ✅ **1-1 Chat** – private messaging between users  
- ✅ **Group Chat** – create and manage group conversations  
- ✅ **Online Presence** – show if user is online/offline (using Redis)  
- ✅ **Message History** – persist messages in MongoDB  
- 🔜 **Media Sharing** – send images, videos, documents  
- 🔜 **Typing Indicators** – show “typing…” in real-time  
- 🔜 **Read Receipts** – single tick (sent), double tick (delivered), blue tick (read)  
- 🔜 **Push Notifications** – notify users for new messages  

---

## ⚙️ Setup & Installation
```bash
### 1. Clone the repository
git clone 

### 2. Install dependencies
npm install

### 4. Run The Server
npm start

### 1. (Optional) Run with Docker
docker-compose up


## Project Structure
│── backend/            # Express + Socket.io server
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API routes
│   ├── services/       # Business logic
│   └── server.js       # Main entry point
│
│── frontend/           # React client (planned)
│
│── README.md           # Project documentation
```
## Future Scope
- Multi-device sync (like WhatsApp Web)
- End-to-End Encryption (E2EE)
- Scaling with Kafka / RabbitMQ for distributed messaging
- Deploy on AWS/GCP with Kubernetes + Load Balancer
- Integrate AI chatbot (for smart replies)

## Why this project
- Practice system design concepts (real-time communication, scalability, consistency).
- Build an interview-ready project for FAANG-level SDE roles.
- Showcase full-stack engineering skills with real-time, distributed systems.