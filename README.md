# Bank Reviews Analysis

## Task 1: Data Collection and Preprocessing

### Methodology

1. **Data Collection**:
   - Used the `google-play-scraper` Python package to collect reviews from three major bank apps on Google Play Store:
     - Chase Mobile (com.chase.sig.android)
     - Bank of America (com.infonow.bofa)
     - Wells Fargo (com.wf.wellsfargomobile)
   - Collected at least 400 reviews per bank (1,200+ total)
   - Captured review text, star rating, date, bank name, and source

2. **Preprocessing**:
   - Removed duplicate reviews
   - Handled missing data by:
     - Dropping rows with missing reviews or ratings
     - Filling missing dates with the current date
   - Ensured consistent data types
   - Normalized date format to YYYY-MM-DD
   - Added review length as an additional feature

### Files

- `scrape_reviews.py`: Script to collect reviews from Google Play Store
- `preprocess_reviews.py`: Script to clean and preprocess the collected data
- `bank_reviews.csv`: Raw scraped data
- `bank_reviews_clean.csv`: Cleaned and processed data

### Requirements

Python packages listed in `requirements.txt`