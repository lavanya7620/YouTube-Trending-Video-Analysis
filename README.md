<<<<<<< HEAD
# YouTube Trending Video Analysis

## Overview
This project analyzes YouTube trending videos from India and the United States to uncover what makes videos go viral. Using data from Kaggle, we explore trends across categories, countries, and engagement metrics, and visualize patterns using advanced Python techniques.

## Dataset
- **Source:** [YouTube Trending Video Statistics – Kaggle](https://www.kaggle.com/datasnaek/youtube-new)
- **Files Used:** INvideos.csv, USvideos.csv, IN_category_id.json, US_category_id.json
- **Number of Unique Videos Analyzed:** <insert total number of rows after deduplication>

## Key Features
- Trending videos’ metadata (title, category, publish time, views, likes, comments)
- Category mapping from category_id to readable names
- Cleaned video titles for text analysis
- Country identifier for India vs US comparison

## Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- NLP: NLTK (stopwords), WordCloud
- Jupyter Notebook for exploration and analysis


## Insights (Summary)
1. **Top Categories Overall:** Entertainment, News & Politics, Music  
2. **Country Differences:**  
   - India → Entertainment & News dominate  
   - US → Film & Animation, Gaming, and Education are more frequent  
3. **Title Analysis:** Words like `episode`, `official`, `news`, `song` dominate trending titles  
4. **Engagement Analysis:**  
   - Views & Likes correlation: 0.83  
   - Views & Comments correlation: 0.56  
   - Likes are the strongest engagement indicator  

## Visualizations
- WordCloud of viral video titles  
- Bar chart of top words in titles  
- Stacked bar chart of top categories by country  

---

## How to Run
1. Clone the repository
2. Place raw CSV & JSON files in `data/raw/`
3. Open `notebooks/01_data_exploration.ipynb`
4. Run all cells to reproduce analysis & visuals

---

## Author
**Lavanya Vanga**  
Aspiring Data Analyst | Portfolio Project  
=======
# YouTube-Trending-Video-Analysis
"Analyze YouTube trending videos from India and US to uncover virality patterns"
>>>>>>> 0a160645004097dec593a533f5c189d9f2a133eb
