# 🚀 Modular RAG (Retrieval-Augmented Generation) Pipeline

This project demonstrates the evolution of a **RAG system**, starting from a core Java implementation to a sophisticated, multi-stage Python pipeline.

## 📌 Project Overview
The system is designed to provide accurate answers to user queries by retrieving relevant information from a JSON-based knowledge base and processing it through various ranking stages.

## 🛠 Evolution Stages

### Phase 1: Java Implementation (The Core)
* **Objective:** Building the foundation of document retrieval.
* **Functionality:** Developed a system that parses **JSON data**, matches user queries with the most relevant information using keyword similarity, and returns the best-fit response.
* **Key Focus:** Robust data structure design and core retrieval logic.

### Phase 2: Python Migration
* **Objective:** Leveraging the Python AI ecosystem for scalability.
* **Action:** Ported the core logic to Python to integrate advanced Natural Language Processing (NLP) libraries and improve processing speed.

### Phase 3: Advanced Optimization (Current State)
* **New Features:** Implemented a **Two-Stage Retrieval** architecture.
* **Re-ranker Integration:** Added a second-stage **Re-ranker** in Python to evaluate the initial results more deeply, ensuring the highest possible answer quality.
* **Modular Design:** Components like `Retriever`, `Re-ranker`, and `QueryWriter` are decoupled for easier maintenance and testing.

## 📂 Project Structure
* `/java-version`: Initial core retrieval logic and JSON parsing.
* `/python-version`: Final optimized pipeline with re-ranking and AI capabilities.

## 🧰 Technologies Used
* **Languages:** Java, Python
* **Data Format:** JSON
* **Concepts:** RAG, Document Retrieval, Re-ranking, OOP, NLP.
