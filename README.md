# Synapse-GPT: The Télécom Paris AI Assistant

---

This chatbot is a work in progress. It works, but I am not satisfied enough to make it publicly available. It mainly acts as a way for me to learn more about RAGs.

---

A LLM that can answer questions about life, courses, and history at **Télécom Paris**. This project uses a Retrieval-Augmented Generation (RAG) pipeline, using the **Mistral AI API** and a custom knowledge base scraped from official sources.

The goal is to provide a single, reliable source of truth for students, centralizing information that is otherwise scattered across multiple platforms (and often quite well hidden...) .

---

## ⚙️ How It Works: The RAG Architecture

This project follows a classic RAG pipeline, broken down into two main stages: **Data Indexing** and **Inference**.

### 1. Data Indexing (Offline)
1.  **🌐 Scrape Data:** A Python script using `BeautifulSoup` crawls and extracts text from:
    *   The official **Télécom Paris website** (`telecom-paris.fr`)
    *   The **Télécom Paris Wikipedia page**
    *   All public-facing **Synapse** course and community pages.
2.  **✂️ Chunk Data:** The raw text is cleaned and split into smaller, semantically meaningful chunks.
3.  **🧠 Generate Embeddings:** Each chunk is converted into a vector embedding.
4.  **💾 Store in Vector DB:** The chunks and their corresponding embeddings are stored and indexed in a local vector database (e.g. FAISS ) for efficient similarity search.

### 2. Inference (Real-time Q&A)
1.  **❓ User Query:** The user asks a question (e.g., "What are the requirements for the 3D Data Science option?").
2.  **🔍 Retrieve Relevant Chunks:** The user's query is embedded, and a similarity search is performed against the vector database to find the most relevant text chunks from the knowledge base.
3.  **💬 Augment Prompt & Generate:** The retrieved chunks are combined with the original query into a detailed prompt. This augmented prompt is sent to the **Mistral AI API**.
4.  **✅ Get Answer:** The Mistral model uses the provided context to generate a coherent, accurate, and sourced answer.

---

## 🔮 Future Improvements

-   [ ] **Inference Code**: Give access to the inference code (it's a mess at the moment)
---

### Disclaimer

This is a personal project and is not an official tool of Télécom Paris. The information provided is based on publicly available data and may not always be 100% accurate or up-to-date.
