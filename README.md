## Task 2: Sentiment and Thematic Analysis

### Methodology

1. **Sentiment Analysis**:
   - Primary analysis using DistilBERT model (`distilbert-base-uncased-finetuned-sst-2-english`)
   - Secondary analysis with TextBlob and VADER for comparison
   - Computed sentiment scores (positive/negative/neutral) and confidence levels
   - Aggregated results by bank and star rating

2. **Thematic Analysis**:
   - Text preprocessing with spaCy (lemmatization, stop word removal)
   - Keyword extraction using TF-IDF to identify significant terms and n-grams
   - Manual theme clustering based on common banking app concerns:
     - Account Access Issues
     - Transaction Problems
     - User Interface & Experience
     - Customer Support
     - Feature Requests
   - Each review assigned to relevant themes based on keyword matching

### Files

- `sentiment_analysis.py`: Script for sentiment analysis using multiple approaches
- `thematic_analysis.py`: Script for keyword extraction and theme identification
- `bank_reviews_with_sentiment.csv`: Reviews with sentiment scores
- `bank_reviews_with_sentiment_and_themes.csv`: Complete analysis results
- `aggregated_sentiment_by_bank_and_rating.csv`: Summary statistics

### Results

Example findings:
- Chase: Most complaints about login issues (Account Access)
- Bank of America: Frequent mentions of slow transfers (Transaction Issues)
- Wells Fargo: Many comments about app crashes (User Interface)