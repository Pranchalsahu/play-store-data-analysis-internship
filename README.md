# Real-Time Google Play Store Data Analytics - Python Project

This project is part of the Data Analyst Internship at NullClass, focusing on real-time visual analytics using Python. The data used for this project is based on Google Play Store apps and includes various metrics like installs, reviews, ratings, size, revenue, etc.

---

##  Internship Tasks Overview

### Task 1: Scatter Plot with Trendline
- Visualize revenue vs. installs for paid apps.
- Add a trendline and color-code by app category.

### Task 2: Grouped Bar Chart with Time Filter
- Compare average rating and total review count for top 10 app categories.
- Filters: `Avg Rating >= 4.0`, `Size >= 10MB`, `Updated in Jan`.
- Visible only between 3 PM - 5 PM IST.

### Task 3: Dual Axis Chart (Installs vs. Revenue)
- Compare free vs. paid apps in top 3 categories.
- Multiple filters applied (installs, revenue, size, android version, content rating, app name length).
- Visible only between 1 PM - 2 PM IST.

### Task 4: Time Series Line Chart
- Monthly installs trend segmented by category.
- Filters on app name, reviews, and translated category names.
- Growth shading on >20% MoM increase.
- Visible only between 6 PM - 9 PM IST.

### Task 5: Bubble Chart
- Analyze size vs. rating, bubble size = installs.
- Filter on categories, rating, reviews, sentiment subjectivity, and app name.
- Translations and visual highlight for `Game` category.
- Visible only between 5 PM - 7 PM IST.

---


## Technologies Used

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- TextBlob (for sentiment analysis)
- NLTK
- Jupyter Notebook

---

## Note

All graphs are designed to appear only during their respective time windows, as per internship task requirements.

---


## Author

**Pranchal Sahu**  
M.Sc. Statistics (2nd Year)  
