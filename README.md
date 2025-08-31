# -djs-compute-tasks
UFC Fighters Data Analysis

This project analyzes a dataset of UFC fighters from Kaggle.  
It focuses on cleaning, exploring, and visualizing fighter statistics such as wins, losses, height, reach, and stance.

---

Dataset
Source: [Kaggle - UFC Fighters Statistics](https://www.kaggle.com/datasets/aaronfriasr/ufc-fighters-statistics)

---

Steps Performed
1. Data Cleaning
   - Removed duplicates
   - Handled missing values (median for numeric, mode for categorical)
   - Converted height/weight to numeric
   - Removed outliers using IQR

2. Exploration & Visualization
   - Weight distribution of fighters
   - Height vs Reach relationship
   - Wins vs Losses trends
---

 Insights
- Most fighters fall between 65–85 kg, aligning with popular weight classes.
- Taller fighters generally have greater reach.
- Orthodox stance is the most dominant style.
- Fight outcomes are not strongly dependent on weight class.

---

 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn

---
