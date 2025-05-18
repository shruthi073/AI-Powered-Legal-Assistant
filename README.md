
# 🧑‍⚖️ AI-Powered Legal Assistant

An AI-based legal assistant designed to simplify legal document creation and provide accurate, real-time responses to legal queries using Natural Language Processing (NLP), Machine Learning (ML), and vector-based search techniques. This tool improves accessibility to legal information, supports legal literacy, and enables low-cost, efficient legal documentation for individuals and small businesses.

---

## 📌 Overview

Legal processes are often complex, expensive, and inaccessible to the general public. This project introduces an AI-powered chatbot capable of:

- Interpreting legal queries in natural language
- Extracting relevant information from legal documents (specifically, the Constitution of India)
- Generating simplified, structured legal responses
- Creating legally sound documents through user inputs and predefined templates

---

## 🛠️ Key Features

- **Conversational AI Interface**: A chatbot built with Python and `ipywidgets`, hosted on Google Colab.
- **Document Retrieval System**: Uses structured dictionaries and vector similarity to match user queries with legal articles.
- **Static Knowledge Base**: Based on a structured, preprocessed version of the Constitution of India.
- **Real-time Interaction**: Users receive immediate responses to legal queries in an easy-to-understand format.
- **Data Privacy**: No user-uploaded documents or personal data is stored or processed.

---

## ⚙️ Architecture

The system follows a modular 5-phase pipeline:

### 1. Data Collection & Preprocessing
- Static dataset: Constitution of India (text format)
- Cleaning: Removal of punctuation, stopwords, special characters
- Text structuring: Article-wise key-value mapping using Python dictionaries and DataFrames

### 2. Embedding & Vector Indexing
- Embeddings: Generated using HuggingFace Transformers
- Dimensionality Reduction: PCA
- Indexing: FAISS / HNSWLib for approximate nearest neighbor search

### 3. AI Model & Logic
- Rule-based keyword mapping
- Context-aware query matching
- Embedding similarity for ranked retrieval

### 4. Chatbot Interface
- Built with `ipywidgets` in Google Colab
- Session history, reset button, dynamic response formatting
- Interactive query-response loop


---

## 💻 Tech Stack

| Category         | Tools / Libraries                                 |
|------------------|--------------------------------------------------|
| Language         | Python                                            |
| NLP              | spaCy, NLTK, HuggingFace Transformers             |
| Vector Search    | FAISS, HNSWLib                                    |
| UI               | Google Colab + ipywidgets                         |
| Data Handling    | Pandas, NumPy                                     |
| Parsing PDFs     | PyMuPDF (Fitz)                                    |
| ML Tools         | scikit-learn (for PCA and preprocessing)          |

---

## 🎯 Project Objectives

- **Simplify legal language** using NLP techniques
- **Automate document drafting** for common legal formats
- **Bridge legal accessibility gaps** for individuals and small businesses
- **Validate legal content** against existing statutes and frameworks
- **Educate users** on fundamental rights, duties, and laws

---

## 📊 Outcomes

- Improved legal literacy among non-experts
- Automated generation of legally compliant documents
- Accurate legal query response system
- User-friendly chatbot accessible through web interface
- Secure, lightweight, and scalable architecture

---

