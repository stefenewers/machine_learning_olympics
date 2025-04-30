# 🏅 Olympic Medals Predictor (Linear Regression Project)

Welcome to my very first machine learning project!  
This beginner-friendly model predicts how many medals a country might win at the Olympics based on how many athletes it sends. Built using Python and linear regression, this project was guided by [DataQuest's YouTube tutorial](https://www.youtube.com/@Dataquest) and expanded to improve my understanding of machine learning, data wrangling, and visualization.

---

## 📊 Project Overview

**Goal:**  
Use a simple linear regression model to predict Olympic medal counts based on athlete count per country.

**Technologies Used:**
- Python 3
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## 📁 Datasets

We used the following datasets:

- [`athlete_events.csv`](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results): Historical data on Olympic athletes and results.
- `teams.csv`: Supplemental data containing team and NOC details.

---

## 🧠 Key Concepts Learned

- Data loading, cleaning, and manipulation using Pandas
- Aggregating athlete and medal data by country
- Handling edge cases like divide-by-zero errors and invalid predictions
- Visualizing data trends with histograms and regression plots
- Training and evaluating a simple linear regression model

---

## 📈 Visualizations

This project includes:

- **Histograms** to show distribution of athletes and medals
- **Scatter plots** with regression lines to visualize the relationship between athletes and medals

Example:

```python
# Histogram
df['Athletes'].hist()

# Regression plot
sns.regplot(x='Athletes', y='Medals', data=df)
