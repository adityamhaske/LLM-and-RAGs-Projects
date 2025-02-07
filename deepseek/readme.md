## 📘 DocuMind AI  
**Your Intelligent Document Assistant**  

DocuMind AI is a **Streamlit-powered** web application that enables users to upload **PDF research documents** and ask questions about their content. It leverages **LangChain, Ollama Embeddings, and an LLM** to extract insights from the document and provide meaningful answers.  

---

### 🚀 Features  
✅ **Upload & Process PDFs** – Automatically loads and splits document content  
✅ **Intelligent Q&A** – Ask questions, get concise answers based on document context  
✅ **Vector Search** – Uses embeddings to find the most relevant document sections  
✅ **Customizable UI** – Dark-themed, modern chat interface with emoji support  
✅ **Fast & Efficient** – Uses in-memory vector search for quick responses  

### Create virtual environment
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate     # For Windows

### Install required libraries
pip install -r requirements.txt

Dependencies
Make sure you have the following Python packages installed:

- streamlit
- langchain
- langchain_community
- langchain_core
- langchain_ollama
- pdfplumber


streamlit run rag_deep.py


