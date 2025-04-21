# 📚 Semantic Book Recommender with LLMs

This repository contains all the code to  **"Build a Semantic Book Recommender with LLM"** It combines modern NLP techniques, vector search, zero-shot classification, and sentiment analysis to build an intelligent book recommendation system.

---

## 🚀 Project Overview

This project demonstrates how to build an LLM-powered semantic book recommender system with five core components:

### 1. 🧹 Text Data Cleaning
- **Notebook**: `data-exploration.ipynb`
- Preprocesses and cleans the raw book metadata to prepare it for downstream tasks like vectorization and classification.

### 2. 🔍 Semantic Search with Vector Database
- **Notebook**: `vector-search.ipynb`
- Builds a vector database to perform **semantic search** — allowing users to query books with natural language (e.g., *"a story about revenge"*).

### 3. 🏷️ Zero-Shot Text Classification
- **Notebook**: `text-classification.ipynb`
- Uses LLMs for **zero-shot classification** to categorize books into **Fiction** or **Non-Fiction**, enabling filterable recommendations.

### 4. 💬 Sentiment & Emotion Analysis
- **Notebook**: `sentiment-analysis.ipynb`
- Performs sentiment and emotion extraction (e.g., suspenseful, joyful, sad) to help sort and recommend books by tone.

### 5. 🖥️ Gradio Web Application
- **Script**: `gradio-dashboard.py`
- A sleek Gradio interface that lets users:
  - Search books semantically
  - Filter by genre or tone
  - View recommended titles and metadata

---

## 🛠️ Setup Instructions

> **Python Version**: `3.11` recommended.


