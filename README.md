# 📄 Conversational RAG with PDF Q&A and Chat History 🧠💬

Interact seamlessly with your PDF documents using a **Conversational Retrieval-Augmented Generation (RAG)** system! 🚀 This project enables users to upload PDFs, ask questions about their content, and receive intelligent, context-aware answers — all while maintaining chat history. 📝✨

---

## 🌟 Key Features
- **PDF Uploads**: Effortlessly upload and process PDF documents. 📂
- **Contextual Q&A**: Get precise answers using context-aware retrieval and language models. 🤖
- **Chat History**: Keep track of your conversation for enhanced user experience. 🗂️
- **Custom LLM Support**: Utilize Groq API-powered Gemma2-9b-It for superior language understanding. 🌐
- **Streamlit Integration**: A user-friendly interface for seamless interactions. 🖥️

---

## 🛠️ Tech Stack
- **Language Model**: Gemma2-9b-It via Groq API 🔑
- **Frameworks**: 
  - Streamlit 📊
  - LangChain 🔗
- **Embedding Model**: HuggingFace `all-MiniLM-L6-v2` 🧠
- **Vector Database**: ChromaDB 🗄️
- **Document Processing**: LangChain's PyPDFLoader 📄
- **Chat History Management**: LangChain's `ChatMessageHistory` 🗨️
- **Environment**: Python 🐍

---

## 🚀 How It Works
1. **Upload PDFs**: Drag and drop your PDF files into the Streamlit app.
2. **Ask Questions**: Enter your queries related to the document's content.
3. **Get Answers**: Receive concise, context-aware answers based on the document and chat history.
4. **View History**: Access the chat history for reference or iterative questioning.

---

## 📦 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/conversational-rag-pdf.git
   cd conversational-rag-pdf
