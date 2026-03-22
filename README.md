# 🤖 AI Virtual Assistant (MERN)

An AI-powered virtual assistant built with the **MERN stack** (MongoDB, Express, React, Node.js).  
Users can chat with the assistant in real time, view previous conversations, and manage their account securely.

---

##  Features

- 💬 **AI Chat Interface** – Real-time conversation with an AI assistant  
- 📚 **Conversation History** – Save and view previous chats  
- 👤 **User Authentication** – Register / Login with JWT-based auth  
- 🌗 **Dark / Light Mode** (optional)  
- 🎙️ **Voice Input / Output** (optional, if you implemented it)  
- ⚙️ **Configurable AI Settings** – Temperature, max tokens, system prompt, etc.  
- 🧩 **Modular & Scalable MERN Architecture**

---

## 🛠️ Tech Stack

**Frontend**
- React / Vite or CRA (React)
- React Router
- Axios / Fetch
- Tailwind CSS / Material UI / CSS Modules (update as needed)

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Tokens (JWT)
- AI Provider SDK or REST API (OpenAI / Gemini / others)

---

## 📁 Project Structure

```bash
.
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components (ChatBox, MessageBubble, etc.)
│   │   ├── pages/          # Route pages (Login, Signup, Chat, Profile)
│   │   ├── context/        # Auth / Theme / App context
│   │   ├── hooks/          # Custom React hooks
│   │   ├── services/       # API calls
│   │   └── main.jsx / index.js
│   └── package.json
│
├── server/                 # Node + Express backend
│   ├── src/
│   │   ├── config/         # DB connection, env config
│   │   ├── controllers/    # Route handlers (auth, chat, user)
│   │   ├── models/         # Mongoose models (User, Message, Conversation)
│   │   ├── routes/         # Express routes
│   │   ├── middleware/     # Auth, error handling, etc.
│   │   └── app.js / index.js
│   └── package.json
│
├── .env                    # Root or per app env (not committed)
├── README.md
└── package.json


Author: Priyanshu Raj
           
