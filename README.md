 # 📺 YouTube 2025 Video Analytics & Visualization

An end-to-end **data analysis project** using **Python, Pandas, and Matplotlib** to explore YouTube video performance, engagement trends, and publishing patterns for the year 2025.

---

## 📌 Project Overview

This project analyzes YouTube video data from 2025 to understand:
- Viewership trends
- Engagement behavior (likes & comments)
- Monthly publishing patterns
- Top-performing videos and channels

The project focuses on **Exploratory Data Analysis (EDA)** and **advanced data visualization** to derive meaningful insights that can support content strategy and business decisions.

---

## 🎯 Objectives

- Identify the most viewed and most engaging videos  
- Analyze the relationship between views, likes, and comments  
- Detect peak months for viewership  
- Highlight outliers and high-performing content  
- Apply log-scale visualizations for skewed data  

---

## 📁 Dataset Description

The dataset contains YouTube video-level information with columns such as:

### Video Details
- `video_id`
- `title`
- `channel_name`
- `channel_id`

### Engagement Metrics
- `view_count`
- `like_count`
- `comment_count`

### Publishing Information
- `published_date`
- `published_month`

📌 Dataset is cleaned and processed within the notebook.

---

## 🛠 Tools & Technologies

| Task | Technology |
|----|----|
| Data Cleaning & Processing | Python (Pandas, NumPy) |
| Data Visualization | Matplotlib |
| Exploratory Analysis | Jupyter Notebook |

---

## 📊 Analysis & Visualizations

The project includes the following analyses:

### 🔹 Engagement Analysis
- Views vs Likes scatter plot using **log scale**
- Likes vs Comments relationship
- Outlier detection for highly viewed videos

### 🔹 Performance Analysis
- Top 5 most viewed videos with annotations
- Top channels by total views

### 🔹 Trend Analysis
- Monthly upload trend
- Monthly total views trend with **peak month annotation**

Advanced visualization techniques used:
- Logarithmic scaling
- Annotations
- Highlighting outliers
- Clean, presentation-ready charts

---

## 📈 Key Insights

- View and like counts are highly skewed, making log-scale visualization essential  
- A small number of videos contribute disproportionately to total views  
- Certain months show clear peaks in total viewership  
- High-view videos often act as outliers in engagement analysis  

---

## ▶️ How to Run This Project

### Prerequisites
Install required Python libraries:
```bash
pip install pandas numpy matplotlib
