# 💬 Real-Time Chat App

A full-stack chat application built using **React.js** for the frontend and **Spring Boot with WebSocket** for the backend. It supports real-time messaging in chat rooms with a simple and responsive UI.

---

## 🧰 Tech Stack

- **Frontend**: React, WebSocket (via SockJS + STOMP)
- **Backend**: Spring Boot, WebSocket
- **Build Tools**: npm, Maven
- **Languages**: Java, JavaScript

---

## 📁 Project Structure

```
chat-app/
├── chat-app-backend/   # Spring Boot backend
└── front-chat/         # React frontend
```

---

## 🚀 Features

- Real-time messaging
- Create or join chat rooms
- User join/leave notifications
- Auto-scrolling chat UI
- Responsive layout

---

## ⚙️ How to Run

### Backend (Spring Boot)

```bash
cd chat-app-backend
mvn clean install
mvn spring-boot:run
```
Runs at: `http://localhost:8080`

---

### Frontend (React)

```bash
cd front-chat
npm install
npm start
```
Runs at: `http://localhost:3000`

---

If you find any issue or have suggestions, feel free to reach out or open an issue.
