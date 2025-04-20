# CiviCraft: GenAI for Participatory Governance

CiviCraft is a generative AI-powered civic assistant designed to make governance **transparent**, **interactive**, and **citizen-accessible**. This project was developed as part of the **Google x Kaggle Gen AI Intensive Capstone (2025Q1)**.

## Overview
Modern democracies face a paradox: more policy data than ever, but fewer engaged citizens. 

CiviCraft bridges this gap by enabling users to:
- Upload and understand complex policy documents
- Ask real-time questions about civic content
- Receive evaluations of policy arguments for fairness and clarity
- Explore civic data through semantic search

##  Key Features
- Document Upload**: `.txt` and `.pdf` support with PyPDF2
- **Summarization**: Gemini 1.5 Pro condenses complex policy documents
- **Argument Evaluation**: Assess fairness, clarity, and evidence with GenAI
- **RAG-style Semantic Search**: Hugging Face embeddings + FAISS
- **Real-Time Q&A**: Gemini 2.0 Flash answers civic questions instantly

## Tech Stack
- **Gemini 1.5 Pro**: Summarization and GenAI Evaluation
- **Gemini 2.0 Flash**: Real-time civic Q&A
- **SentenceTransformers (MiniLM)**: Embedding generation
- **FAISS**: Vector search engine
- **PyPDF2 + ipywidgets**: PDF parsing and file uploads
- **Python / Jupyter / Kaggle**: Notebook interface

## 📈 Use Case
Imagine a citizen uploads the Clean Air Act. CiviCraft:
- Summarizes the act in plain English
- Evaluates a claim like: "This act is unfair to industry"
- Answers questions like: "What pollutants are regulated?"
- Matches queries to policy content using embeddings

## Capabilities Demonstrated
-  Document Understanding
-  Function Calling
-  Agents
-  Long Context Windows
-  GenAI Evaluation
-  Embeddings
-  Retrieval-Augmented Generation (RAG)
-  Vector Search

## What's Next
- Multilingual summarization
- OCR support for scanned civic forms
- Voice interface and mobile deployment
- Integration into local civic platforms

##  Try It Out
- [Run on Kaggle](https://www.kaggle.com/code/chamander01/civiccraft)
- [Watch the demo video](https://www.youtube.com/watch?v=-D6BHrDJGMY)
- [Read the blog](https://medium.com/@bigbangygvip1/civic-craft-capstone-project-1f0cffd496a9)

## Contributing
Open to collaborators! Reach out via GitHub Issues or submit a pull request if you'd like to expand this project into a real-world civic tech tool.

