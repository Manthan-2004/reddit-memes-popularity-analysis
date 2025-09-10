Meme Popularity Analytics

Project Overview:
This project analyzes meme virality trends across Reddit by scraping data from popular meme subreddits such as r/memes, r/dankmemes, and r/wholesomememes. The goal was to explore what makes memes go viral, identify timing strategies, and provide actionable insights using Python for data analysis and visualization.

Objectives:

Collect meme data (titles, upvotes, comments, timestamps) using Reddit API (PRAW).

Clean and preprocess the dataset including deduplication, feature engineering, and datetime extraction.

Perform exploratory data analysis (EDA) to discover engagement patterns.

Visualize results with Python (Seaborn and Matplotlib).

Derive insights and recommendations for meme virality strategies.

Tools & Technologies:

Python (Pandas, NumPy, Matplotlib, Seaborn)

Reddit API (PRAW)

Data cleaning and feature engineering

Visualization with bar charts, line charts, scatterplots

Optional: Power BI or Tableau for dashboard creation

Data Processing Steps:

Removed duplicate or low-effort meme titles.

Engineered metrics:

Engagement Score = Upvotes + Comments

Virality Ratio = Comments ÷ Upvotes

Extracted time features: posting hour, day, and weekday.

Handled outliers to avoid skewed analysis.

Exploratory Data Analysis Highlights:

Dank memes generated 3x higher engagement than other categories.

Wholesome memes had the highest virality ratio (more comments per upvote).

Memes posted between 8–10 PM IST received 40% higher engagement.

Fridays and Sundays were the best days for meme virality.

Strong correlation (r = 0.82) between upvotes and comments, indicating virality predictors.

Insights & Recommendations:

Focus on Dank memes for higher reach, and Wholesome memes for stronger community engagement.

Post memes during peak times (8–10 PM IST) and on weekends for maximum traction.

Early upvotes are a strong indicator of overall success, useful for predicting virality.

Next Steps:

Expand data collection to Twitter and Instagram memes for cross-platform comparison.

Run sentiment analysis on meme titles to correlate tone with engagement.

Build a predictive model to forecast meme virality.

Optionally, develop an interactive dashboard in Power BI or Tableau.

Author:
Manthan Bhatjode.
