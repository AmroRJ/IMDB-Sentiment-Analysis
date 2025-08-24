Overview;  
This project performs sentiment analysis on the IMDB movie reviews dataset using Natural Language Processing (NLP) techniques and machine learning. The goal is to classify movie reviews as either positive or negative based on their textual content.

Project Structure;  
1.The notebook follows a comprehensive workflow for sentiment analysis:  
Data Loading & Exploration: Loads the IMDB dataset and performs initial exploration including sentiment distribution analysis.  
2.Text Preprocessing:  
HTML tag removal, 
URL removal, 
Special character removal, 
Lowercasing, 
Tokenization, 
Stopword removal, 
Lemmatization, 
Text length analysis  
3.Data Visualization:  
Sentiment distribution plots, 
Word count analysis by sentiment, 
Word clouds for positive and negative reviews  
4.Feature Engineering:  
Text length features, 
Word count features, 
Processed text preparation for modeling  
5.Interactive Demo:   
Includes a widget-based interface for users to input their own reviews and get sentiment predictions.

Key Features;  
Comprehensive Text Cleaning: Multiple preprocessing steps to prepare text data for analysis
Exploratory Data Analysis: Visualizations to understand data distribution and characteristics
Word Cloud Visualization: Visual representation of most frequent words in positive vs negative reviews
Interactive Prediction: User-friendly interface to test custom reviews
Dimensionality Reduction: Text processing reduces original text length by ~38% while preserving meaningful content

Technologies Used;  
Python, 
Pandas & NumPy for data manipulation, 
NLTK for text processing, 
Matplotlib & Seaborn for visualization, 
WordCloud for text visualization, 
Scikit-learn for machine learning utilities, 
TextBlob for sentiment analysis, 
IPython widgets for interactive demo

Dataset;  
The project uses the IMDB Dataset containing 50,000 movie reviews labeled as positive or negative sentiment.

Results;  
The analysis reveals:    
Balanced dataset with 25,000 positive and 25,000 negative reviews, 
Distinct vocabulary patterns between positive and negative sentiments, 
Effective text preprocessing pipeline for sentiment classification tasks

Usage;  
The notebook provides an end-to-end workflow for sentiment analysis that can be adapted for other text classification tasks. The interactive demo allows users to input custom text and receive sentiment predictions with confidence scores.

Potential Applications;  
Product review analysis, 
Social media sentiment monitoring, 
Customer feedback classification, 
Content moderation systems

This project demonstrates fundamental NLP techniques and provides a solid foundation for building more advanced sentiment analysis systems.
