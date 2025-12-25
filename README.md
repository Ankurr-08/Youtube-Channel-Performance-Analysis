# 📊 YouTube Channel Performance Analysis

## 📌 Project Overview
This project analyzes real YouTube video-level performance data to understand **what drives views, engagement, subscriber growth, and revenue**.  
The focus of this project is **Exploratory Data Analysis (EDA)** and **business insights**, not machine learning.

The goal is to help content creators, analysts, and marketers understand:
- How videos perform over time
- What factors influence revenue and growth
- How audience behavior impacts channel success

---

## 🎯 Objectives
- Analyze the distribution of key YouTube performance metrics
- Understand relationships between views, revenue, engagement, and retention
- Identify optimal publishing times
- Evaluate audience growth and monetization behavior
- Provide actionable recommendations for channel optimization

---

## 📂 Dataset Information
- **Dataset Name:** YouTube Channel Real Performance Analytics
- **Rows:** 364 (each row represents one video)
- **Columns:** 70 performance metrics
- **Granularity:** Video-level analytics

### Key Metrics Include:
- Views, Likes, Comments, Shares
- Estimated Revenue (USD), CPM
- Watch Time & Average View Duration
- Video Thumbnail CTR (%)
- Subscribers gained
- Video Duration & Publish Time
- Audience retention and monetization metrics

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook**

---

## 🔍 Methodology & Steps Performed

### 1️⃣ Data Inspection
- Loaded dataset and examined structure
- Verified dataset size and column composition
- Understood metric categories (performance, audience, revenue)

---

### 2️⃣ Data Cleaning
- Verified **no missing values** and **no duplicate records**
- Converted `Video Publish Time` to datetime format
- Converted categorical columns (e.g., Day of Week) to appropriate types
- Retained all numerical metrics to preserve real-world variation

📌 *No rows were dropped as the dataset was already clean.*

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of:
  - Views
  - Estimated Revenue
  - Video Duration
- Identified strong right-skew in views and revenue
- Observed that a small number of videos dominate overall performance

---

### 4️⃣ Relationship Analysis
Analyzed relationships between:
- Views vs Estimated Revenue
- Video Duration vs Views
- Engagement vs Views
- Engagement vs Revenue

**Key takeaway:**  
Views are the strongest driver of revenue, while engagement and duration influence performance indirectly.

---

### 5️⃣ Time-Based Analysis
- Performance by day of week
- Monthly performance trends
- Year-wise growth trends

**Findings:**
- Upload performance varies across days
- Seasonal patterns exist across months
- Channel performance improves over time due to audience growth and optimization

---

### 6️⃣ Audience & Monetization Analysis
Focused on:
- Views vs Subscribers
- Thumbnail CTR vs Views
- CPM vs Revenue
- Retention vs Views

**Insights:**
- Not all views convert equally into subscribers
- Thumbnail CTR significantly affects discoverability
- CPM strongly impacts monetization efficiency
- Higher retention improves long-term performance

---

## 📈 Key Insights
- YouTube performance metrics are highly skewed; a few videos generate most views and revenue
- Views are the primary revenue driver
- Video length alone does not guarantee success
- Thumbnail CTR plays a critical role in initial reach
- Audience retention is a strong signal for sustained performance
- Monetization efficiency varies due to CPM and audience factors

---

## 💡 Business & Creator Recommendations
- Optimize thumbnails and titles to improve CTR
- Focus on audience retention rather than video length
- Upload videos on high-performing days for better initial traction
- Target content niches with higher CPM for better monetization
- Design content that converts viewers into subscribers, not just views

---

## 📌 Scope Clarification
This project is intentionally designed as a **data analytics (EDA-focused)** project.

### Excluded in this version:
- Feature engineering for model accuracy
- Machine learning models
- Predictive analytics and deployment

These exclusions are **intentional**, not missing work.

---

## 🔮 Future Scope
- Apply feature engineering to create predictive signals
- Build machine learning models to predict views and revenue
- Perform feature importance analysis to identify key growth drivers

---

## 🧾 Conclusion
This project provides a comprehensive exploratory analysis of YouTube channel performance using real analytics data. By examining distribution patterns, relationships between key metrics, timing effects, and audience behavior, the analysis delivers actionable insights for improving content strategy and monetization. The project lays a strong foundation for future machine learning-based performance prediction.

---

## ✨ Author
**Ankur Maheshwari**  
Data Analytics Project

