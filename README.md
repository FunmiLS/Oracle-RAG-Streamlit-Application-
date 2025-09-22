# Notes from Oracle Microservices Sandbox: Retrieval Augmented Generation Streamlit Application

> This repository showcases the personal notes and learnings from following Oracle Microservices Sandbox workshop. The application uses features from Oracle Database 23ai, like AI VectorSearch and SelectAI. The Sandbox helps users boost the performance of existing AI models.

> **No workshop code is included.** These are reflections and debugging logs.



---
## 📌 Why This Repo?
This repository was created to:
- Record our experience developing RAG applications while following the Oracle Microservices Sandbox Workshop.
- Share the different technologies used.
- Record challenges, debugging steps, and lessons learned.
- Provide a quick reference for anyone exploring RAG.

---
## 🚀 Oracle Microservices Sandbox Features

- 🔍 Document retrieval using vector search
- 🤖 LLM-based answer generation
- 🛠️ Configuring Embedding and Chat Models
- 🖼️ Interactive UI with Streamlit front-end
- 📁 Document ingestion and embedding
  
---

## 🔍 What is RAG?

**Retrieval-Augmented Generation (RAG)** is a powerful technique that enhances Large Language Models (LLMs) by grounding their responses in external data. It combines two key components:

- **Retriever** – Finds relevant information from your data sources.
- **Generator** – Uses that information to produce accurate, context-aware answers.

---

### ⚙️RAG Pipeline

1. **Ingest**  
Break documents into chunks, clean the text, and compute embeddings.

2. **Index**  
Store the embeddings in a vector database for efficient retrieval.

3. **Retrieve**  
Use similarity or hybrid search to find the top-k relevant chunks.

4. **Augment**  
Insert the retrieved context into the prompt sent to the LLM.

5. **Generate**  
The LLM produces a grounded response, with citations.


---

## 🛠️ Tech Stack
- **Python 3.11**
- **Cloud Platform**: Oracle Cloud Infrastructure (OCI)
- **Vector Store**: Oracle Database 23ai
- **Embeddings Model**: Cohere embed-english-light-v3.0
- **LLM**: Cohere command-r
- **Front End**: Streamlit

---

## 📦 Installation

Follow the instructions outlined in https://github.com/oracle/ai-optimizer

---
## 💾 Connect to Database

- In OCI, navigate to Autonomous Database > 'your database' > Database Connection.
- Select Database Connect and select Download Wallet
- Create a tns_admin folder in the src folder on your computer. Navigation: Oaim-sandbox > app > src
- Paste the wallet file in the tns_admin folder
- In the sandbox, open the database connection tab and insert your database user credientaisl, database string and wallet password


---

## 📸 Application Preview


<table align="center">
  <tr>
    <td>
      <img width="959" height="473" alt="image" src="https://github.com/user-attachments/assets/9259da00-1e40-475c-a7cf-d8e627ce5f74" />
      <p align="center"><strong>Language Models</strong></p>
    </td>
    <td>
     <img width="959" height="512" alt="image" src="https://github.com/user-attachments/assets/dc9d5155-8340-4d0e-ae6a-cdf2d64681d7" />
      <p align="center"><strong>Emedding Models</strong></p>
    </td>
  </tr>
  <tr>
    <td>
      <img width="959" alt="image (2)" src="https://github.com/user-attachments/assets/48b0ba1a-e10f-4671-b715-474315b30eb1" />
      <p align="center"><strong>Chatbot UI</strong></p>
    </td>
    <td>
      <img width="959" alt="image (2)" src="https://github.com/user-attachments/assets/ed9fe5a8-475e-4b4d-a206-bb8c333044a2" />
      <p align="center"><strong>Embeddings in Oracle Database</strong></p>
    </td>
  </tr>
  
</table>

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

