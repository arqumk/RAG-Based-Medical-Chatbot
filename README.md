# 🤖 Transforming Healthcare Accessibility with a RAG-Based Medical Chatbot

> **Role:** Data Scientist  
> **Client:** U.S.-based Healthcare Organization  
> **Date:** December 25, 2024

---

![Pipeline Overview](./pipeline.png)

---

## 🩺 Project Overview

In today’s fast-paced world, accessing accurate and timely medical information is critical. Our client sought to revolutionize patient interaction with medical data by deploying a **Retrieval-Augmented Generation (RAG)**-based chatbot that delivers precise, context-aware responses — all while ensuring regulatory compliance and a smooth user experience.

---

## 🚧 Key Challenges

1. Extracting accurate answers from a large corpus of unstructured PDF documents  
2. Handling contextual follow-up queries within conversations  
3. Ensuring full compliance with HIPAA and data protection policies  
4. Supporting multilingual interactions for a diverse user base  

---

## 🔍 Our Approach

- **📚 Dynamic Response Generation**  
  Used **LangChain** with the **OpenAI API** for generating coherent, context-sensitive responses.

- **🧠 Smart Retrieval Layer**  
  Indexed medical documents using **Pinecone vector DB** and improved relevance with **MMR re-ranking**.

- **🖥️ Frontend Interface**  
  Designed an interactive UI using **Streamlit** for easy patient interaction.

- **☁️ Cloud Deployment**  
  Deployed securely on **Azure App Services**, enabling scalable and global availability.

---

## ✅ Results

- ⏱️ Delivered precise answers in under 2 seconds  
- 📉 Reduced redundant questions to healthcare staff  
- 🌍 Boosted multilingual accessibility and trust  
- 🔒 Ensured complete data security and compliance  

---

## 🛠 Tech Stack

| Component     | Tool / Framework         |
|--------------|--------------------------|
| LLM API      | OpenAI (GPT-3.5)         |
| Framework    | LangChain                |
| Vector Store | Pinecone                 |
| UI           | Streamlit                |
| Deployment   | Azure App Services       |
| Embedding    | `text-embedding-3-small` |

---

## 🎯 Highlights

- ✅ Extracted & chunked thousands of PDF documents
- 💬 Enabled intelligent follow-up questioning
- 🌐 Implemented multilingual support (EN, ES, UR)
- 📊 Improved patient query resolution speed by >60%

---

> **Note**: The code for this project is confidential and owned by the client. This repository documents the architecture, methodology, and outcomes only.
