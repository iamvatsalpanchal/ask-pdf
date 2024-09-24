# 📚 Ask-PDF - RAG Streamlit Application
Open-source LLM-based PDF Chat streamlit application
This application allows you to upload PDF documents, create a knowledge base from their contents, and ask questions related to the content using a Retrieval-Augmented Generation (RAG) model. 
It provides concise answers based on the PDF's contents.

✨ Features
- 🗂️ Upload PDFs: Easily upload your PDF files to create a searchable knowledge base.
- 💾 Persistent Storage: Stores the PDF embeddings for later use.
- 🤖 Question Answering: Ask questions related to the content of the uploaded PDFs and receive concise answers generated by the AI model.
- 🛠️ Modular Design: Clean and modular code structure for easy maintenance and extension.

## About the App
This application allows you to upload PDF documents and create a knowledge base or vector store from them. 
You can then ask questions based on the content of the PDFs, and the app will provide concise answers using a Retrieval-Augmented Generation (RAG) model.

### How it Works
1. **Upload PDF**: Upload your PDF document using the uploader in the main section.
2. **Create Knowledge Base or Vector Store**: Click the 'Create Knowledge Base' button to process the PDF and store its contents as embeddings.
3. **Ask Questions**: Type your questions related to the content of the PDF, and get concise answers generated by the AI model.

### Key Features
- **Persistent Storage**: The embeddings of the PDF are stored persistently for later use.
- **Advanced AI**: Leverages state-of-the-art models for accurate question answering.
- **Modular Design**: The code is structured for easy maintenance and extension.


### 🔧 Environment Variables
Ensure you have the following environment variable configured in your .env file:

GROQ_API_KEY: Your Groq API key for accessing the language model.

### 📦 Dependencies
- Python 3.7+
- Streamlit 📖
- FAISS 🗂️
- LangChain 📘
- HuggingFace Instruct Embeddings 🤗
- PyPDF2
- Groq API 🧠
-- Other dependencies as listed in requirements.txt

### 📧 Contact
For any issues or feature requests, feel free to contact us at vatsalpanchal4488@gmail.com or call at 94275-16765.

### 🖼️ Screenshots
Add screenshots of your application in the screenshots/ directory and reference them in the README file where applicable.
