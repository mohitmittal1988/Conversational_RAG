# 🧠 Conversational RAG with PDF Upload and Chat History

This project showcases a conversational Retrieval-Augmented Generation (RAG) pipeline built using **LangChain**, **Groq**, and **Streamlit**. Users can upload a PDF, ask context-based questions, and receive concise, document-aware answers powered by the `gemma2-9b-it` model.

---

## 🚀 Features

- 📄 **PDF Ingestion & Chunking** with LangChain
- 🤖 **Conversational RAG** with history-aware retrieval
- 💬 **Chat History Tracking** across user-defined sessions
- ⚡ **Fast, accurate responses** using Groq's Gemma LLM
- 🧠 **Standalone question reformulation** for context clarity
- 🔍 Dynamic context retrieval with Chroma vector store
- 🖥️ **Streamlit-based UI** for intuitive chat and uploads

---

## 🛠️ Tech Stack

- [LangChain](https://www.langchain.com/)
- [Streamlit](https://streamlit.io/)
- [Groq](https://console.groq.com/)
- [HuggingFace Embeddings](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
- [Chroma Vectorstore](https://www.trychroma.com/)
- Python 3.10+

---

## 📦 Setup

1. Clone the Repository
  ```bash
    git clone https://github.com/your-username/pdf-chat-rag-groq.git
    cd pdf-chat-rag-groq
2. Create a Virtual Environment
  ```bash
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
3. Install Dependencies
  ```bash
    pip install -r requirements.txt
4. Set Environment Variables
Create a .env file in the root directory:
  ```bash
    HF_TOKEN=your_huggingface_token
5. Run the App
  ```bash
    streamlit run app.py

### API Key Requirement
When prompted in the UI, provide your Groq API Key to access the gemma2-9b-it LLM.
