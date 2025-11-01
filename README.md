# 🎬 Netflix Data Analysis

This project explores and visualizes data from the **Netflix Titles Dataset**, containing over 8,800 movies and TV shows available on Netflix.  
The analysis helps uncover insights into Netflix's content distribution, genres, release trends, and more.

---

## 📊 Project Overview

**Objective:**  
To analyze Netflix’s catalog and answer key questions such as:
- What is the proportion of Movies vs TV Shows?
- Which countries produce the most Netflix titles?
- What are the most common genres?
- How has Netflix’s content evolved over time?

---

## 🧠 Key Steps

1. **Data Loading:**  
   Imported the dataset `netflix_titles.csv` using pandas.

2. **Exploration:**  
   Viewed top records and dataset structure using `df.head()` and `df.info()`.

3. **Data Cleaning:**  
   - Removed duplicates  
   - Handled missing values  
   - Trimmed whitespace and formatted text  
   - Converted `date_added` to datetime format

4. **Analysis Performed:**  
   - Count of Movies vs TV Shows  
   - Top 10 content-producing countries  
   - Most common genres  
   - Distribution of release years  

5. **Visualization:**  
   Created bar and histogram plots using **Matplotlib** and **Seaborn** for:
   - Movies vs TV Shows count  
   - Yearly release distribution  
   - Top genres on Netflix  

6. **Conclusion:**
