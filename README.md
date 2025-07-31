# 📊 Prototype Real-Time Dashboard – Sentiment Analysis Visualization

This repository contains a real-time dashboard built using **Tableau** to visualize and analyze public sentiment data derived from Twitter. The dashboard is designed to support university communications and PR teams in tracking and interpreting sentiment trends related to a prestigious university.

## 🔍 Project Overview

The objective of this project is to create an interactive, insightful, and user-friendly dashboard that transforms raw tweet data into visual stories. It helps uncover key insights on public opinion, engagement behavior, and emotional patterns across time and geography.

### 🎯 Key Objectives
- Visualize sentiment distribution (Positive, Neutral, Negative).
- Map tweets geographically by sentiment.
- Analyze tweet sources (Web App, Android, iPhone).
- Track sentiment trends over time.
- Display engagement metrics (likes, quotes, retweets).
- Compare emotional tone across tweets (Joy, Sadness, Anger, etc.).
- Distinguish between verified and unverified account activity.
- Identify top 20 hashtags influencing public sentiment.

## 🗃️ Data Source

The dataset was collected from Twitter and includes metadata such as:
- `tweet_id`
- `sentiment_label`
- `emotion`
- `like_count`, `quote_count`, `retweet_count`
- `verified` (True/False)
- `source` (device/platform used)
- `hashtags`
- `location`
- `created_at`

Sample dataset included: [`twitter_dataset.csv`](./twitter_dataset.csv)

> **Note:** Data used in the dashboard has been preprocessed and anonymized for academic use only.

## 🛠️ Tools & Technologies
- **Tableau Public** – Main visualization tool
- **Python (for preprocessing)** – Optional
- **Mapbox** – Geographical mapping
- **D3.js / Plotly (for future frontend expansion)**

## 🧩 Dashboard Components

| Visualization                    | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| Pie Chart                        | Sentiment Distribution Overview (Positive, Neutral, Negative)              |
| Choropleth Map                   | Geographical Sentiment Mapping by country                                  |
| Bar Charts                       | Source of Tweets & Number of Verified Accounts                             |
| Stacked Bar Chart                | Emotion Distribution segmented by sentiment                                |
| Line Chart                       | Sentiment Trend Over Time                                                  |
| Bubble Chart                     | Engagement Metrics (likes, quotes, tweet count)                            |
| Word Cloud                       | Top 20 Hashtags Influencing Sentiment                                      |

## 🌍 Interactive Dashboard

You can explore the full interactive Tableau dashboard here:

🔗 [Prototype Real-Time Dashboard – Tableau Public](https://public.tableau.com/views/PrototypeReal-TimeDashboard/PrototypeReal-TimeDashboard)

## 🧑‍🤝‍🧑 Team Members
- Mutasim Billah (AIU21102122)
- Kjwae Thazin Aung (AIU22102148)
- Ryotaro Okamura (AIU24034001)
- Mustafe Abdirahman Mohamed (AIU21102133)

## 📅 Submission Details
- **Course:** CCS3133 – Information Visualization  
- **Instructor:** Dr. Mozaherul Hoque  
- **Institution:** School of Computing and Informatics  
- **Semester:** 1 (2024/2025)  
- **Submission Date:** 13 January 2025  

## 🚀 Future Work
- Automate data collection via Twitter API for live updates.
- Host dashboard on a cloud server with real-time filtering and drill-down.
- Expand front-end interactivity using D3.js or Plotly.
- Integrate user sentiment feedback for improved PR actions.

## 📄 License
This project is for academic and educational purposes only. All rights reserved to the original contributors.

---
