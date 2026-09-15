# RAG Pipeline From Scratch

A hands-on implementation of a **Retrieval-Augmented Generation (RAG) pipeline** built step by step using Python.

This lab starts with a raw university policy document and demonstrates how to prepare the document, split it into chunks, generate embeddings, store them in a vector database, and retrieve relevant information using similarity search.

---

## 📌 Project Overview

The goal of this lab is to understand the core building blocks of a RAG system by implementing the retrieval process from scratch.

Instead of working with a large document as one piece, the pipeline transforms the knowledge base into searchable chunks and uses semantic similarity to retrieve the most relevant information for a query.

### 🔄 RAG Pipeline

```text
Raw Document
     ↓
Document Inspection
     ↓
Text Chunking
     ↓
Embeddings Generation
     ↓
Vector Database
     ↓
Similarity Search
     ↓
Relevant Chunks
```

---

## 🎯 Objectives

Through this lab, the following concepts are explored:

* Inspecting and understanding the structure of a document
* Counting and analyzing document sections
* Splitting long text into smaller chunks
* Creating text embeddings
* Storing embeddings in a vector database
* Performing similarity search
* Retrieving relevant chunks based on a query
* Understanding the fundamental workflow of a RAG system

---

## 📚 Knowledge Base

The project uses a fictional **University Academic Policy Document** as the knowledge base.

The document contains **7 chapters** covering:

1. Attendance Policy
2. Grading System
3. Examination Rules
4. Academic Integrity
5. Student Services and Support
6. Library and Research Facilities
7. Financial Policies

The document includes realistic university rules such as attendance requirements, grading scales, examination policies, academic integrity rules, student services, and financial policies.

---

## 🛠️ Technologies & Libraries

* **Python**
* **LangChain Text Splitters** — document chunking
* **Sentence Transformers** — text embeddings
* **ChromaDB** — vector database and retrieval
* **NumPy** — numerical operations
* **Scikit-learn** — similarity and machine learning utilities
* **tiktoken** — tokenization and token estimation

---

## 🧩 Exercises

The notebook contains **Exercises 1–7 + Bonus**, covering the main stages of the RAG retrieval workflow.

The exercises progressively build the pipeline from document inspection to retrieving relevant chunks through similarity search.

---

## 📂 Project Structure

```text
day1-rag-pipeline-from-scratch/
│
├── Day1_Lab_Notebook_Walaa_Omar_Hassan.ipynb
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/lool133/day1-rag-pipeline-from-scratch.git
```

### 2. Install the required libraries

```bash
pip install langchain-text-splitters sentence-transformers chromadb numpy scikit-learn tiktoken
```

### 3. Run the notebook

Open:

```text
Day1_Lab_Notebook_Walaa_Omar_Hassan.ipynb
```

and execute the cells step by step.

---

## 💡 Key Takeaways

This lab provides practical experience with the fundamental components behind modern **RAG applications**.

The main takeaway is understanding how unstructured text can be transformed into a searchable knowledge base through **chunking, embeddings, vector storage, and similarity-based retrieval**.

---

## 👩‍💻 Author

**Walaa Omar Hassan**

GitHub: [lool133](https://github.com/lool133)
