🎓 RAG-Based University Assistant Chatbot

An intelligent AI-powered chatbot designed to assist university students by answering their queries using uploaded documents. This system leverages Retrieval-Augmented Generation (RAG) along with Google Gemini API to provide accurate, context-aware responses directly from PDF-based knowledge sources.

📌 Project Overview

This chatbot was developed as a semester project to address a common issue faced by students — repeatedly asking the same questions across platforms like WhatsApp, Instagram, and YouTube.

The solution automates responses by retrieving relevant information from university documents and generating precise answers, reducing manual effort and improving accessibility.

🎯 Project Goal

Students often struggle to find accurate information quickly. This project aims to:

Provide instant, automated responses to student queries
Reduce repetitive questioning across multiple platforms
Improve access to important university-related information
Deliver a smart, AI-driven assistance system

📊 Data Collection Methodology

To ensure the chatbot provides reliable and relevant answers:

🌐 Collected FAQs from 20+ university websites in Pakistan
📝 Gathered real student queries through Google Forms
📄 Combined all data into a single structured PDF document
📚 Used this PDF as the primary knowledge base for the chatbot

🚀 Key Features
📂 Upload university-related PDF files (e.g., FAQs, brochures, admission guides)
🔍 Intelligent document processing and understanding
✂️ Splits documents into smaller chunks for better retrieval
🧠 Converts text into embeddings for semantic search
🎯 Retrieves the most relevant information based on user queries
💬 Generates concise and accurate answers using Google Gemini AI
🌐 Simple and interactive web interface built with Streamlit

⚙️ Tech Stack
Programming Language: Python
Frameworks & Libraries:
LangChain
Streamlit
PDFPlumber
NumPy
scikit-learn
AI & APIs:
Google Gemini API
Concept Used:
Retrieval-Augmented Generation (RAG)

🧠 How It Works
📥 Upload a PDF document (e.g., university FAQs)
📖 The system reads and processes the document
✂️ Content is split into smaller chunks
🔎 Each chunk is converted into embeddings for efficient search
❓ User asks a question (e.g., "What documents are required for NTS?")
📌 The system retrieves the most relevant chunks
🤖 Gemini AI generates a clear and concise answer based on retrieved data

🛠️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/SohaibBazaz/rag-university-chatbot.git
cd rag-university-chatbot
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the Application
streamlit run University_Assistant.py
