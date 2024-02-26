# Sentiment-Analysis
## Analyzing sentiments in customer reviews for hotel using NLP and machine learning techniques.
The Sentiment Analysis of Customer Hotel Reviews project is implemented to analyze and classify the sentiment of customer reviews about hotels. By employing natural language processing (NLP) techniques and machine learning algorithms, this project aims to categorize customer sentiments as positive, negative, or neutral based on their reviews.

**Basic Understanding of code**
* Gather customer reviews of hotels from various online platforms or datasets.
* Import vader_lexicon module from nltk(Natural Language ToolKit) package used for analysing sentiments in textual data.
* Find the polarity score (The polarity score ranges from -1 to 1. A score of -1 means the words are super negative, like “disgusting” or “awful.” A score of 1 means the words are super positive, like “excellent” or “best.”) and compound score (A compound score is the sum of all the words in a lexicon, normalized between -1 and 1. It's calculated by normalizing the other three scores (neg, neu, pos) between -1 and +1.)
* Finally differentiate the reviews based on compound score into positive & negative tables respectively.

**Dependencies**
* Python 3.x
* Libraries: pandas, numpy, nltk, SentimentIntensityAnalyzer, vader_lexicon, etc.

**Data Sources**
Customer reviews from online travel platforms (e.g., TripAdvisor, Booking.com, Expedia)
Publicly available datasets containing hotel reviews (e.g., Kaggle datasets)
