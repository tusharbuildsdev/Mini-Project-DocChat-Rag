# 📄 Mini-Project-DocChat-RAG


# 👨‍💻 Author

## Tushar Verma

B.Tech CSE (AI)

Python Developer

AI & Machine Learning Enthusiast

GitHub:
https://github.com/tusharbuildsdev

LinkedIn:
https://linkedin.com/in/tusharbuildsdev

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python">

<img src="https://img.shields.io/badge/Framework-Streamlit-red?style=for-the-badge&logo=streamlit">

<img src="https://img.shields.io/badge/LLM-Groq-orange?style=for-the-badge">

<img src="https://img.shields.io/badge/VectorDB-ChromaDB-success?style=for-the-badge">

<img src="https://img.shields.io/badge/Embeddings-SentenceTransformers-yellow?style=for-the-badge">

<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">

</p>

---

# 🚀 Overview

**Mini-Project-DocChat-RAG** is an AI-powered document question answering application that allows users to upload **PDF, DOCX, and TXT** files and ask questions in natural language.

Instead of searching manually through large documents, the application retrieves the most relevant information using **Retrieval-Augmented Generation (RAG)** and generates accurate answers with **Groq LLM**.

---

# ✨ Features

- 📄 Upload PDF documents
- 📝 Upload DOCX documents
- 📃 Upload TXT files
- 🤖 AI-powered Question Answering
- ⚡ Groq LLM Integration
- 🧠 Semantic Search using Sentence Transformers
- 📚 ChromaDB Vector Database
- ✂️ Automatic Text Chunking
- 🎯 Context-aware Responses
- 💬 Interactive Streamlit Interface
- 🔒 Secure API Key using .env
- 🚀 Fast and Lightweight

---

# 🏗️ Project Architecture

```

                User
                  │
                  ▼
          Upload Document
        (PDF / DOCX / TXT)
                  │
                  ▼
           File Loader
                  │
                  ▼
          Text Extraction
                  │
                  ▼
             Chunking
                  │
                  ▼
      Sentence Transformer
          Embeddings
                  │
                  ▼
            ChromaDB
        Vector Database
                  │
                  ▼
       Similarity Search
                  │
                  ▼
             Groq LLM
                  │
                  ▼
          Final Response

```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Streamlit | Frontend |
| Groq API | LLM |
| ChromaDB | Vector Database |
| Sentence Transformers | Embeddings |
| PyPDF | PDF Reader |
| python-docx | DOCX Reader |
| dotenv | Environment Variables |

---

# 📂 Project Structure

```

Mini-Project-DocChat-RAG
│
├── app.py
├── llm.py
├── rag.py
├── chunker.py
├── vector_store.py
├── file_loader.py
├── config.py
│
├── requirements.txt
├── README.md
├── .env.example
├── .gitignore
│
└── uploaded_docs.pdf

```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/Mini-Project-DocChat-Rag.git
```

## 2️⃣ Go to Project

```bash
cd Mini-Project-DocChat-Rag
```

## 3️⃣ Create Virtual Environment

Windows

```bash
python -m venv .venv
```

Activate

```bash
.venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Create .env

Create a file named

```
.env
```

Inside it

```env
GROQ_API_KEY=your_api_key_here
```

---

## 6️⃣ Run Application

```bash
streamlit run app.py
```

Application will open automatically in your browser.

---

# 📖 How It Works

### Step 1

Upload a document.

↓

### Step 2

The application extracts text.

↓

### Step 3

Text is divided into chunks.

↓

### Step 4

Embeddings are generated.

↓

### Step 5

Embeddings are stored in ChromaDB.

↓

### Step 6

User asks a question.

↓

### Step 7

Relevant chunks are retrieved.

↓

### Step 8

Groq generates the final answer.

---

# 📸 Screenshots

## Home Page

```

assets/home.png

```

## Upload Document

```

assets/upload.png

```

## Ask Questions

```

assets/chat.png

```

---

# 🎥 Demo

A demo GIF can be placed inside

```

assets/demo.gif

```

---

# 💡 Example Questions

```
Summarize this document.

What is the conclusion?

Who is the author?

Explain Chapter 3.

What are the key points?

```

---

# 📌 Future Improvements

- OCR Support
- Multiple PDF Upload
- Chat History
- Conversation Memory
- Image OCR
- Voice Input
- Citation Support
- Highlight Source Paragraph
- Export Chat
- Dark Mode
- Authentication
- Cloud Deployment

---

# 🔒 Environment Variables

```
GROQ_API_KEY=YOUR_API_KEY
```

---

# 📦 Requirements

Major libraries used

- Streamlit
- Groq
- ChromaDB
- Sentence Transformers
- Transformers
- Torch
- python-docx
- PyPDF
- python-dotenv

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📝 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Tushar Verma

B.Tech CSE (AI)

Python Developer

AI & Machine Learning Enthusiast

GitHub:
https://github.com/tusharbuildsdev

LinkedIn:
https://linkedin.com/in/tusharbuildsdev

---

# ⭐ If you found this project helpful...

Please consider giving it a **Star ⭐** on GitHub.

It motivates me to build more useful open-source AI projects.

---