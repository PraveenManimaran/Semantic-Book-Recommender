# Semantic Book Recommender with LLMs  

This repository contains the code for a **Semantic Book Recommender**, an AI-powered system that recommends books based on natural language queries. The system leverages **large language models (LLMs)** and **vector search** to provide book recommendations based on themes, emotions, and classifications.  

## Features  

This project includes five main components:  

- **Text Data Cleaning**: Preprocessing book descriptions to improve the quality of semantic search (`data-exploration.ipynb`).  
- **Semantic (Vector) Search**: Creating a vector database to find books most similar to a given query (e.g., "a book about a person seeking revenge") (`vector-search.ipynb`).  
- **Zero-Shot Text Classification**: Categorizing books as "fiction" or "non-fiction" using LLM-based classification (`text-classification.ipynb`).  
- **Sentiment & Emotion Analysis**: Extracting emotions from text to sort books by tone (e.g., suspenseful, joyful, sad) (`sentiment-analysis.ipynb`).  
- **Interactive Web Application**: A user-friendly interface built with **Gradio** for easy book discovery (`gradio-dashboard.py`).  

## Installation  

This project was developed in **Python 3.11**. To install the required dependencies, use:  

```bash
pip install -r requirements.txt
```

## Dependencies

The project relies on the following libraries:

kagglehub
pandas
matplotlib
seaborn
python-dotenv
langchain-community
langchain-opencv
langchain-chroma
transformers
gradio
notebook
ipywidgets
