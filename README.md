# news_sentiment_tts

# News Sentiment & Hindi TTS App

## Overview
A web app that extracts news articles about a company, performs sentiment analysis, and generates a Hindi TTS summary.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourrepo/news-sentiment-tts.git
   cd news-sentiment-tts
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Application
### Step 1: Start the API Backend
```
uvicorn api:app --host 0.0.0.0 --port 8000
```

### Step 2: Run the Streamlit Frontend
```
streamlit run app.py
```

## Deployment on Hugging Face Spaces
1. Push your repository to GitHub.
2. Create a **Hugging Face Space** and select **Streamlit** as the framework.
3. Link your GitHub repository and deploy!
