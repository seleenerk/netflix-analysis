# Netflix Analysis Project

This project analyzes the **Netflix Movies and TV Shows dataset** (from Kaggle) to explore production trends by country and genre.

---

## Project Overview

Using Python (Pandas, Matplotlib, Seaborn), we examined over **8,800 Netflix titles** to uncover:

- Which countries produce the most Netflix content  
- Which genres are most common overall  
- How content genres differ between countries  

---

## What I Learned

- Loading and cleaning datasets with **pandas** 
- Visualizing data using **matplotlib** and **seaborn**
- Creating **pivot tables** and **heatmaps** to reveal patterns  

---

## Visualizations

### Top 10 Content-Producing Countries and Most Common Genres by Country
This bar chart shows which countries have the largest number of Netflix titles.
A heatmap showing which genres dominate in each of the top 10 producing countries.
```python
sns.barplot(x=top_countries.values, y=top_countries.index, palette="Reds_r")
sns.heatmap(pivot_top, cmap="YlOrRd", linewidths=0.5)

