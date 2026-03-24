Modular RAG Pipeline

Project Overview
This project focuses on building a Retrieval-Augmented Generation system. It started with a Java implementation for core retrieval and evolved into a multi-stage Python pipeline for better performance and AI integration.

Development Stages

Phase 1: Java Core
The initial version was built in Java to handle document retrieval from JSON data. It parses user queries and matches them with relevant information using keyword similarity to return the most accurate response.

Phase 2: Python Migration
The core retrieval logic was ported to Python to take advantage of the AI ecosystem and libraries. This migration improved the processing speed and allowed for more complex data handling.

Phase 3: Advanced Re-ranking
A second-stage re-ranker was added to the Python pipeline. This ensures higher accuracy by re-evaluating the initial search results. The system is designed with modular components like Retriever and Re-ranker for easier maintenance.

Project Structure
/java-version: Core retrieval and JSON parsing logic.
/python-version: Final pipeline with re-ranking and AI capabilities.

Technologies
Languages: Java, Python
Data: JSON
Key Concepts: RAG, Document Retrieval, Re-ranking, OOP
