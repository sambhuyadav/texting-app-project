# 📱 TextApp

A real-time texting application built with **React.js** and **DaisyUI** for the frontend, **Node.js**, **Express**, and **Socket.IO** for the backend, and **MongoDB** for data persistence.

---

## 🔧 Tech Stack

### 🖥️ Frontend
- [React.js](https://reactjs.org/)
- [DaisyUI](https://daisyui.com/) (Tailwind CSS Components)
- [Vite](https://vitejs.dev/) for fast development
- [Socket.IO Client](https://socket.io/)

### 🔙 Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Socket.IO](https://socket.io/) for real-time communication
- [MongoDB](https://www.mongodb.com/) for database
- JWT for authentication

---

## 📁 Project Structure

```bash
TEXTAPP/
├── backend/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── utils/
│   ├── generateToken.js
│   └── server.js
├── frontend/
│   ├── dist/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── ...
├── .env
├── .gitignore
├── package.json
└── README.md
