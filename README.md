# 🤖 RAREbot: Development of an NLP system: thematic analysis, automatic summarization, and RAG

This repository contains the source code and resources for the Master's Thesis project titled **“Development of a chatbot specialized in rare diseases using Retrieval-Augmented Generation (RAG) techniques”**, developed by Ignacio Hernández Bas in collaboration with **newsRARE**, a Spanish magazine focused on rare diseases.

## Project Overview

The goal of this project is to democratize access to high-quality medical information on **rare diseases** using cutting-edge **Natural Language Processing (NLP)** techniques. This includes **topic modeling**, **automatic summarization**, and a **question-answering chatbot** based on **Retrieval-Augmented Generation (RAG)**. The system has been trained and evaluated on a real-world dataset built from *newsRARE* articles.

## System Architecture

The project is divided into four main modules:

1. **Web Scraping & Data Processing**  
   Automated extraction and preprocessing of articles from [newsRARE.es](https://www.newsrare.es).

2. **Topic Modeling**  
   Grouping of articles by topic using NMF, with interactive visualizations using t-SNE and Plotly.

3. **Automatic Summarization**  
   Generation of summaries using both general and biomedical models, followed by quantitative and qualitative evaluation.

4. **RAG-based Chatbot**  
   A question-answering system combining retrieval (ChromaDB + sentence embeddings) and generative models (Flan-T5 and BioGPT) via LangChain.

## Technologies Used

- **Python** (main language)
- **Transformers**: Flan-T5, BioGPT, BioGPT-Large
- **LangChain** and **ChromaDB**
- **NLTK**, **spaCy**, **Scikit-learn**
- **Gradio** (for UI)
- **t-SNE**, **Plotly**,
- **Google Colab**, **Hugging Face**

## Evaluation Metrics

Multiple evaluation strategies have been applied:

- **Summarization**: BERTScore
- **Answer Quality with generated Q/A(dataset)**: Cosine Similarity, BERTScore-F1, ROUGE-L
- **Comparisons** across different embedding models (`bge-m3`, `MiniLM`) and generative models (`Flan-T5`, `BioGPT`, etc.)
- **Robustness Testing**: in-domain vs out-of-domain question sets


## Chatbot interface

![image](https://github.com/user-attachments/assets/0ca6a882-eb0a-4c34-b828-6fbbcd173e1b)


## Project Report

This work was developed as part of the Master's in Big Data & Advanced Analytics at **Universidad Pontificia Comillas (ICAI)**. The full thesis report is available [here (PDF, Spanish)](https://github.com/user-attachments/files/20847514/TFM_HernandezBasIgnacio.pdf).
English Summary [here](https://github.com/user-attachments/files/20847544/Resumen.Ingles.Acabado.pdf)


## Author

**Ignacio Hernández Bas**  
📧 ignaciohernandezbas@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/ignaciohernandezbas/)  
🎓 Universidad Pontificia Comillas – ICAI  
---
