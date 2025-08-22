# 📄 Document QA Bot (RAG Project)

## 📌 Overview
This is my first Machine Learning / GenAI project 🚀  
I built a simple Question-Answering (QA) bot using **Retrieval-Augmented Generation (RAG)**.  

The bot can read a document, store it in a vector database, and then answer natural language questions based only on that document.  

---

## ⚙️ How It Works
1. **Document Loading** – Upload a text/PDF file.  
2. **Chunking** – Split the document into smaller parts.  
3. **Embedding** – Convert each chunk into numerical vectors.  
4. **Store in FAISS** – Save embeddings in a vector database for fast retrieval.  
5. **QA Pipeline** – Retrieve relevant chunks + use an LLM to generate answers.  

---

## 🛠️ Tech Stack
- Python  
- LangChain  
- FAISS (vector database)  
- Google Colab (runtime environment)  

---

## 🚀 Features
- Upload your own document 📑  
- Ask natural questions ❓  
- Get context-aware answers 💡  
- Handles edge cases (like irrelevant/funny questions) gracefully 🤖  

---

## 📝 Example Interaction
Ask a question (or 'exit'): give three important points from document
Answer: Exploratory analysis, handling missing data, and standardizing formats.

Ask a question (or 'exit'): are you mad?
Answer: No, I'm not mad.

Ask a question (or 'exit'): exit
Thanks for using my QA bot! Bye 👋

---

## 📂 Project Files
├── document_qa.ipynb # Main Google Colab notebook

├── README.md # Project documentation

---

## ✨ Learning Outcomes
- Understood the basics of the RAG pipeline  
- Hands-on practice with LangChain and FAISS  
- Built a small document-based QA bot  
- Learned how to test for edge cases (irrelevant queries, exit command, casual questions)  

---

## 🔮 Future Improvements
- Add support for multiple documents  
- Improve user interface (web/app)  
- Use a more advanced LLM for better answers  

---

This was my **first step into ML/GenAI projects** 🎉  
