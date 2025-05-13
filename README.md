# 📚 CTSE Lecture Notes Chatbot


The **CTSE Lecture Notes Chatbot** is a chatbot that allows students to ask questions about their lecture materials and receive accurate, citation-based answers. The chatbot processes PDFs from a selected folder, converts them into searchable chunks using vector embeddings, and uses a Large Language Model (LLM) to generate responses based entirely on the course content.

This solution is designed to reduce the time students spend manually searching through lecture documents, enabling smarter, faster, and more focused learning.

---

## ✨ Key Features

- 🔍 **Ask questions about lecture notes in plain English**
- 🧠 **Powered by Gemini 2.0 Flash** from Google GenAI
- 🗃 **Retrieval-Augmented Generation (RAG)** pipeline for accuracy
- ⚡️ **FAISS** for fast vector-based document retrieval
- 🔄 **Maximum Marginal Relevance (MMR)** for diverse search results
- 🖥 **AI-generated Tkinter GUI** for easy interaction
- 📌 **Responses are always grounded in source material with citations**
- 🧱 Modular, class-based code structure for extensibility

---

## 🔐 API Keys Required

To run the application, **you must provide the following API keys** when prompted at startup:

1. **`GOOGLE_API_KEY`**  
   For accessing the Gemini 2.0 Flash model and generating embeddings.

2. **`LANGSMITH_API_KEY`**  
   For LangSmith-based debugging, tracing, and evaluation tools.

3. **`UNSTRUCTURED_API_KEY`** *(Optional but recommended)*  
   For processing scanned and complex PDF documents with the Unstructured API.

These are entered securely via GUI prompts and are not hardcoded.

---
