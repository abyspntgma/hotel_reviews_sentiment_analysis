# Hotel Reviews Sentiment Analysis using Google Maps, Transformers, and NLTK Project Overview

This project performs sentiment analysis on hotel reviews collected from Google Maps using the SerpAPI Google Maps API. The notebook demonstrates a complete Natural Language Processing (NLP) workflow, from data collection and text preprocessing to sentiment prediction and model evaluation.

The primary objective is to analyze customer opinions about hotels around the Sarinah area (Jakarta) and compare the performance of two sentiment analysis approaches:

🤗 Hugging Face Transformers Sentiment Analysis Pipeline
📚 NLTK VADER Sentiment Analyzer

## Project Workflow

### 1. Data Collection
Scrape hotel information from Google Maps using SerpAPI
Retrieve customer reviews for each hotel
Extract:
- Hotel name
- Reviewer name
- Rating
- Review text

### 2. Data Preprocessing
- The review texts undergo several preprocessing steps:
- Convert text to lowercase
- Remove punctuation and non-alphabetic characters
- Tokenization
- Stopword removal
- Lemmatization using NLTK
- Create sentiment labels based on Google ratings:
-- Positive: Rating > 3
-- Negative: Rating ≤ 3
  
### 3. Exploratory Data Analysis (EDA)
The notebook includes visualizations such as:
- Distribution of hotel ratings
- Positive review Word Cloud
- Negative review Word Cloud
- Sentiment distribution
These visualizations provide insights into customer feedback patterns.

### 4. Sentiment Analysis Models
Hugging Face Transformers
Uses the pre-trained sentiment-analysis pipeline to classify customer reviews into:
- Positive
- Negative
Predicted probabilities are also extracted for evaluation.
NLTK VADER
Uses the VADER sentiment analyzer to predict review sentiment based on lexical features and sentiment scores.

### 5. Model Evaluation
The predicted results are evaluated against the labels generated from review ratings using:
- Accuracy
- Confusion Matrix
This allows comparison between Transformer-based sentiment analysis and the rule-based VADER approach.

## Technologies Used
- Python
- Pandas
- NLTK
- Hugging Face Transformers
- SerpAPI
- Matplotlib
- Seaborn
- WordCloud
- Scikit-learn
- Project Highlights
- Google Maps review scraping using SerpAPI
- Complete NLP preprocessing pipeline
- Text cleaning and lemmatization
- Sentiment visualization with Word Clouds
- Comparison between deep learning and lexicon-based sentiment analysis
- Model performance evaluation using confusion matrices and accuracy metrics
- Learning Outcomes

Through this project, I gained hands-on experience with:
- Web data collection using APIs
- Natural Language Processing (NLP)
- Text preprocessing techniques
- Sentiment analysis using modern Transformer models
- Rule-based sentiment analysis with NLTK VADER
- Performance evaluation of machine learning models
- Data visualization for textual data

The ppt file for the presentation can be seen in full on the following website page https://heyzine.com/flip-book/d8b3e1159f.html

Also you can reach me on my Linkedin on https://www.linkedin.com/in/abiyasapanatagama/ 
