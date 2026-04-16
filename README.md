# Google Play Store Data Analysis Dashboard

## Project Overview
This project analyzes Google Play Store application data using Python, Pandas, Plotly, HTML, and CSS. The dashboard provides interactive visualizations to understand app performance, installs, reviews, ratings, revenue, growth trends, and category-based insights.

The project includes six different tasks with separate interactive charts and one combined dashboard that displays all graphs based on time conditions.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Plotly
- HTML
- CSS
- Jupyter Notebook

---

## Dataset Used
- Play Store Data.csv
- User Reviews.csv

---

## Features
- Data cleaning and preprocessing
- Interactive Plotly charts
- Time-based graph visibility
- Dashboard with hover descriptions
- Separate graph pages for detailed view
- Category translations into multiple languages
- Revenue and install analysis
- Growth trend analysis

---

## Project Tasks

### Task 1: Bubble Chart
Analyzes the relationship between app size and rating. Bubble size represents installs and categories are highlighted using different colors.

### Task 2: Choropleth Map
Displays global installs by category using ISO-3 country mapping and highlights categories with high installs.

### Task 3: Monthly Installs Trend
Shows monthly installs trend by category and highlights areas where monthly growth is greater than 20%.

### Task 4: Cumulative Installs Area Chart
Displays cumulative installs over time for selected categories and highlights months with more than 25% growth.

### Task 5: Rating vs Reviews
Compares average rating and total reviews for the top categories using a grouped bar chart.

### Task 6: Installs vs Revenue
Compares average installs and revenue between free and paid apps using a dual-axis chart.

---

## Folder Structure
```text
index.html
task_1_bubble_chart.html
task_2_global_installs_by_category.html
task_3_monthly_installs_trend_by_category.html
task_4_cumulative_installs_area_chart.html
task_5_rating_vs_reviews.html
task_6_installs_vs_revenue.html
playstore_dashboard.ipynb
Play Store Data.csv
User Reviews.csv
README.md
