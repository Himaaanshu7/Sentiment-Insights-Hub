# Sentiment-Insights-Hub
Welcome to Sentiment Insights Hub, a project that analyzes Amazon Fine Food Reviews to uncover sentiment trends and popular words using Python and Tableau. This end-to-end project processes review data, performs sentiment analysis, calculates word frequencies, and visualizes the results in an interactive dashboard.

**Features**
Preprocesses raw review data (e.g., cleans text, converts timestamps).
Analyzes sentiments (Positive, Negative, Neutral) using VADER.
Identifies top words by sentiment with frequency counts.
Visualizes insights with bar charts, line graphs, and word tables in Tableau.

**Project Structure**
Sentiment-Insights-Hub/
├── preprocess_reviews.py        # Cleans and preprocesses review data
├── sentiment_analysis.py        # Adds sentiment scores and labels
├── word_frequency.py            # Computes word frequencies by sentiment
├── Reviews.csv                  # Original dataset (Amazon Fine Food Reviews)
├── preprocessed_reviews.csv     # Processed data with dates and text
├── reviews_with_sentiment.csv   # Data with sentiment analysis results
├── word_frequency.csv           # Word counts by sentiment
├── Sentiment_Insights_Hub.twb   # Tableau dashboard file
├── README.md                    # This file


**Requirements**
Python 3.9+
Libraries:
pandas
nltk
vaderSentiment
Tableau Public (for visualization)
Anaconda (recommended for environment management)

**Installation**
Clone the repository:git clone https://github.com/yourusername/Sentiment-Insights-Hub.git
cd Sentiment-Insights-Hub

Set up a virtual environment (optional but recommended):python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # macOS/Linux

Install dependencies:pip install pandas nltk vaderSentiment

Download NLTK data (run once):import nltk
nltk.download('punkt')
nltk.download('stopwords')

Install Tableau Public from tableau.com.

Usage

Preprocess Data:

Run the preprocessing script:python preprocess_reviews.py
Output: preprocessed_reviews.csv with cleaned text and dates.


Analyze Sentiment:

Run the sentiment analysis script:python sentiment_analysis.py
Output: reviews_with_sentiment.csv with sentiment labels and scores.


Compute Word Frequencies:

Run the word frequency script:python word_frequency.py
Output: word_frequency.csv with top words by sentiment.


Visualize in Tableau:

Open Sentiment_Insights_Hub.twb in Tableau Public.
Explore the dashboard with filters for ProductId and Year.
Save or publish to Tableau Public for a shareable link.


Results

Sentiment Breakdown: Most reviews are Positive, with trends visible over time.
Word Insights: Words like “great” dominate Positive reviews, while “bad” appears in Negative ones.
Dashboard: Interactive charts show sentiment distribution, trends, and word frequencies.

Acknowledgments

Dataset: Amazon Fine Food Reviews from Kaggle.
Tools: Python, NLTK, VADER, Tableau Public.
