# 💬 Real-Time Chat Application

A full-stack real-time chat application built with **React** on the frontend and **Spring Boot + WebSocket + STOMP** on the backend. The app supports **room-based chat**, live message broadcasting, and smooth user interactions — all in real time.

---


## 🧰 Tech Stack

- **Frontend**: React.js, SockJS, STOMP over WebSocket
- **Backend**: Spring Boot, WebSocket, STOMP Protocol
- **Build Tools**: Maven, npm
- **Languages**: Java, JavaScript

---

## 📁 Project Structure

chat-app/
├── chat-app-backend/ # Spring Boot backend
└── front-chat/ # React frontend


---

## 🚀 Features

- Join or create chat rooms
- Real-time communication using WebSockets
- Auto-scroll chat UI
- Notification when users join/leave
- Clean and responsive UI

---

## ⚙️ Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- Node.js & npm
- Git

### Backend Setup

```bash```
cd chat-app-backend
mvn clean install
mvn spring-boot:run 

The backend runs on http://localhost:8080 and handles WebSocket connections.

### Frontend Setup
cd front-chat
npm install
npm start



