# netflix-data-analysis-powerbi
An end-to-end analysis of Netflix's movie and show library using Python for data cleaning and Power BI for interactive visualizations.
# 📊 Netflix Content Analysis | Python EDA + Power BI Dashboard

An end-to-end data analysis project on Netflix's content library using **Python for data preprocessing and EDA**, followed by an **interactive Power BI dashboard** for visual storytelling and insights.

---

## 📁 Project Overview

This project explores Netflix's vast library of movies and TV shows to extract meaningful insights into genres, directors, IMDb ratings, runtimes, and global availability.  
The process includes:
- Comprehensive data cleaning and feature engineering in Python
- Outlier detection, correlation analysis, and export to Excel
- Interactive Power BI dashboard creation with slicers, tooltips, and custom visuals

---

## 🐍 Python EDA Summary

A full exploratory data analysis was conducted before dashboarding:

1. **Column Standardization**  
   - Renamed all columns to snake_case following INC naming rules.

2. **Duplicate & Null Handling**  
   - Removed duplicate rows.
   - Dropped columns with excessive null values offering no analytical insights.

3. **Data Type Correction**  
   - Ensured proper data types (e.g., datetime, numeric, categorical).

4. **Data Overview**  
   - Used `.describe()` for statistical summary and basic distribution check.

5. **Outlier Detection & Treatment**  
   - Detected outliers via **boxplots**.
   - Treated them using the **IQR method** to preserve analytical integrity.

6. **Correlation Analysis**  
   - Generated a heatmap to examine relationships between numerical features.

7. **Export for BI**  
   - Cleaned data exported to Excel for visualization in Power BI.

📦 **Libraries Used**: `pandas`, `numpy`, `seaborn`, `matplotlib`

---

## 📊 Power BI Dashboard Summary

The polished dataset was used to build an **interactive Power BI dashboard**, themed in Netflix-style colors (black, red, white), featuring:

### 🔹 Key Features:
- **KPI Cards**  
  - Total Titles: 3,001  
  - Average IMDb Score: 6.78  
  - Global Availability: 659 Countries

- **IMDb Score Classification**  
  - Segmented into Excellent, Good, Average, Poor

- **Top Directors Visualization**  
  - Ranked by number of titles contributed

- **Genre Analysis**  
  - Pie chart for genre distribution  
  - Tooltip **treemap**: Genre by average IMDb score (on hover)

- **Country Reach**  
  - Overview of Netflix's global distribution footprint

### 🔸 Interactivity:
- Slicers: Content type filter (Movies or Series)
- Custom Tooltips: Hover-based details (e.g., genre ratings)
- Responsive layout with clean visual hierarchy

---

## 📈 Key Insights

- **Drama** is the most frequent and highly rated genre
- **Longer runtimes** correlate with better IMDb scores
- A few top **directors** contribute heavily to the content pool
- Netflix is available in **659 countries**, showing massive global reach

---

## 💼 Business Recommendations

- 🎭 **Invest in Long-Form Drama**: It consistently performs well with viewers.
- 👨‍🎬 **Secure High-Performing Directors**: Partner with those having strong IMDb track records.
- 🌍 **Boost Regional Content**: Focus on localized, high-rated content to deepen engagement in specific countries.
- 🕵️‍♀️ **Promote Strong Genres**: Use genres with high IMDb averages in marketing for better viewer response.

---

## 📂 Dataset

- **Source**: https://www.kaggle.com/datasets/ashishgup/netflix-rotten-tomatoes-metacritic-imdbs/ashishgup/netflix-rotten-tomatoes-metacritic-imdb

---

## 🧰 Tools & Technologies

| Tool        | Purpose                    |
|-------------|----------------------------|
| Python      | Data Cleaning & EDA        |
| Pandas, Numpy | Data Transformation     |
| Seaborn, Matplotlib | Visualization    |
| Power BI    | Dashboarding & Storytelling|
| Excel       | Data Export                |

## 🧠 Author

**[Priya Singhal]** – Aspiring Data Analyst  
📬 https://www.linkedian.com/in/priya-singhal-829a2624b/ 

## ⭐️ Feel free to fork, star, or contribute!


