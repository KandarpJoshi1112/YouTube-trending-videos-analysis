# **YouTube Trend Analysis**

## 📑 **Project Overview**
This project analyzes trending YouTube videos in the US to uncover patterns and insights related to engagement metrics, title characteristics, and overall video performance. By leveraging data visualization and correlation analysis, the study aims to guide content strategies and enhance video performance.

---

## 📂 **Project Structure**

```
YouTube_Trend_Analysis/
│
├── Datasets/
│   └── USvideos.csv            # Dataset of US trending videos
├── requirements.txt             # Required libraries and dependencies
└── Youtube_Trend_Analysis.ipynb # Jupyter Notebook with analysis code
```

---

## 🚀 **How to Run the Project**

1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/YouTube_Trend_Analysis.git
cd YouTube_Trend_Analysis
```

2. **Install Required Libraries:**
```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook:**
```bash
jupyter notebook Youtube_Trend_Analysis.ipynb
```

---

## 📊 **Key Analysis & Findings**

### **1. Data Cleaning & Exploration**
- Null values in the `description` column were filled with empty strings.
- Key Statistics:
  - **Average Views:** ~2.36M | **Median Views:** ~681,861
  - **Average Likes:** ~74,266 | **Median Likes:** ~3,711
  - **Average Comments:** ~8,446 | **Median Comments:** ~1,856

### **2. Visualization Highlights**
- **Capitalized Words in Titles:**
  - 44% of trending video titles contain at least one fully capitalized word, possibly for emphasis or clickbait.
  
- **Title Length Analysis:**
  - Trending video titles are generally **30-60 characters** long.
  - No strong correlation between title length and views.
  - Videos with over **100M views** tend to have title lengths between **33-55 characters**.

- **Correlation Analysis:**
  - Strong positive correlation between **views** and **likes**, suggesting more popular videos also gain more likes.

- **Word Cloud Visualization:**
  - Showcased the most common words in video titles, offering insights into trending topics and keywords.

---

## 📈 **Engagement Metrics Analysis**

- **Top Categories by Engagement Rate:**
  - **Music (ID: 10):** 5.27%
  - **Howto & Style (ID: 26):** 5.22%
  - **Comedy (ID: 23):** 5.06%

- **Top Channels by Engagement Rate:**
  - **Daily Caller:** 22.29%
  - **Desimpedidos:** 22.10%
  - **KickThePj:** 19.43%

---

## 🛠️ **Technologies Used**
- **Python**: Data Analysis & Visualization
- **Pandas, Numpy**: Data manipulation
- **Matplotlib, Seaborn**: Data Visualization
- **WordCloud**: Visualization of most common words in titles
- **Jupyter Notebook**: Code execution and presentation

---

## 🧑‍💻 **Author**

**Kandarp Joshi**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kandarp%20Joshi-blue)](https://www.linkedin.com/in/kandarp-joshi-3451231bb/)

---

