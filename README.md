# 📊 Social Media Likes Analysis

## 📌 Project Overview
This project analyzes a simulated social media dataset (e.g., tweets) to identify trends in **likes** across different post categories. Using **Python**, the goal is to uncover patterns in user engagement and help marketing teams make **data-driven recommendations** for improving social media performance.

## 🗂 Categories Analyzed
- 🍔 Food  
- ✈️ Travel  
- 👗 Fashion  
- 🏋️ Fitness  
- 🎵 Music  
- 🎭 Culture  
- 👨‍👩‍👧 Family  
- 🏥 Health  

## 🛠 Tools & Libraries
- **Python** 🐍  
- Pandas — data handling  
- Seaborn / Matplotlib — data visualization  
- Jupyter Notebook — analysis environment  

## 🔍 Process
1. **Load Libraries** — Import required packages.  
2. **Load & Explore Data** — `head()`, `info()`, `describe()`.  
3. **Data Cleaning** — Check nulls (`isnull()`), drop duplicates, format dates, convert likes to integers.  
4. **Visualization** —  
   - Histogram of Likes distribution  
   - Boxplot of Likes by Category  
   - Bar plot of Average Likes per Category  

## 📈 Key Insights
- The histogram shows likes are evenly distributed, with no heavy skew toward extremes. 
- The boxplot highlights that Food and Music have slightly higher medians, while Health posts have the lowest median but wide variability. 
- The bar plot confirms Food has the highest average likes, followed by Music and Fitness, with Health trailing behind — suggesting room for content optimization.
