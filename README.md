📊 YouTube Trending Video Analysis

Data Analysis Project – 3

📌 Project Overview

This project analyzes YouTube trending video statistics to understand the relationship between views, likes, dislikes, comments, and engagement.
The goal is to answer an important analytical question:

Does popularity (views) guarantee likes and engagement?

Using real-world data from Kaggle, this project goes beyond basic analysis by incorporating feature engineering, engagement metrics, country-wise comparison, and time-based insights.

🎯 Learning Objectives

Through this project, I practiced and improved:

Data cleaning & preprocessing

Sorting and filtering large datasets

Correlation analysis

Feature engineering (engagement rates)

Exploratory Data Analysis (EDA)

Data visualization using Matplotlib & Seaborn

Drawing actionable insights from data

📂 Dataset

Source: Kaggle – YouTube Trending Videos Dataset
📎 Link:
https://www.kaggle.com/datasets/datasnaek/youtube-new

Files used:

USvideos.csv

CAvideos.csv

US_category_id.json

CA_category_id.json

🧱 Project Structure
youtube-video-analysis/
│
├── data/
│ ├── USvideos.csv
│ ├── CAvideos.csv
│ ├── US_category_id.json
│ └── CA_category_id.json
│
├── charts/
│ ├── scatter_views_likes.png
│ ├── engagement_by_category.png
│ ├── top_10_videos.png
│ └── views_by_day.png
│
├── youtube_analysis.ipynb
├── insights.txt
├── report.txt
└── README.md

🧹 Data Cleaning Steps

Removed duplicate videos

Handled missing values

Converted date columns to datetime

Extracted:

Day of week

Hour of publish

Mapped category IDs using JSON files

Filtered invalid or zero-value metrics

⚙️ Feature Engineering

New analytical features created:

Like Rate = Likes / Views

Dislike Rate = Dislikes / Views

Comment Rate = Comments / Views

Title Length

Publish Day

Publish Hour

These features helped analyze engagement beyond raw views.

📊 Analysis Performed

Correlation between views and likes

Engagement comparison across categories

Country-wise comparison (US vs Canada)

Most engaging days of the week

Effect of title length on engagement

Top 10 trending videos analysis

📈 Visualizations

Scatter plot: Views vs Likes

Bar chart: Top 10 trending videos

Bar chart: Engagement by category

Time-based charts (day & hour analysis)

All plots are saved inside the charts/ directory.

🔍 Key Insights

High views do not always guarantee high likes

Engagement rate varies significantly by category

Certain days of the week generate more engagement

Shorter titles tend to perform better in engagement metrics

Trending behavior differs between countries

🧠 Final Conclusion

Popularity alone does not define audience appreciation.
Engagement metrics (likes, comments, rates) provide a much clearer picture of how users actually respond to content.

This project highlights why raw views are not enough for meaningful content performance analysis.

🛠 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🚀 Future Improvements

Add statistical tests (Pearson/Spearman correlation)

Build interactive dashboards (Plotly / Power BI)

Include more countries for global comparison

Convert analysis into a reusable pipeline

👤 Author

Dipak Basnet
Aspiring Data Analyst | Python | Pandas | Data Visualization
