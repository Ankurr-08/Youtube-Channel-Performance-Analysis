# 📊 YouTube Channel Performance Analysis | Data Analytics Project

🔗 **Live Tableau Dashboard:** https://public.tableau.com/views/YoutubePerformanceDashboard_17666662862580/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

📈 *Interactive dashboard analyzing YouTube views, engagement, revenue, subscriber growth, and publishing patterns.*

---

## 📌 Project Summary
This project conducts **business-focused exploratory data analysis (EDA)** on real **YouTube video-level performance data** to identify the key drivers behind **views, engagement, subscriber growth, and revenue**.

Using Python for analysis and Tableau for visualization, the project demonstrates an **end-to-end analytics workflow** — from clean data validation to insight generation and dashboard storytelling.  
The project is well-suited for **Data Analyst, Business Analyst, and Digital Analytics** roles.

---

## 🎯 Business Objectives
- Identify key factors influencing **views and revenue**
- Analyze **engagement and audience retention behavior**
- Evaluate **publishing time and seasonal performance trends**
- Assess **monetization efficiency** using CPM and revenue metrics
- Translate raw analytics into **actionable business insights**

---

## 📂 Dataset Overview
- **Dataset Name:** YouTube Channel Performance Analytics  
- **Source:** Channel-level YouTube Analytics export  
- **Rows:** 364 (each row represents one video)  
- **Columns:** 70 performance metrics  
- **Granularity:** Video-level  

### Key Metrics Included
- Views, Likes, Comments, Shares  
- Estimated Revenue (USD), CPM  
- Watch Time, Average View Duration  
- Thumbnail Click-Through Rate (CTR %)  
- Subscribers Gained  
- Video Duration & Publish Time  
- Audience Retention & Monetization Metrics  

---

## 🛠 Tools & Technologies
**Programming & Analysis**
- Python
- Pandas
- NumPy

**Visualization**
- Matplotlib
- Seaborn
- Tableau Public

**Analytics Techniques**
- Data Validation & Cleaning
- Exploratory Data Analysis (EDA)
- Trend & Distribution Analysis
- Correlation & Relationship Analysis
- KPI Identification
- Data Storytelling

---

## 🔍 Analytical Workflow

### 1️⃣ Data Inspection & Validation
- Loaded dataset and reviewed schema and data types
- Verified dataset size and column consistency
- Confirmed absence of missing values and duplicate records

📌 *The dataset required no row removal due to high data quality.*

---

### 2️⃣ Data Preparation
- Converted `Video Publish Time` to datetime format
- Standardized categorical fields (e.g., day of week)
- Preserved all numerical metrics to retain real-world variation

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed distributions of:
  - Views
  - Estimated Revenue
  - Video Duration
- Identified **right-skewed distributions**, indicating that a small number of videos generate a large share of total performance

---

### 4️⃣ Relationship Analysis
Explored relationships between:
- Views and Estimated Revenue  
- Engagement metrics and Views  
- Engagement metrics and Revenue  
- Video Duration and Views  

**Key Finding:**  
Views are the **primary driver of revenue**, while engagement and duration influence performance indirectly.

---

### 5️⃣ Time-Based Performance Analysis
- Day-of-week performance comparison
- Monthly and yearly trend analysis

**Insights:**
- Publishing day impacts early performance
- Seasonal effects are present across months
- Long-term growth improves as the channel matures

---

### 6️⃣ Audience & Monetization Analysis
Focused on:
- Views vs Subscribers Gained
- Thumbnail CTR vs Views
- CPM vs Revenue
- Audience Retention vs Views

**Insights:**
- High views do not always convert proportionally into subscribers
- Thumbnail CTR significantly affects video discoverability
- CPM strongly impacts monetization efficiency
- Higher audience retention supports sustained performance

---

## 📈 Tableau Dashboard Features
- Key KPIs for views, revenue, engagement, and subscribers
- Video-level performance comparison
- Time-based trend analysis
- Monetization and audience behavior insights
- Interactive filters for deeper exploration

---

## 📌 Key Insights
- YouTube performance metrics are **highly skewed**
- A small percentage of videos generate the majority of views and revenue
- Views are the strongest predictor of revenue
- Video duration alone does not guarantee success
- Thumbnail CTR plays a critical role in initial reach
- Audience retention is a strong indicator of long-term performance
- Monetization efficiency varies due to CPM and audience quality

---

## 🚀 Impact & Business Value
- Converts raw YouTube analytics into **actionable insights**
- Supports **content optimization and monetization strategies**
- Demonstrates a **real-world analytics + dashboard workflow**
- Strong portfolio project for analytics and digital intelligence roles

---

## 📌 Scope Clarification
This project is intentionally designed as a **data analytics (EDA-focused)** project.

---

## 🔮 Future Enhancements
- Feature engineering for predictive signals
- Machine learning models for view and revenue prediction
- Feature importance analysis to identify growth drivers

---

## 🧾 Conclusion
This project demonstrates a complete **YouTube analytics workflow**, transforming raw performance data into meaningful business insights.  
It highlights strong capabilities in **EDA, KPI analysis, visualization, and storytelling**, making it suitable for professional analytics roles.

---

## ✨ Author
**Ankur Maheshwari**  
Data Analytics Portfolio Project

---

⭐ If you find this project useful, consider giving it a star.

