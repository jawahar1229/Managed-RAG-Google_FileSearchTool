# 📘 Google GenAI Knowledge Base (RAG)

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using **Google GenAI**. It allows you to upload documents (PDF, TXT, MD), index them into a knowledge store, and ask questions with grounded answers and citations.

---

## ✅ Pre-requisites

### 1. Python Packages

```bash
pip install -U google-genai
pip install pip-system-certs   # Only if behind a corporate firewall
```

### 2. Generate API Key

1. Visit **Google AI Studio** at https://aistudio.google.com/api-keys
2. Create an API key
3. Replace `<<YOUR_API_KEY>>` in the notebook

---

## 📂 Project Structure

```
.
├── README.md
├── Google_GenAI_ManagedRAG_FileSearch.ipynb
└── my articles/
    ├── doc1.pdf
    ├── notes.txt
    └── guide.md
```

---

## 🚀 What the Notebook Does

1. Initializes Google GenAI client
2. Creates a File Search Knowledge Store
3. Uploads and indexes documents
4. Queries the knowledge base using Gemini
5. Displays grounded answers with citations

---

## ▶️ Usage

1. Open `knowledge_base.ipynb`
2. Add your API key
3. Place documents in `my articles/`
4. Run all cells
5. Call `ask_knowledge_base("your question")`

---

## ⚠️ Notes

- SSL verification is disabled for corporate networks
- Intended for internal / controlled environments only

---

✅ Ready to use and share 🚀
