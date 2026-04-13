# 🎓 ProjectVault – Academic Project Selection System

## 👥 Authors

* L.Sivamani(Y22ACS489)
* K.Y.Sai Sandeep(L23ACS604)
* M.Gayathri(Y22ACS502)
* Y.Vamsi Krishna(Y22ACS595)

---

## 🚀 Implementation

ProjectVault is a full-stack web application designed to manage, validate, and track academic project submissions using **Natural Language Processing (NLP)** and **Artificial Intelligence (AI)**.

---

## 📌 Overview

The Academic Project Selection System helps institutions streamline project submission and evaluation by preventing duplicate projects and improving project quality.

The system analyzes project content using:

* NLP-based similarity detection
* AI-based validation
* Role-based project management

---

## 🛠️ Technologies Used

### 🔹 Backend

* Python
* FastAPI
* PostgreSQL
* SQLAlchemy
* spaCy (NLP)
* Scikit-learn (TF-IDF, Cosine Similarity)
* Groq API (LLM-based validation)

### 🔹 Frontend

* React (Vite)
* Tailwind CSS
* Axios
* React Router

---

## ⚙️ Features

* 📄 Project submission and management
* 🔍 NLP-based similarity detection (duplicate checking)
* 🤖 AI-powered project validation and feedback
* 🔐 Role-based access control (Student / Guide / Admin)
* 📊 Dashboard with project status tracking
* 📝 Review and approval system
* ⚡ Real-time feedback on project quality

---

## 📂 Project Structure

### Backend

```
backend/
 ├── main.py
 ├── database.py
 ├── nlp_engine.py
 ├── ai_validator.py
 ├── routes/
 │    ├── auth.py
 │    ├── projects.py
 │    └── reviews.py
 └── requirements.txt
```

### Frontend

```
frontend/
 ├── src/
 │    ├── pages/
 │    ├── context/
 │    ├── utils/
 │    └── main.jsx
 └── package.json
```

---

## ⚙️ Setup & Installation

### 🔹 Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 🔹 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 Usage

1. Open the frontend in browser
2. Register/Login as Student/Guide/Admin
3. Submit a new project
4. System performs:

   * AI validation
   * NLP similarity check
5. View results on dashboard

---

## 📊 Output

The system provides:

* ✅ Similarity Score (0–100%)
* 🤖 AI Validation Feedback
* 📌 Project Status (Pending / Approved / Rejected)

---

## 🔮 Future Work

* 📈 Improve similarity accuracy using deep learning models
* 🌍 Multilingual project analysis
* 📊 Advanced analytics dashboard
* 🔗 Integration with institutional databases

---

## 📎 GitHub Repositories

* Backend: https://github.com/Bujji2801/Academic-Project-Selection-backend.git
* Frontend: https://github.com/Bujji2801/Academic-Project-Selection-frontend.git

---

## 📌 Conclusion

ProjectVault provides an intelligent solution for academic project management by integrating NLP and AI techniques. It helps reduce duplicate submissions, improves project quality, and streamlines the evaluation process.

---
