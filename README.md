# Multi-Chatbot System 🤖

A **scalable, modular, and production-ready web application** that integrates multiple chatbots into a unified platform. This system provides a foundation for building intelligent conversational agents that can serve different use cases, such as customer support, FAQs, knowledge bases, or personal assistants.

---

## 🚀 Features
- 🔹 **Multi-Bot Support** – Handle multiple chatbot modules in a single system.
- 🔹 **Full-Stack Setup** – Includes a backend (Python/FastAPI) and frontend (React).
- 🔹 **API-First Design** – REST APIs for easy integration and scaling.
- 🔹 **Deployment Ready** – Configured with Netlify, build scripts, and deployment checklists.
- 🔹 **Extensible Architecture** – Add new bots or models with minimal effort.

---

## 📂 Project Structure

Multi-chatbot-System/
│── backend/ # FastAPI backend for chatbot APIs
│── frontend/ # React-based user interface
│── build.sh # Linux build script
│── build.ps1 # Windows build script
│── deploy.md # Deployment guide
│── DEPLOYMENT_CHECKLIST.md # Pre-deployment checklist
│── netlify.toml # Netlify deployment config
│── test-production.sh # Testing script for production
│── README.md # Project documentation


---

🛠️ Tech Stack
- **Frontend:** React, JavaScript, TailwindCSS
- **Backend:** Python (FastAPI)
- **Deployment:** Netlify, GitHub Actions
- **Others:** Shell scripts for automation

---

⚙️ Setup Instructions

 1. Clone the Repository
```bash
git clone https://github.com/hemanthsinghk14/Multi-chatbot-System.git
cd Multi-chatbot-System
2. Backend Setup
cd backend
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
➡️ Backend runs at: http://localhost:8000
3. Frontend Setup
cd frontend
npm install
npm start
➡️ Frontend runs at: http://localhost:3000
```
🚀Deployment :-

This project includes preconfigured deployment settings.
Frontend → Deploy via Netlify (see netlify.toml)
Backend → Deploy on Render, Heroku, or Docker
Check DEPLOYMENT_CHECKLIST.md & deploy.md for detailed steps.

✅ Production Checklist :-

 Dependency management
 Environment variable setup
 Build & test scripts
 Deployment configs
 Hosting ready

 🧪 Testing :-
 
Run production tests: 
./test-production.sh

📌 Future Enhancements : -

🔮 Add support for LLM-based chatbots (OpenAI, Hugging Face).
🔮 User authentication & role-based chatbot access.
🔮 Analytics dashboard for chatbot performance.
🔮 Multi-language support.

🤝 Contributing :-

Contributions are welcome!
Please fork the repo and create a pull request with your improvements.



