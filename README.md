## 🧹 Task 1: Data Collection & Preprocessing

We scraped 1,200+ user reviews from Google Play Store for three Ethiopian banks using `google-play-scraper`.

### 🛠 Methodology

- **Scraping**: Used official app IDs for CBE, BOA, and Dashen.
- **Cleaning**:
  - Removed duplicate reviews
  - Handled missing data
  - Normalized date format to `YYYY-MM-DD`
- **Storage**: Saved CSV files to `data/raw/` and `data/cleaned/`

### 📊 Output

- `data/raw/all_reviews_raw.csv`: Unprocessed full dump
- `data/cleaned/all_reviews_cleaned.csv`: Ready for sentiment analysis
