# 🎥 YouTube Video Q&A System (RAG + LangChain + Anthropic)

An AI-powered **Retrieval-Augmented Generation (RAG)** application that converts any YouTube video into an interactive knowledge source. Provide a **YouTube video ID**, and the system summarizes the video and answers questions based strictly on its content.

This project combines **LLMs, embeddings, and semantic search** to deliver accurate, context-aware answers.

---

## 🚀 Features

✅ YouTube transcript extraction  
✅ AI-generated video summaries  
✅ Natural language Q&A  
✅ Semantic search using embeddings  
✅ Context-grounded responses (low hallucination)

---

## 🧠 Tech Stack

| Component      | Technology              |
|---------------|-------------------------|
| LLM           | Anthropic Claude API    |
| Framework     | LangChain               |
| Embeddings    | Vector Embeddings       |
| Vector Store  | FAISS / Chroma          |
| Language      | Python                  |

---

## ⚙️ System Workflow

```text
YouTube Video ID
        ↓
Transcript Extraction
        ↓
Text Chunking
        ↓
Embedding Generation
        ↓
Vector Database Storage
        ↓
User Question
        ↓
Relevant Chunk Retrieval
        ↓
Claude LLM Response
