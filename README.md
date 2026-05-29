# Edtech-App-Analytics
# 📊 Digital Learning Analytics - Excel Dashboard

## 📝 Overview
This repository contains an interactive Excel Dashboard designed to analyze the behaviors, engagement metrics, and revenue generation of 100,000 learners across major MOOC (Massive Open Online Course) platforms. The project transforms raw educational data into actionable business intelligence, highlighting trends in user acquisition, course completion, and platform monetization.

## 📸 Dashboard Preview


<img width="1312" height="522" alt="image" src="https://github.com/user-attachments/assets/e0647289-f3c0-4c26-ab85-5957b225f408" />


<img width="1313" height="528" alt="image" src="https://github.com/user-attachments/assets/9e77706b-97b3-4f06-bdfd-19333e527675" />


<img width="1321" height="524" alt="image" src="https://github.com/user-attachments/assets/81b61a32-dfa5-4eba-8074-85176565d05a" />


<img width="1316" height="525" alt="image" src="https://github.com/user-attachments/assets/9ae5b4ec-b3c0-46ea-b56d-d39400a5ee0f" />


<img width="1316" height="522" alt="image" src="https://github.com/user-attachments/assets/6b328fa0-97dc-4eed-9cc7-57648b1349e6" />



## 🎯 Key Objectives
* **Demographic & Acquisition Analysis:** Track user growth (DAU) from 2020 to 2025 and understand the distribution of learners by age, gender, and education level.
* **Financial Performance:** Compare the revenue contributions of Free vs. Premium users to evaluate monetization strategies.
* **Engagement & Performance Metrics:** Analyze app completion rates, video completion percentages, and average time-to-mastery across various course categories (e.g., Data Science, Arts & Humanities, Business & Finance).
* **Churn & Retention:** Investigate the factors contributing to learner churn versus active retention.

## 🗂️ Dataset Description
The underlying dataset (`digital_learning_analytics_100k.xlsx`) contains 100,000 anonymized learner records. Key features include:
* **User Profiles:** `learner_id`, `age`, `gender`, `education_level`, `country`, `employment_status`
* **App Usage & Engagement:** `daily_app_minutes`, `session_count_weekly`, `app_completion_rate`, `video_completion_pct`
* **Course Info:** `mooc_platform` (e.g., Coursera, Udemy, Khan Academy), `course_category`, `learning_path_type`
* **Performance:** `in_app_quiz_score`, `skill_pre_score`, `skill_post_score`, `time_to_mastery_hours`
* **Business Metrics:** `user_type` (Free/Premium), `Revenue`, `Churn_Status`

## 🛠️ Tools & Techniques Used
* **Microsoft Excel:** The primary tool for data processing and visualization.
* **Pivot Tables & Pivot Charts:** Used extensively for aggregating metrics (e.g., Average Time to Mastery by Category, Revenue by User Type).
* **Data Cleaning & Transformation:** Ensuring data consistency across 100k rows for accurate dashboard rendering.
* **Interactive Dashboard Design:** Utilizing slicers and dynamic charts to allow users to filter data by year, platform, and user type.

## 💡 Key Insights
1. **Revenue Concentration:** Premium users drive the entirety of the platform's $6.87M revenue pool, while free users represent a significant portion of the acquisition funnel.
2. **Consistent Learning Times:** The average "Time to Mastery" remains incredibly stable (~36.8 to 36.9 hours) regardless of the discipline (Data Science vs. Arts & Humanities).
3. **Acquisition Trends:** User acquisition remained highly stable from 2020 through 2025, averaging roughly ~16,600 to ~16,700 new learners annually.
