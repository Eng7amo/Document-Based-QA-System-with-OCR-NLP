# AI-Powered QA Chatbot with OCR & NLP  

This repository contains an **AI-powered Question-Answering (QA) chatbot** that extracts text from **PDFs and images** using **OCR (Optical Character Recognition)** and processes queries using **Neural Networks**. The system leverages **transformers, sentence embeddings, and vector databases** to provide intelligent responses.

## 🚀 Features  
- **OCR Support:** Extracts text from images and PDFs using Tesseract & pdf2image.  
- **NLP-Based QA:** Uses Transformer models for question answering.  
- **Vector Search for Context Matching:** Utilizes FAISS and Pinecone for efficient retrieval.  
- **Scalable & Fast Processing:** Optimized for large document-based QA.  

## 📂 Project Structure  
📁 AI_QA_Chatbot │── 📜 QA_Chatbot.ipynb # Main Jupyter Notebook │── 📜 requirements.txt # Dependencies list │── 📜 README.md # Project documentation │── 📁 data/ # PDF & image files for OCR processing │── 📁 models/ # Pretrained models for NLP │── 📁 embeddings/ # Saved vector embeddings

bash
Copy
Edit

## 📌 Installation  
### 1️⃣ Clone the repository  
git clone https://github.com/yourusername/AI_QA_Chatbot.git
cd AI_QA_Chatbot
### 2️⃣ Create a virtual environment (optional but recommended)
bash
Copy
Edit
python -m venv chatbot_env
source chatbot_env/bin/activate  # On Windows: chatbot_env\Scripts\activate
### 3️⃣ Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
### 🛠 Usage
Run the Jupyter Notebook
bash
Copy
Edit
jupyter notebook
Open QA_Chatbot.ipynb and execute the cells to extract text, generate embeddings, and interact with the chatbot.

### 🔍 How It Works
Extracts text from PDFs and images using Tesseract OCR & pdf2image.

Converts text into vector embeddings using Sentence Transformers.

Stores and retrieves relevant context using FAISS/Pinecone vector database.

Answers user queries using a pretrained Transformer model (e.g., BERT, GPT).

### 📊 Model & Training
Uses Sentence Transformers for sentence embeddings.

Pretrained QA models (Huggingface Transformers) for answering questions.

Vector search powered by FAISS/Pinecone for fast retrieval.

🤝 Contribution
Feel free to contribute by creating pull requests or reporting issues in the Issues section.
