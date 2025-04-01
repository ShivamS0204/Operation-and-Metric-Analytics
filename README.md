## 📌 Overview
This project analyzes operational efficiency and investigates metric spikes using SQL-based data analytics. It consists of two case studies:
1. **📊 Operational Analytics** - Analyzing job data to measure efficiency and throughput.
2. **📈 Metric Spike Investigation** - Understanding user engagement fluctuations, retention, and email interactions.

## 📖 Table of Contents
- [📌 Project Description](#-project-description)
- [🛠 Approach](#-approach)
- [🖥 Tech Stack](#-tech-stack)
- [📊 Case Study 1: Job Data Analysis](#-case-study-1-job-data-analysis)
- [📈 Case Study 2: Investigating Metric Spike](#-case-study-2-investigating-metric-spike)
- [🏆 Results and Conclusion](#-results-and-conclusion)

## 📌 Project Description
The project leverages SQL queries to extract and analyze data for operational insights. The key focus areas include:
- 🔹 Job data analysis to evaluate operational throughput and efficiency.
- 🔹 Identifying patterns in metric spikes via user activity trends and email engagement.

## 🛠 Approach
1. **📂 Data Extraction** - Using MySQL to fetch job data, user engagement logs, and email events.
2. **🧹 Data Cleaning** - Handling missing values, standardizing timestamps, and selecting useful records.
3. **📊 Analysis** - Running SQL queries to compute metrics like job throughput, retention, and engagement rates.

## 🖥 Tech Stack
- **🗄 Database Management**
  - 🐬 MySQL Community Server-GPL (8.0.41)
  - 🔌 MySQL Connector C++ (8.0.41)
  - 🏗 MySQL Workbench
- **📑 Presentation & Reporting**
  - 🖥 Microsoft PowerPoint
  - ☁ Google Drive

## 📊 Case Study 1: Job Data Analysis
### 🔍 Insights
- **📅 Jobs Reviewed Over Time**: Productivity peaked on November 28 (218.18 jobs/hour) and was lowest on November 27 (34.62 jobs/hour).
- **📉 Throughput Analysis**: The 7-day rolling average provided better trend insights compared to daily fluctuations.
- **🌍 Language Distribution**: Persian had the highest share (37.5%), while other languages had equal representation (12.5%).
- **📑 Duplicate Detection**: Identified duplicate job records to ensure data accuracy.

## 📈 Case Study 2: Investigating Metric Spike
### 🔍 Insights
- **📅 Weekly User Engagement**: Engagement peaked at Week 31 (1,299 users) before declining to 104 users by Week 35.
- **📈 User Growth**: A steady increase in active users, reaching 404 by Week 10.
- **🔁 Weekly Retention**: Retention struggles were observed, with many users failing to return after signing up.
- **💻 Engagement by Device**: Laptops had the highest engagement, while smartphones showed lower interaction rates.
- **📧 Email Engagement**: Open rate was 33.58%, and click-through rate was 14.79%, indicating room for improvement.

## 🏆 Results and Conclusion
- 📌 Rolling averages provided better insights into throughput trends.
- 📉 Engagement trends revealed user drop-off patterns.
- 📧 Email engagement rates highlighted areas for improvement in user interaction strategies.
