# Notes from Oracle Microservices Sandbox: Retrieval Augmented Generation Streamlit Application

> This repository showcases the personal notes and learnings from following Oracle Microservices Sandbox workshop. The application uses features from Oracle Database 23ai, like AI VectorSearch and SelectAI. The Sandbox helps users boost the performance of existing AI models.

> **No workshop code is included.** These are reflections and debugging logs.



---

## 🚀 Features

- 🔍 Document retrieval using vector search
- 🤖 LLM-based answer generation
- 🛠️ Configuring Embedding and Chat Models
- 🖼️ Interactive UI with Streamlit front-end
- 📁 Document ingestion and embedding
  
---

## 🛠️ Tech Stack
- Python 3.11
- **Cloud Platform**: Oracle Cloud Infrastructure (OCI)
- **Vector Store**: Oracle Database 23ai
- **Embeddings Model**: Cohere embed-english-light-v3.0
- **LLM**: Cohere command-r
- **Front End**: Streamlit

---

## 📦 Installation

Follow the instructions outlined in https://github.com/oracle/ai-optimizer


---

## 📸 Application Preview

### Language Models
<img width="959" height="473" alt="image" src="https://github.com/user-attachments/assets/9259da00-1e40-475c-a7cf-d8e627ce5f74" />

### Embedding Models

<img width="959" height="512" alt="image" src="https://github.com/user-attachments/assets/dc9d5155-8340-4d0e-ae6a-cdf2d64681d7" />

### Chatbot UI

![RAG_UI](https://github.com/user-attachments/assets/48b0ba1a-e10f-4671-b715-474315b30eb1)


### Embeddings in Oracle Database

<img width="959" alt="image (2)" src="https://github.com/user-attachments/assets/ed9fe5a8-475e-4b4d-a206-bb8c333044a2" />


---
## ⚠️ Challenges & Debugging Log

We discovered a few issues and bugs with the application when following the demo tutorial. The known issues and bugs are found below:

- **Open AI Credits**: If you choose to use OpenAI's free tier account, you will likely run out of credits quickly to generate embeddings and interact with the chat models.
- **Packages**: Some of the required packages are not running the latest versions. We advise manually installing the older versions to get the app to run.


---

## 📄 License

This project is licensed under the MIT License.

## 👥 Authors

- **FunmiLS & 4Khan** 

