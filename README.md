# 📊 Meme Popularity Analytics

## 🔹 Project Overview
This project analyzes meme virality trends across Reddit by scraping data from popular meme subreddits (`r/memes`, `r/dankmemes`, `r/wholesomememes`).  
The goal is to explore **what makes memes go viral**, identify optimal posting times, and provide actionable insights using **Python (EDA)** and **visual storytelling**.

---

## 🔹 Objectives
- Collect meme data (titles, upvotes, comments, timestamps) using **Reddit API (PRAW)**.  
- Clean and preprocess the dataset (deduplication, feature engineering, datetime extraction).  
- Perform **Exploratory Data Analysis (EDA)** to identify key trends.  
- Visualize results with **Seaborn/Matplotlib**.  
- Derive **insights & recommendations** for meme virality strategy.  

---

## 🔹 Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **API**: Reddit PRAW (for scraping)  
- **Data Cleaning**: Feature engineering, datetime conversion, outlier handling  
- **Visualization**: Bar charts, line charts, scatter plots  
- *(Optional)* Power BI / Tableau → Interactive Dashboard  

---

## 🔹 Data Processing
- Removed duplicates & very short/low-effort titles.  
- Engineered metrics:  
  - **Engagement Score** = Upvotes + Comments  
  - **Virality Ratio** = Comments ÷ Upvotes  
- Extracted **time features**: posting hour, day, weekday.  
- Handled outliers by capping extreme engagement values.  

---

## 🔹 Exploratory Data Analysis (EDA)
  
### Time-of-Day Analysis
- Peak posting time: **8–10 PM IST** (+40% more engagement).  

![Engagement by Hour](https://github.com/Manthan-2004/reddit-memes-popularity-analysis/blob/main/average%20engagement%20by%20posting%20hour.png)

### Day-of-Week Analysis
- Fridays & Sundays → best performing days for meme virality.  

![Engagement by Weekday](https://github.com/Manthan-2004/reddit-memes-popularity-analysis/blob/main/average%20engagement%20by%20weekday.png)

### Engagement Correlation
- Upvotes ↔ Comments correlation = **0.82** → strong predictor of virality.  

![Upvotes vs Comments Scatter](https://github.com/Manthan-2004/reddit-memes-popularity-analysis/blob/main/upvotes%20vs%20comments%20(virality%20scatterplot).png)

---

## 🔹 Insights & Recommendations
- **Content Strategy**: Focus on Dank memes for reach, Wholesome memes for community discussion.  
- **Timing**: Post memes at **8–10 PM IST** and on **weekends** for maximum traction.  
- **Virality Prediction**: Early upvotes strongly indicate overall meme success.  

---

## 🔹 Next Steps
- Expand scraping to **Twitter & Instagram memes** for cross-platform analysis.  
- Apply **Sentiment Analysis** on meme titles to study tone impact.  
- Build a **predictive model** → *Will this meme go viral?*  
- Develop an **interactive Power BI / Tableau dashboard** for deeper insights.  

---

## 🔹 Author
👤 **Manthan Bhatjode**  
