📄 AI Resume Analyzer

An AI-powered web application that analyzes resumes, extracts skills, and generates an ATS-style score using Python and Flask.

🚀 Features
📤 Upload Resume (PDF / DOCX)
🧠 Extracts text from resumes
🔍 Detects key skills automatically
📊 Generates ATS-style score (0–100)
🎨 Clean modern UI with Flask frontend
⚡ Fast and lightweight local web app
🛠️ Tech Stack
Python 🐍
Flask 🌐
PyPDF2 📄
python-docx 📝
HTML, CSS 🎨
📁 Project Structure
resume-analyzer/
│
├── app.py
├── uploads/
├── templates/
│     ├── index.html
│     └── result.html
└── README.md
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/resume-analyzer.git
cd resume-analyzer
2. Install dependencies
pip install flask PyPDF2 python-docx
3. Run the application
python app.py
4. Open in browser
http://127.0.0.1:5000/
📊 How It Works
User uploads resume
        ↓
Flask backend receives file
        ↓
Extract text from PDF/DOCX
        ↓
Match skills using keyword logic
        ↓
Generate ATS score
        ↓
Display result on UI
🧠 Example Skills Detected
Python
Java
Flask
SQL
HTML
CSS
Machine Learning
📌 Future Improvements
🤖 AI-powered resume feedback (GPT-based)
📊 Animated score progress bar
📄 Downloadable PDF report
🌐 Live deployment (Render / Vercel)
📈 Advanced ATS matching system
💡 Note

This is a beginner-friendly AI project that simulates resume analysis using keyword-based logic. It can be upgraded into a full AI system using NLP or LLMs.

👨‍💻 Author

Built by: Aarthi PS
