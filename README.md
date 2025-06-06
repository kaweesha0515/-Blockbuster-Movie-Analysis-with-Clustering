# 📽 Blockbuster Movie Clustering Analysis (1975–2015)

## 📌 Project Overview

This project explores trends, patterns, and groupings among the top 10 blockbuster movies from each year between *1975 and 2015. Using **K-means clustering* and data visualization techniques in *R*, the analysis focuses on identifying similarities and differences in audience reception, critical acclaim, financial success, and other key movie attributes.

The goal is to provide actionable insights into what defines a blockbuster in different decades, assisting researchers, studios, and film analysts in understanding the evolving cinematic landscape.

---

## 📊 Dataset

*Source:* [Data.World – Blockbuster Top Ten Movies per Year](https://data.world/crowdflower/blockbuster-database)

*Rows:* 399  
*Columns:* 20  
*Timeframe:* 1975–2015  

### Key Features Used:
- audience_freshness
- rt_audience_score
- rt_freshness
- rt_score
- 2015_inflation
- imdb_rating
- Length
- rank_in_year
- Studio
- worldwide_gross
- Year

Note: Non-essential columns such as poster URLs, genre fields, and release date were removed during preprocessing.

---

## ⚙ Methodology

### 🔄 Data Preprocessing
- Removed irrelevant or redundant columns.
- Converted data types for consistency.
- Handled missing values and ensured numerical compatibility for clustering.

### 🔍 Clustering Analysis
- *K-means Clustering*: Applied to group movies into clusters based on numerical and categorical variables.
- *Elbow Method*: Used to determine the optimal number of clusters (k).

### 📈 Visualization Tools in R
- ggplot2: For scatter plots and visual aesthetics.
- factoextra: To generate cluster plots, scree plots, and distance matrices.
- cluster: To implement clustering algorithms.

---

## 🧰 Tools & Technologies

- *R Programming Language*
- *Packages*:
  - cluster
  - factoextra
  - ggplot2
- *Data Source*: Data.world CSV file

---

## 📌 Key Insights

- Identified patterns across decades based on viewer ratings, box office performance, and critic scores.
- Grouped movies with similar characteristics, aiding understanding of blockbuster formulas.
- Provided visual interpretations that highlight market and audience shifts over time.

---
