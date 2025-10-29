# 🎬 Netflix Data Cleaning & Exploratory Data Analysis

## 📌 Project Overview
This project analyzes Netflix titles data to explore what type of content is added on the platform.  
It includes thorough data cleaning and visual analysis to uncover trends in content type, rating distribution, and global content focus.

Dataset Source: Netflix Titles Dataset from Kaggle

---

## 🎯 Key Insights
- ✅ Movies make up ~70% of titles on Netflix  
- 🔞 TV-MA and TV-14 dominate the ratings → more adult content  
- 🌍 International TV & Movies (e.g., Drama) appear most frequently  
- 📈 Strong growth in fresh content after 2015  
- 🧹 Cleaned major issues in `duration`, `rating`, and `date_added` fields

---

## 🧹 Data Cleaning Steps
- Converted date fields to DateTime format  
- Removed or corrected inconsistent rating & duration values  
- Handled missing values with imputation  
- Added new columns for improved analysis  

---

## 📊 Exploratory Data Analysis (EDA)
Includes:
- Type distribution (Movies vs TV Shows)
- Top content ratings
- Trend of content addition by year
- Genre/category popularity

📌 *Attach your visualization images here for best presentation*

---

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Run
```bash
git clone <your_repo_link>
pip install -r requirements.txt
jupyter notebook
