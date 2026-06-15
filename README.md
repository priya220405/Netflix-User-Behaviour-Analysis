# 🎬 Netflix User Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-11557C)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> Exploratory Data Analysis on Netflix user data to uncover subscription patterns, viewing behavior, and demographic insights using Python.

---

## 📌 Project Overview

This project analyzes a Netflix user dataset containing **25,000 synthetic user records** to answer key business questions:

- Which subscription plan do most users prefer?
- Which age group has the highest engagement?
- What genres are most watched — and which drive the most watch time?
- Which countries have the highest user base?
- How many users are actively using Netflix vs inactive?

The goal is to simulate a real-world **Data Analyst role** — cleaning raw data, performing EDA, creating meaningful visualizations, and communicating business insights.

---

## 🗂️ Dataset

| Detail | Info |
|--------|------|
| Source | [Kaggle — Netflix Users Database](https://www.kaggle.com/datasets/smayanj/netflix-users-database) |
| Records | 25,000 users |
| Type | Synthetic (generated for analysis practice) |
| Format | CSV |

### Columns Used

| Column | Description |
|--------|-------------|
| `Age` | User age (13–80) |
| `Country` | Country of the user |
| `Subscription_Type` | Basic / Standard / Premium |
| `Watch_Time_Hours` | Monthly watch hours |
| `Favorite_Genre` | Most watched genre |
| `Last_Login` | Date of last login |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib | Base chart plotting |
| Seaborn | Statistical visualizations |
| Google Colab | Development environment |

---

## 📊 Visualizations (10 Charts)

| # | Chart | Insight |
|---|-------|---------|
| 1 | Age Distribution (Histogram + KDE) | Most users fall in 25–40 age range |
| 2 | Subscription Type Count (Bar) | Standard plan is most popular |
| 3 | Avg Watch Time by Subscription (Bar) | Premium users watch the most |
| 4 | Favorite Genre Distribution (Bar) | Drama and Comedy dominate |
| 5 | Avg Watch Time by Genre (Horizontal Bar) | Documentary watchers spend most time |
| 6 | Top 10 Countries by Users (Bar) | USA leads in user count |
| 7 | Age Group × Subscription Type (Heatmap) | 25–35 age group prefers Premium |
| 8 | Active vs Inactive Users (Pie) | ~30% users inactive in last 30 days |
| 9 | Correlation Heatmap | Age and Watch Time show weak correlation |
| 10 | Watch Time Boxplot by Subscription | Premium plan has higher median watch time |

---

## 🔍 Key Findings

- 📺 **Premium plan** users have the highest average monthly watch time
- 🎭 **Drama** is the most popular genre by user count
- 🎬 **Documentary** viewers spend the most time watching per session
- 🌍 **USA, UK, and Canada** are the top 3 countries by user count
- 👥 Age group **25–35** has the largest user base
- ⚠️ Around **30% of users** have not logged in within the last 30 days — a churn risk

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com)
2. Upload `netflix_analysis_colab.py`
3. Download dataset from [Kaggle](https://www.kaggle.com/datasets/smayanj/netflix-users-database)
4. Run cells top to bottom

### Option 2 — Local
```bash
# Clone the repo
git clone https://github.com/your-username/netflix-user-behavior-analysis
cd netflix-user-behavior-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run
python netflix_analysis.py
```

---

## 📁 Project Structure

```
netflix-user-behavior-analysis/
│
├── netflix_analysis_colab.py   # Main analysis code (Colab-ready)
├── netflix_users.csv           # Dataset (download from Kaggle)
├── plots/                      # Generated chart images
│   ├── 01_age_distribution.png
│   ├── 02_subscription_distribution.png
│   ├── 03_watchtime_subscription.png
│   ├── 04_genre_distribution.png
│   ├── 05_watchtime_genre.png
│   ├── 06_top_countries.png
│   ├── 07_agegroup_subscription_heatmap.png
│   ├── 08_active_inactive.png
│   ├── 09_correlation_heatmap.png
│   └── 10_watchtime_boxplot.png
└── README.md
```

---

## 💡 Skills Demonstrated

- ✅ Data loading and preprocessing
- ✅ Handling missing values and duplicates
- ✅ Feature engineering (Age Group, User Status)
- ✅ Exploratory Data Analysis (EDA)
- ✅ Statistical visualization with Seaborn and Matplotlib
- ✅ Correlation analysis
- ✅ Business insight generation from raw data

---

## 🎓 Internship Context

This project was completed as part of the **Data Science Internship at Skillinfytech IT Solutions**.

---

## 👩‍💻 Author

**Priyadharshini**
B.Tech — Artificial Intelligence & Data Science
Velalar College of Engineering and Technology, Erode

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/your-username)
