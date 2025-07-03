# Echoes Of Emotions : Sentiment-analysis-project
This is a project description for "Echoes of Emotion", a sentiment analysis project that focuses on Amazon food reviews. Here's a breakdown of the key points:

*Project Goal:* Analyze the sentiment of Amazon food reviews using various techniques.

## Techniques Used:
1. VADER (rule-based sentiment analysis)

## Key Features:
1. Process large dataset of Amazon food reviews
2. Apply text preprocessing techniques:
    - Word tokenization
    - Part of speech tagging
    - Named entity recognition
3. Compare performance of VADER  in sentiment classification

## Implementation Details:
1. Programming language: Python
2. Libraries used:
    - NLTK
    - Scikit-learn

## Setup Instructions:
1. Create a virtual environment and activate it:
   ```
   python -m venv venv
   venv/Scripts/activate
   ```
2. Install required dependencies using pip:
   ```
   pip install pandas nltk python-dotenv
   ```
3. Download necessary NLTK packages:
   ```
   python -m nltk.downloader vader_lexicon
   ```
4. Download Amazon food reviews dataset from Kaggle and place it in the appropriate directory


## Running the Streamlit Interface

To run the Streamlit interface for sentiment analysis and summary generation:

1. Install Streamlit if not already installed:
   ```
   pip install streamlit
   ```
2. Run the Streamlit app:
   ```
   streamlit run streamlit_app.py
   ```
3. Enter customer feedback text in the input area and click "Analyze" to see sentiment and summary results.


 
