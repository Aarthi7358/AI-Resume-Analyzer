# 🧠 AI Resume Analyzer (Flask Project)

A smart AI-powered Resume Analyzer built using Python and Flask that extracts resume text, detects skills, and generates an ATS-style score.

---

## 🚀 Live Demo 
https://your-app-link.com

---

## 📌 Features

- 📤 Upload Resume (PDF / DOCX)
- 🧠 Extract text from resumes automatically
- 🔍 Detect key technical skills
- 📊 Generate ATS-style score (0–100)
- 🎨 Clean and modern UI
- ⚡ Fast Flask backend processing

---

## 🛠️ Tech Stack

- Python 🐍  
- Flask 🌐  
- PyPDF2 📄  
- python-docx 📝  
- HTML, CSS 🎨  

---

## 📁 Project Structure

```
resume-analyzer/
│
├── app.py                 # Flask backend
├── uploads/              # Uploaded resumes stored here
├── templates/
│     ├── index.html      # Upload page
│     └── result.html     # Result page
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
```

---

### 2️⃣ Install dependencies
```bash
pip install flask PyPDF2 python-docx
```

---

### 3️⃣ Run the application
```bash
python app.py
```

---

### 4️⃣ Open in browser
```
http://127.0.0.1:5000/
```

---

## 🧠 How It Works

```
User uploads resume
        ↓
Flask backend receives file
        ↓
Extract text from PDF/DOCX
        ↓
Match skills using keywords
        ↓
Generate ATS score
        ↓
Display results on UI
```

---

## 📊 Example Skills Detected

- Python  
- Java  
- Flask  
- SQL  
- HTML  
- CSS  
- Machine Learning  

---

## 📈 Scoring System

- Each detected skill adds to score
- Final score normalized to 100
- Simulates basic ATS evaluation

---

## 🎯 Future Improvements

- 🤖 AI-powered feedback using GPT
- 📊 Animated progress bar UI
- 📄 Downloadable PDF report
- 🌐 Deploy on Render / Vercel
- 📈 Advanced NLP skill detection

---

## 🧑‍💻 Author

Built by: **Aarthi PS**

---
