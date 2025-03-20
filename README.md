# Semantic Book Recommender 

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

- kagglehub
- pandas
- matplotlib
- seaborn
- python-dotenv
- langchain-community
- langchain-opencv
- langchain-chroma
- transformers
- gradio
- notebook
- ipywidgets

## Setup
1. API Keys & Environment Variables

- Create a .env file in the root directory.
- Add your OpenAI API key following the format provided in the repo.

2. Dataset

- The dataset is available on Kaggle. Instructions for downloading and setting it up are provided in the repository.

## Usage
Once the setup is complete, you can run the web application with:

```bash
python gradio-dashboard.py
```
This will launch an interactive interface where users can input natural language queries to receive personalized book recommendations.

## Future Enhancements

Planned improvements include:

- Expanding the dataset with more book metadata
- Improving classification with fine-tuned models
- Enhancing UI/UX for a more intuitive recommendation experience


This project demonstrates how LLMs and semantic search can be leveraged to build powerful recommendation systems. Contributions and feedback are welcome! 🚀









