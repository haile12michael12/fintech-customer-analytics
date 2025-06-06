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

   
## 4. Update README.md

Add this section to your README.md:

```markdown
## Task 4: Insights and Recommendations

### Methodology

1. **Data Analysis**:
   - Calculated sentiment and rating distributions
   - Identified key themes through word frequency analysis
   - Tracked sentiment trends over time

2. **Visualization**:
   - Created multiple plot types using Matplotlib/Seaborn
   - Generated word clouds for thematic analysis
   - Designed publication-quality figures

3. **Recommendations**:
   - Developed both quick wins and strategic improvements
   - Prioritized based on frequency and sentiment impact
   - Considered technical feasibility

### Files

- `analysis_visualization.ipynb`: Jupyter notebook with all analysis code
- `final_report.md`: 4-page final report with insights and recommendations
- Visualizations:
  - `sentiment_distribution.png`
  - `rating_distribution.png`
  - `sentiment_trend.png`
  - `wordcloud_*.png`

### Usage

1. Run the Jupyter notebook to regenerate analysis
2. Review final_report.md for key findings
3. Visualizations are saved as PNG files for presentations