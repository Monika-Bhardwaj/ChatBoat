# 🤖 ChatBoat

**ChatBoat** is an AI-powered chatbot built using the **MERN stack**, styled with **Tailwind CSS**, powered by **Vite** for blazing-fast development, and integrated with the **Gemini API** for intelligent, context-aware responses.  

It provides a sleek chat interface that allows users to have natural, conversational interactions with AI — all inside a modern, responsive web app.

---

## 🚀 Features

- 💬 **Real-time AI Conversations** using Gemini API  
- ⚡ **Vite + React** frontend for fast performance  
- 🎨 **Tailwind CSS** for beautiful, responsive UI  
- 🌐 **Node.js + Express** backend  
- 🗄️ **MongoDB** for storing chat history or user sessions  
- 🔐 Secure API handling with environment variables  
- 🧩 Modular and easily extendable architecture  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React + Vite + Tailwind CSS |
| **Backend** | Node.js + Express |
| **Database** | MongoDB (via Mongoose) |
| **AI Integration** | Gemini API |
| **Version Control** | Git + GitHub |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/Monika-Bhardwaj/ChatBoat.git
cd ChatBoat

2️⃣ Install Dependencies
For the client:
cd client
npm install

For the server:
cd ../server
npm install

3️⃣ Create Environment Variables

Create a .env file in both client and server directories.

Server .env example:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key


Client .env example:

VITE_API_BASE_URL=http://localhost:5000

4️⃣ Run the App

In two separate terminals:

Backend:

cd server
npm run dev


Frontend:

cd client
npm run dev


Then open your browser at:
👉 http://localhost:5173

🧠 How It Works

The user sends a message through the chat interface.

The backend receives the request and forwards it to the Gemini API.

Gemini processes the message and returns a response.

The frontend displays the AI’s reply in real-time.

Optionally, all conversations can be saved in MongoDB for later retrieval.

📁 Project Structure
ChatBoat/
├── client/              # React + Vite frontend
│   ├── src/
│   │   ├── components/  # UI components
│   │   ├── pages/       # Chat and app pages
│   │   ├── utils/       # Helper functions
│   │   └── App.jsx
│   └── tailwind.config.js
│
├── server/              # Express backend
│   ├── routes/          # API endpoints
│   ├── controllers/     # Logic for handling chat requests
│   ├── models/          # MongoDB schemas
│   ├── server.js        # App entry point
│   └── .env
│
├── package.json
└── README.md

📸 Screenshots

(You can add screenshots of your app here — e.g. UI preview or chat window)
Example:

/assets/screenshots/chatboat-ui.png

🧩 Future Improvements

🧠 Add conversation memory and context persistence

🎤 Integrate voice input and output

🌍 Multi-language support

📱 Mobile-friendly chat interface

💾 Store and retrieve chat history

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or issue in the repo.

📜 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

👩‍💻 Author

Monika Bhardwaj
🔗 GitHub Profile

⭐ If you find this project helpful, please consider giving it a star on GitHub!
