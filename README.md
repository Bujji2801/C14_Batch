🧠 Academic Project Selection System (ProjectVault)
👥 Authors
Your Name
(Add your teammates if any)
🚀 Implementation

Academic Project Selection System is a full-stack web application that helps institutions manage, validate, and track student project submissions using AI and NLP techniques.

📌 Overview

The system is designed to eliminate duplicate project submissions and improve the quality of academic projects through intelligent validation.

It uses advanced technologies to analyze project content based on:

Natural Language Processing (NLP)
Machine Learning similarity detection
AI-based validation using LLM
🔗 GitHub Repositories
Backend: https://github.com/Bujji2801/Academic-Project-Selection-backend
Frontend: https://github.com/Bujji2801/Academic-Project-Selection-frontend
🛠️ Technologies Used
🔹 Backend
Python
FastAPI
PostgreSQL
SQLAlchemy
spaCy (NLP)
Scikit-learn (TF-IDF, Cosine Similarity)
Groq API (AI Validation)
🔹 Frontend
React
Vite
Tailwind CSS
Axios
⚙️ Features
📌 Project submission and management
🔍 NLP-based similarity detection (TF-IDF + cosine similarity)
🤖 AI-based project validation and feedback
👥 Role-based access (Student, Guide, Admin)
📊 Dashboard with project status tracking
🔐 Secure authentication using JWT
📈 Real-time feedback on project quality
🧩 System Architecture
Frontend: React (Vercel)
Backend: FastAPI (Render)
Database: PostgreSQL
AI/NLP: spaCy + Groq API
📂 Project Structure
Backend
backend/
 ├── main.py
 ├── database.py
 ├── nlp_engine.py
 ├── ai_validator.py
 ├── routes/
 └── requirements.txt
Frontend
frontend/
 ├── src/
 │   ├── pages/
 │   ├── components/
 │   ├── context/
 │   └── utils/
 └── package.json
🔮 Future Work
📊 Improve NLP accuracy using advanced models
🌍 Multilingual project analysis
📱 Mobile application support
📈 Advanced analytics dashboard
🤖 Enhanced AI feedback using latest LLMs
📎 Usage
Run Backend
uvicorn main:app --reload
Run Frontend
npm install
npm run dev

Open browser:

http://localhost:5173
📊 Output

The system provides:

✔ Similarity score (0–100%)
✔ AI-based feedback on project quality
✔ Project status (Pending / Approved / Rejected)
📌 Conclusion

This project provides an intelligent solution for academic institutions by integrating NLP-based similarity detection and AI validation, ensuring originality, improving project quality, and streamlining the project evaluation process.
