# AI-Paper-Generator
# 🤖 AI Teacher Assistant – Exam Question Generator

An AI-powered web application to generate **short answer**, **long answer**, and **multiple-choice questions (MCQs)** from uploaded documents (PDF, DOCX, TXT). Perfect for teachers, educators, and content creators!

---

### 🧠 Features

- 📄 Upload multiple documents (PDF, DOCX, TXT)
- 🧾 Auto-generate:
  - Short answer questions
  - Long answer questions
  - Multiple-choice questions (MCQs)
- 💾 Download questions as **PDF** or **DOCX**
- 🔐 User login system (basic session-based)
- ⚡ Powered by **Groq + LLaMA 3 + LangChain**
- 💻 Easy-to-use web interface (Bootstrap)

---

### 🚀 Live Demo

> *(Coming Soon — deploy on Render, Hugging Face, or your own server)*

---

### 📸 Screenshots

| Upload & Generate | Output & Download |
|-------------------|-------------------|
| ![upload](screenshots/upload.png) | ![questions](screenshots/output.png) |

---

### 🛠️ Tech Stack

- **Frontend**: HTML + Bootstrap 5
- **Backend**: Flask (Python)
- **AI/NLP**: LangChain + HuggingFace Embeddings + Groq (LLaMA3)
- **File Handling**: `python-docx`, `fpdf`
- **Authentication**: Flask Session (Basic)

---

### 📦 Installation

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-teacher-assistant.git
cd ai-teacher-assistant

# 2.Create Virtual Enviroment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## 3. Install Dependencies
pip install -r requirements.txt

## 4. Add your Groq API key
Create a .env file:
GROQ_API_KEY=your_groq_api_key_here
You can get your API key from https://console.groq.com/

5000

🔑 Default Login
Username	Password
teacher  	pass123


