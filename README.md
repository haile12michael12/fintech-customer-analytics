# fintech-customer-analytics

## Methodology

1. Data Collection:
   - Used google-play-scraper Python package
   - Collected 400+ reviews each for Chase, Bank of America, and Wells Fargo mobile apps
   - Captured review text, star rating, date, bank name, and source

2. Data Preprocessing:
   - Removed duplicate reviews
   - Handled missing values by dropping incomplete records
   - Standardized date format to YYYY-MM-DD
   - Verified data types (rating as integer, etc.)

3. Quality Control:
   - Achieved <5% missing data threshold
   - Maintained all key columns in final dataset