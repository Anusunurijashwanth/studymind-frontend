# 🤖 StudyMind AI Frontend

Frontend for the **StudyMind AI Assistant** project.

This application allows users to upload PDF files, ask questions from the uploaded content, and also ask general questions using AI.

---

## 🚀 Tech Stack

- React.js
- Axios
- CSS

---

## ✨ Features

- 📄 Upload PDF files
- 💬 Chat-style interface
- 🧠 Ask questions from PDF
- 🌐 Ask general questions
- ⚡ Fast and responsive UI
- 🔗 Connected to Spring Boot backend

---

## 📂 Project Structure


studymind-frontend/
│
├── public/
│ └── index.html
│
├── src/
│ ├── components/
│ │ ├── Header.js
│ │ ├── UploadPDF.js
│ │ ├── ChatBox.js
│ │ └── Message.js
│ │
│ ├── services/
│ │ └── api.js
│ │
│ ├── App.js
│ ├── index.js
│ └── index.css
│
├── package.json
└── README.md


---

## ⚙️ Setup & Run

### 1️⃣ Clone the repository


git clone https://github.com/Anusunurijashwanth/studymind-frontend.git

cd studymind-frontend


---

### 2️⃣ Install dependencies


npm install


---

### 3️⃣ Run the application


npm start


---

## 🌐 Application URL


http://localhost:3000


---

## 🔗 Backend Connection

This frontend connects to Spring Boot backend.

Update this file:


src/services/api.js


### Example:


baseURL: "http://localhost:8080
"


---

## 🔌 API Endpoints

### Upload PDF


POST /api/ai/upload


---

### Ask Question


GET /api/ai/ask?question=your_question


---

### Check Status


GET /api/ai/status


---

## ⚠️ Important Notes

- Backend must be running before using frontend
- PDF processing may take a few seconds
- AI service (FastAPI + Ollama) should be active

---

## 🧠 Example Questions

- What is this PDF about?
- Explain this document
- What are the topics in this PDF?
- What is Python?
- Java roadmap

---

## 🚀 Deployment

You can deploy this frontend using:

- Vercel (recommended)
- Netlify

---

## 👨‍💻 Author

**Anusunuri Jashwanth**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
