# AI-Powered Financial News Sentiment Analysis

This project uses **Natural Language Processing (NLP)** to analyze the sentiment of financial news articles. The sentiment analysis helps to identify whether the tone of the article is **positive** or **negative**, enabling better market decision-making.

## Key Features

- **Sentiment Analysis**: Classifies financial news articles into positive, neutral, or negative sentiment.
- **Automated Data Pipeline**: Scrapes and processes financial news from online sources.
- **Real-time Sentiment Visualization**: Display sentiment trends dynamically.
- **Cloud Deployment**: Deployed on **AWS Lambda** for scalable, on-demand access.

## Tools and Technologies

- **Python**: Programming language used for developing the sentiment analysis model.
- **Hugging Face Transformers**: Pre-trained models for sentiment analysis.
- **AWS Lambda**: Cloud platform for serverless deployment.
- **Streamlit**: For creating a simple real-time dashboard (optional for visualization).

## Installation

### Prerequisites
Make sure you have **Python 3.x** installed. Then, you can install the required libraries using:

```bash
pip install transformers
pip install streamlit  # Optional if you want the dashboard
pip install newspaper3k  # Optional for scraping financial news
