# Insights Summary – YouTube Trending Video Analysis

## Project Goal
Analyze YouTube trending videos from India and the US to discover patterns in virality, engagement, and category trends.

## Data Preparation
- Loaded India and US CSV files
- Added `country` column to identify source
- Combined datasets and removed duplicates (kept highest views per video)
- Converted `trending_date` and `publish_time` to proper datetime
- Mapped `category_id` to `category_name`
- Cleaned `title` text for word frequency analysis

## Key Findings

### 1. Top Categories
- **Overall Top 3:** Entertainment (9079), News & Politics (3006), Music (1994)
- **India:** Entertainment & News dominate  
- **US:** Film & Animation, Gaming, Education are more frequent

### 2. Text Analysis of Titles
- Most frequent words in viral titles: `episode`, `full`, `news`, `video`, `tv`, `official`, `telugu`, `song`, `movie`, `new`  
- Indicates **official content, news, and entertainment** dominate trending videos
- Stopwords removed for cleaner visualization

### 3. Engagement Analysis
| Metrics | Correlation |
|---------|------------|
| Views & Likes | 0.83 |
| Views & Comments | 0.56 |
| Likes & Comments | 0.76 |

- Videos with more views generally get more likes
- Comments are moderately correlated with views
- Likes are the strongest engagement indicator of virality

### 4. Country-Level Insights
- India favors **Entertainment & News**
- US favors **Gaming, Film & Animation, and Education**
- Shows **regional differences** in trending video patterns

## Visualizations
1. **WordCloud:** Highlights frequent words in viral titles  
2. **Top Words Bar Chart:** Quantifies word frequency  
3. **Stacked Bar Chart by Country:** Compares category trends between India & US

## Conclusion
- Viral YouTube videos are dominated by **official media, entertainment, and news content**  
- Regional trends exist, showing cultural preferences in India vs US  
- Engagement metrics reveal **likes as a key indicator of virality**

---

**Author:** Lavanya Vanga
