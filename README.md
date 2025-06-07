# 📊 Banking App Review Sentiment Analysis (CBE, BOA, Dashen)

This project analyzes customer satisfaction with mobile banking applications in Ethiopia by collecting and processing user reviews from the Google Play Store. It simulates the role of a Data Analyst at **Omega Consultancy**, providing insights and recommendations to improve digital banking experiences for:

- 🇪🇹 Commercial Bank of Ethiopia (CBE)
- 🇪🇹 Bank of Abyssinia (BOA)
- 🇪🇹 Dashen Bank

---

## 🗂️ Repository Structure

- banking-review-analysis/
- ├── data/ # Raw and cleaned review CSVs
- ├── notebooks/ # Jupyter notebooks for each task
- ├── scripts/ # Python scripts for scraping, analysis, DB
- ├── db/ # SQL schema and inserts
- ├── plots/ # Visualizations
- ├── reports/ # Markdown report with findings
- ├── requirements.txt # Project dependencies
- ├── README.md # Project documentation


## 🚀 Project Tasks

### ✅ Task 1: Data Collection & Preprocessing
- Scraped 1,200+ user reviews using `google-play-scraper`.
- Cleaned the data (duplicates, missing values, normalized dates).
- Stored as structured CSV with: `review`, `rating`, `date`, `bank`, `source`.

### ✅ Task 2: Sentiment & Thematic Analysis
- Applied **DistilBERT** and **VADER** to score sentiments (positive/negative/neutral).
- Extracted keywords using **spaCy** and **TF-IDF**.
- Clustered keywords into 3–5 themes per bank (e.g., 'Login Issues', 'Transaction Delays').

### ✅ Task 3: Oracle DB Integration
- Designed relational schema: `Banks`, `Reviews`.
- Inserted cleaned data (>1,000 rows) into Oracle XE using Python + `cx_Oracle`.

### ✅ Task 4: Insights & Recommendations
- Visualized trends (bar plots, word clouds).
- Identified pain points (e.g., login failure, app crashes) and satisfaction drivers (e.g., easy navigation).
- Proposed 2+ actionable improvements per bank.



## 📊 Example Visualizations

- 📈 Sentiment Distribution by Bank
- ☁️ Word Clouds (Positive & Negative)
- 📉 Ratings vs. Sentiment Trends
- 🧠 Thematic Clusters per Bank


## 🛠️ Technologies Used

- Python (Pandas, Seaborn, Matplotlib, spaCy, Scikit-learn)
- NLP Models: `distilbert-base-uncased-finetuned-sst-2-english`, VADER
- Oracle XE (via `cx_Oracle`)
- Google Play Scraper (Python)
- GitHub (version control, PRs, branches per task)


## 📚 How to Run

1. Clone this repo:
   
    git clone https://github.com/haile12michael12/fintech-customer-analyst.git
    cd banking-review-analysis
   

2. Install dependencies:
  
    pip install -r requirements.txt
   

3. Run scripts:
    - Scraping: `python scripts/scraping/scrape_reviews.py`
    - Preprocessing: `python scripts/preprocessing/clean_reviews.py`
    - Sentiment/Theme Analysis: `python scripts/analysis/sentiment.py`
    - DB Insert: `python scripts/database/insert_to_oracle.py`

