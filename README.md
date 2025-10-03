# 📰 Open2Talk

A secure, Medium-like platform for anonymous article publishing.  
This project empowers **journalists, whistleblowers, and activists** to share the truth without fear—by protecting their identity.

---

## 🛠️ Tech Stack

- **Frontend:** React + TailwindCSS  
- **Backend:** Node.js + Express + MongoDB  
- **Deployment:** Docker + docker-compose  

---

## 🚀 Features

- ✍️ **Anonymous Article Publishing** – No real names, only pseudonyms  
- 🔒 **Identity Protection** – No IP logging, no metadata  
- 📖 **Reader Feed** – Browse all published articles  
- 💬 **Simple & Secure Discussions** *(planned)*  
- 🌍 **Dockerized Setup** – One command to run frontend, backend, and MongoDB  

---

## 📁 Project Structure

Open2Talk/  
├── backend/               # Node.js + Express API  
│   ├── src/  
│   │   ├── controllers/   # Post logic  
│   │   ├── models/        # MongoDB schemas  
│   │   ├── routes/        # Express routes  
│   │   └── app.js         # Main app entry  
│   ├── Dockerfile  
│   └── package.json  
│  
├── frontend/              # React + Tailwind frontend  
│   ├── src/               # Components & pages  
│   ├── Dockerfile  
│   └── package.json  
│  
├── docker-compose.yml     # Orchestration for backend + frontend + DB  
└── README.md  

---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites

Make sure you have installed:

- [Docker](https://www.docker.com/)  
- [docker-compose](https://docs.docker.com/compose/)  

### 3️⃣ Run with Docker

```bash
docker-compose up --build
```

### 4️⃣ Access the App

- Frontend → [http://localhost:3000](http://localhost:3000)  
- Backend API → [http://localhost:5000/api/posts](http://localhost:5000/api/posts)  
- MongoDB → runs inside container (`mongodb://mongo:27017/anonmedium`)  

---

## 🔧 Development (Without Docker)

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm start
```

---

## 🔮 Roadmap

- 🛡 Strip metadata from uploaded files  
- 🕵️ Support for Tor/Onion routing  
- ⛓ Blockchain/IPFS integration for censorship resistance  
- 🗳 Community moderation + trust system  

---

## 🤝 Contributing

Contributions are welcome!  
Fork the repo, create a branch, and submit a PR with your changes.

---

## ⚠️ Disclaimer

This project is built for ethical use cases like protecting free speech, whistleblowing, and journalism in oppressive environments.  
The maintainers are not responsible for misuse of the platform.

---
