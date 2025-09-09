# 🧠 Oracle-RAG-Streamlit-Application

This repository showcases a demo implementation of a **Retrieval-Augmented Generation (RAG)** application. It combines document retrieval with large language model (LLM) generation to provide accurate, context-aware responses based on external knowledge sources.

---

## 🚀 Features

- 🔍 Document retrieval using vector search in Oracle Autonomous Database 23ai
- 🤖 LLM-based answer generation using OCI Generative AI service
- 🖼️ Interactive UI with Oracle APEX
- 📁 Document ingestion and embedding in Oracle Autonomous Database 23ai

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Streamlit**

---

## 📦 Installation




---

## 📸 Demo Preview



---
## 🐞 Known Issues & Bugs

We discovered a few issues and bugs with the application when following the demo tutorial. The known issues and bugs are found below:

- **Retrieval inconsistencies**: Occasionally, the retriever may return irrelevant or low-quality documents, especially when queries are ambiguous or under-specified.
- **Latency**: Response times may be slower than expected due to the size of the document corpus and model inference time.
- **Context window limitations**: Large retrieved documents may be truncated or omitted if they exceed the model’s context window.
- **Error handling**: Some edge cases (e.g., empty queries, malformed inputs) may not be gracefully handled yet.
- **UI/UX quirks**: If you're using a frontend, you might notice minor layout or interaction issues depending on the browser.

---

## 📄 License

This project is licensed under the MIT License.
