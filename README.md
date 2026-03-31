## SketchFlow

### A Web-Based Real-Time Collaborative Whiteboard System

---

🚧 **Project Status:** *In Progress*

SketchFlow is a web-based digital whiteboard platform that enables **real-time collaboration** among multiple users. It allows participants to draw, write, and interact simultaneously on a shared canvas from different locations with low latency.

---

## ✨ Features

* 🖊️ Real-time drawing & editing
* 👥 Multi-user collaboration
* ⚡ Low-latency synchronization using WebSockets
* 🎨 Drawing tools (pen, eraser, shapes, colors)
* 💬 Real-time chat system
* 🔄 Session persistence & recovery

---

## 🛠️ Tech Stack

### 🎨 Frontend

* HTML5, CSS3 (Modern UI / Glassmorphism)
* Vanilla JavaScript (Canvas API)
* SockJS (WebSocket fallback)

### ⚙️ Backend

* Java + Spring Boot
* STOMP over WebSocket (Real-time messaging)
* REST APIs for session handling

### 📡 Realtime Communication

* WebSockets
* STOMP Protocol

### 🗄️ Database & Cache

* MySQL (Persistent storage)
* Redis (In-memory cache & Pub/Sub messaging)

### 🧰 Dev Tools

* IntelliJ IDEA
* Maven
* Git

---

## 📌 Use Cases

* Online teaching & learning
* Team collaboration & brainstorming
* Remote meetings
* UI/UX wireframing

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/sketchflow.git

# Navigate into the project directory
cd sketchflow

# Build backend (Spring Boot)
mvn clean install

# Run backend
mvn spring-boot:run
```


## 📄 License

This project is licensed under the MIT License.

---
