# 💬 Real-Time Chat Application

A sleek, full-stack real-time chat application built using **React**, **Node.js**, and **Socket.IO**. Supports real-time messaging, user login, and dark/light theme toggle 🌙☀️. Designed with a clean and modern UI.

---

## 🚀 Live Demo

🌐 **Frontend:** [https://your-frontend.netlify.app](https://your-frontend.netlify.app)  
⚙️ **Backend (Socket.IO):** [https://your-backend.onrender.com](https://your-backend.onrender.com)

---

## 📸 Screenshots

| 💻 Chat Screen | 🧑‍💻 Login Screen | 🌗 Day/Night Toggle |
|:--------------:|:----------------:|:------------------:|
| ![chat](assets/chat.png) | ![login](assets/login.png) | ![darkmode](assets/darkmode.png) |

---

## 🛠️ Tech Stack

**Frontend:**  
- React.js ⚛️  
- Socket.IO Client  
- CSS (Dark & Light Mode)

**Backend:**  
- Node.js  
- Express.js  
- Socket.IO Server  
- CORS

**Hosting:**  
- Netlify (Frontend)  
- Render (Backend)

---

## ✨ Features

- 🚀 Real-time message updates using Socket.IO
- 🔐 Simple username login system
- 🌓 Light/Dark theme toggle
- 🕒 Timestamped messages
- 🧍 Own messages are right-aligned
- 💻 Responsive layout

---

## 📁 Project Structure

```
chat-app/
│
├── backend/
│   └── server.js         # Node.js + Socket.IO server
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── App.js        # Main chat UI
│   │   ├── Login.js      # Username login screen
│   │   └── index.js
│   └── package.json
```

---

## 🧑‍💻 Getting Started Locally

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/realtime-chat-app.git
cd realtime-chat-app
```

### 2. Start Backend
```bash
cd backend
npm install
node server.js
```

### 3. Start Frontend
```bash
cd ../frontend
npm install
npm start
```

The app will be live at `http://localhost:3000`.

---

## 🌐 Deployment Steps

### ✅ Backend (Render)
- Push backend folder to GitHub
- Create a new Web Service on Render
- Set start command: `node server.js`
- Change your socket connection URL in frontend to Render URL

### ✅ Frontend (Netlify)
- Build React app with `npm run build`
- Deploy `/build` folder to Netlify

---

## 🙌 Credits

Made with ❤️ by [Your Name](https://github.com/yourusername)

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).
