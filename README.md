# AI Powered Notes Summarizer and Question Answering System Using RAG and CAG

\<p align="center">
&#x20; \<b>An AI-powered study assistant that summarizes academic notes and answers student questions using Retrieval-Augmented Generation (RAG) and Cache-Augmented Generation (CAG).\</b>
\</p>

---

## 📌 Project Overview

The AI Powered Notes Summarizer and Question Answering System is designed to help students understand and revise their study materials easily.

Users can upload PDF and TXT documents, generate AI-powered summaries, and ask questions based on their uploaded notes.

The system uses RAG to retrieve relevant information from uploaded documents and CAG to cache previously generated answers and reduce repeated API requests.

## ✨ Key Features

- 📄 PDF and TXT document upload.
- 📚 Multiple document processing.
- 📝 AI-powered short and detailed summaries.
- 🔑 Important key points and topics extraction.
- 🎓 Exam preparation notes generation.
- 💬 Interactive question answering.
- 🔍 FAISS-based semantic search.
- 🧠 Retrieval-Augmented Generation (RAG).
- ⚡ Cache-Augmented Generation (CAG).
- 📌 Source document and page number references.
- 📊 Cache statistics and API usage status.
- 🖥️ Interactive Gradio interface.

## 🛠️ Technology Stack

| Technology              | Purpose                          |
| ----------------------- | -------------------------------- |
| Python                  | Programming Language             |
| Google Colab            | Development Environment          |
| Navigate Labs Nexus API | LLM API Provider                 |
| RAG                     | Context-based Question Answering |
| CAG                     | Answer Caching                   |
| FAISS                   | Vector Database                  |
| Sentence Transformers   | Text Embeddings                  |
| PyMuPDF                 | PDF Text Extraction              |
| Gradio                  | Interactive User Interface       |

## 🏗️ System Workflow

1. Upload PDF or TXT study materials.
2. Extract and preprocess document text.
3. Split documents into meaningful chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in the FAISS vector database.
6. Retrieve relevant chunks when a question is submitted.
7. Send the retrieved context to Navigate Labs Nexus API.
8. Generate context-based AI answers.
9. Cache generated answers for repeated questions.
10. Display answers with source references.

## 🧠 RAG Implementation

Retrieval-Augmented Generation retrieves relevant information from uploaded study materials before generating an answer.

**RAG Workflow:**

Document Upload → Text Extraction → Chunking → Embeddings → FAISS Search → Nexus API → AI Answer

## ⚡ CAG Implementation

Cache-Augmented Generation stores previously generated answers and reuses valid cached responses.

**CAG Workflow:**

User Question → Cache Check → Cache HIT / Cache MISS → Answer Generation → Cache Storage

This helps reduce unnecessary repeated API calls.

## 🤖 AI Summarization

The system supports:

- Short Summary
- Detailed Summary
- Important Key Points
- Important Topics
- Exam Preparation Notes
- Easy-to-Understand Study Notes

## 💻 Installation and Execution

This project is designed to run in Google Colab.

**Step 1:** Download or clone this repository.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

**Step 2:** Open Google Colab.

[https://colab.research.google.com/](https://colab.research.google.com/)

**Step 3:** Upload and open the notebook:

`AI_Notes_Summarizer_RAG_CAG.ipynb`

**Step 4:** Configure your college-provided Navigate Labs Nexus API key securely using Google Colab Secrets or the notebook's secure input.

**Step 5:** Execute the notebook cells in order.

**Step 6:** Upload your PDF or TXT notes and start using the application.

## 🔐 API Configuration

This project uses Navigate Labs Nexus API as its LLM provider.

**Base URL:**

`https://nexusapi.navigatelabs.ai`

API credentials must be entered securely.

Never upload API keys or private credentials to GitHub.

## 📂 Project Structure

```text
AI_Notes_Summarizer_RAG_CAG/
│
├── AI_Notes_Summarizer_RAG_CAG.ipynb
│
├── diagrams/
│
├── implementation_screenshots/
│
└── README.md
```

## 🎯 Project Objectives

- Simplify academic note preparation.
- Reduce manual reading time.
- Generate understandable study summaries.
- Provide context-based answers from uploaded documents.
- Improve repeated question response efficiency through caching.
- Help students prepare for examinations.

## 🔮 Future Enhancements

- Support for additional document formats.
- Improved semantic retrieval.
- Multilingual summarization.
- Advanced document search.
- Enhanced caching strategies.

## 👩‍💻 Author

**Hari Triya A**

## 📜 License

This project is developed for educational and academic purposes.

---

\<p align="center">   \<b>AI Powered Notes Summarizer and Question Answering System Using RAG and CAG\</b>   \<br>   Built with Python, Google Colab, Nexus API, RAG, CAG and Gradio. \</p>
