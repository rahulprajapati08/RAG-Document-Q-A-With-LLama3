# 📄 RAG Document Q&A with GROQ API and LLaMA 3

This is a **Retrieval-Augmented Generation (RAG)** based document question-answering app powered by the **GROQ API** and **Meta’s LLaMA 3 model**. Built using **Streamlit**, the app allows users to upload documents (PDF or text), ask questions, and receive precise, context-aware answers based on the document content.

---

## 🚀 Features

- 📄 Upload any document (PDF or `.txt`)
- 🔍 Asks context-aware questions using RAG
- 🧠 Uses **GROQ API with LLaMA 3** for fast and accurate LLM responses
- 🧬 Supports **OpenAI**  embeddings
- 🔐 Secure API key management with `.env` file
- 🖥️ Intuitive frontend with **Streamlit**

---

## 🧠 Tech Stack

- **Frontend**: Streamlit
- **LLM**: LLaMA 3 via GROQ API
- **Embeddings**: OpenAI 
- **Vector Store**: FAISS
- **Language**: Python

---

## ⚙️ Setup Instructions

> ⚠️ This app is not deployed yet. Follow the steps below to run it locally.

1. Clone the repository:
   ```bash
    git clone https://github.com/your-username/RAG-Document-Q-A-With-LLama3.git
    cd RAG-Document-Q-A-With-LLama3
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Create .env File
   ```bash
   GROQ_API_KEY=your_groq_api_key
    OPENAI_API_KEY=your_openai_api_key  # optional , if you are using huggingface embeddings then add huggingface token

4. Launch the App:
   ```bash
   streamlit run main.py

---

## 📷 Screenshots
<img width="1280" height="720" alt="Screenshot 2025-08-07 174658" src="https://github.com/user-attachments/assets/e871d348-9243-4c7b-a6d2-da4450b8a0fd" />
<img width="1280" height="720" alt="Screenshot 2025-08-07 174630" src="https://github.com/user-attachments/assets/b874922f-f350-4066-bb0c-5ca1c616eec4" />

---

## 💡 Future Improvements
 - ✅ User dashboard with session history

 - ✅ Embedding selection UI

 - 🔜 Deployment on Streamlit Cloud

 - 🔜 Support for multiple file formats (docx, CSV)

 - 🔜 Chat history & PDF highlight references


