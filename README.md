# 📊 Social Media Engagement Analytics Using Python

## 📌 Project Overview
This project analyzes **social media engagement data** (likes, comments, shares, impressions, watch time, etc.) using Python.  
The goal is to clean, transform, explore, and visualize engagement metrics to uncover **content performance, user trends, and behavioral insights**.

Dataset: `social media engagement 5000.csv`

---

## 🛠️ Tech Stack
- **Python**
- **NumPy / Pandas** for data handling
- **Matplotlib / Seaborn / Plotly** for visualization
- **Jupyter Notebook / Google Colab** for execution

---

## ✅ Tasks Completed

### **Task 1 - Data Import & Setup**
- Imported dataset using `pandas.read_csv()`
- Verified and converted data types
- Converted date columns to `datetime`

### **Task 2 - Data Cleaning**
- Handled missing values (`dropna`, `fillna`, median/mode, ffill/bfill)
- Removed duplicates
- Fixed incorrect data types and standardized categories (e.g., gender labels)
- Corrected unrealistic values in likes, comments, shares
- Extracted hashtag counts and cleaned sentiment labels

### **Task 3 - Data Exploration (EDA)**
- Explored dataset using `head()`, `tail()`, `shape`, `info()`, `describe()`
- Analyzed categorical distributions with `value_counts()`, `unique()`, `nunique()`
- Generated correlation matrix for numeric fields
- Used `groupby()` to summarize metrics (e.g., avg likes by post type, impressions by country)

### **Task 4 - Data Wrangling**
- Created new fields: `engagement_score`, log-transformed metrics, hashtag count
- Performed `groupby` summaries by post_type, country, and sentiment
- Merged/concatenated DataFrames where required

### **Task 5 - Statistical Analysis**
- Computed descriptive statistics for likes, comments, shares, watch_time, engagement_rate, followers:
  - Mean, Median, Mode
  - Standard Deviation, Variance
  - Percentiles
  - Skewness & Kurtosis (optional)

### **Task 6 - Data Visualization**
- **Matplotlib**: Scatter (likes vs impressions), Line (daily trend), Bar (posts by category), Pie (gender distribution), Histogram (age), Box (engagement rate)
- **Seaborn**: Count plot (post type), Bar plot (avg likes by category), Violin (followers vs sentiment), Pair plot (numeric features), Heatmap (correlation matrix), Swarm plot (engagement vs device)
- **Plotly**: Interactive line, bar, bubble, and scatter charts

---

## 📈 Insights & Findings

### **Content Performance**
- Post types with highest engagement identified
- Best-performing content categories highlighted
- Countries with highest average engagement rate analyzed

### **User Trends**
- Age impact on engagement studied
- Verified vs non-verified account performance compared

### **Behavioral Insights**
- Best time of day for impressions discovered
- Device type impact on watch time analyzed
- Sentiment analysis: which sentiment performs best, and behavior of negative/neutral posts

---

## 🏆 Skills Demonstrated
- **Data Loading & Setup**: Pandas, datetime handling  
- **Data Cleaning & Transformation**: Missing values, duplicates, formatting  
- **Exploration & Wrangling**: EDA, slicing, indexing, groupby, feature engineering  
- **Statistical Analysis**: Descriptive stats, distributions  
- **Data Visualization**: Matplotlib, Seaborn, Plotly  
- **Reporting & Insights**: Clear communication of trends and patterns  

---

## 📊 Evaluation Rubric Coverage
- Data Loading & Setup ✔️  
- Data Cleaning & Transformation ✔️  
- Exploration & Wrangling ✔️  
- Statistical Analysis ✔️  
- Data Visualization ✔️  
- Reporting & Insights ✔️  

---

