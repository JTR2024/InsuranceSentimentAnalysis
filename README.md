# Insurance
# SentimentAnalysis

A Generative AI-powered sentiment analysis tool for insurance discussions using GPT-4o and RAG.

## Overview

This project demonstrates an end-to-end NLP and Generative AI solution for analyzing insurance-related discussions, using synthetic data that mimics typical customer feedback about insurance products and services.

## Key Features

- **Synthetic Data Generation** - Creates realistic insurance discussion data
- **Data Preprocessing** - Cleans and prepares text for analysis
- **GPT-4o Sentiment Analysis** - Classifies comments as positive, negative, or neutral
- **Retrieval-Augmented Generation** - Answers queries using relevant context from the dataset
- **Data Visualization** - Presents insights through charts and an HTML dashboard

## Project Structure

```
notebooks/                  # Step-by-step implementation
data/                       # Generated datasets and visualizations
insurance_dashboard.html    # Visual summary of findings
```

## Implementation Steps

1. **Environment Setup** - Configuration and dependency installation
2. **Data Generation** - Creation of synthetic insurance comments dataset
3. **Data Preprocessing** - Cleaning, EDA, and feature extraction
4. **Sentiment Analysis** - GPT-4o-based classification with rationales
5. **RAG Implementation** - Building a retrieval system for context-aware responses
6. **Visualization** - Creating charts and dashboard to present findings

## Technologies

- Python, Pandas, NumPy
- OpenAI API (GPT-4o)
- Matplotlib, Seaborn, WordCloud
- TF-IDF for retrieval implementation

## Getting Started

1. **Clone the repository**
2. **Install dependencies:**
   ```
   pip install openai pandas matplotlib seaborn wordcloud scikit-learn
   ```
3. **Set your OpenAI API key:**
   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your-api-key-here"
   ```
4. **Run the notebooks in sequence** (Steps 1-6)

## Future Enhancements

- Replace synthetic data with real customer feedback
- Implement multi-class or aspect-based sentiment analysis
- Create an interactive Streamlit dashboard
- Fine-tune models on insurance-specific language
