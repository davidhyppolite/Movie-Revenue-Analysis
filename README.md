# 🎬 Movie Revenue Analysis

This project analyzes historical movie data to uncover trends in profitability, budget efficiency, and revenue forecasting. It uses Python for data cleaning, exploratory analysis, and regression modeling, and Tableau Public for interactive visualizations.

---

## 📁 Dataset
The data comes from the [Kaggle Movies Metadata Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset), which includes information on movie budgets, revenues, genres, runtimes, and release dates.

---

## 🧪 Python Analysis (Jupyter Notebook)

In Python, I:

- Cleaned and prepared movie metadata
  - Removed invalid rows, parsed dates, converted columns to numeric types
  - Engineered features like `profit` and `release_year`
- Visualized data using `matplotlib` and `seaborn`:
  - 📈 **Average Profit by Year**
  - 🏆 **Top 10 Most Profitable Movies**
  - 💣 **Top 10 Biggest Flops**
- Built a **linear regression model** to predict movie revenue using:
  - Budget, runtime, and release year
- Evaluated the model using R² and RMSE
- Plotted **Actual vs. Predicted Revenue** to visualize model performance

> 📂 Cleaned datasets for visualization were exported as `.csv` for Tableau.

---

## 📊 Tableau Public Dashboard

Explore the interactive dashboard 👉  
🔗 [View on Tableau Public]([https://public.tableau.com/app/profile/your-link-here](https://public.tableau.com/app/profile/david.hyppolite/viz/MovieRevenueAnalysisBoxOfficeFlopsandForecasting/Dashboard1?publish=yes))

### Tableau Features:
- 🎯 **Profit Trends Over Time** (Line chart)
- 🏆 **Top 10 Profitable Movies** (Bar chart)
- 💣 **Top 10 Flops** (Bar chart)
- 🔍 **Actual vs. Predicted Revenue** (Scatter plot with trend line)

The dashboard is fully interactive and showcases key insights in a business-friendly format.

---

## 🔧 Tools Used
- **Python**: pandas, seaborn, matplotlib, scikit-learn
- **Jupyter Notebook**
- **Tableau Public**
- **CSV & Excel** for dataset export

---

## 💡 Key Insights
- High-budget movies generally correlate with higher revenue, but not always higher profit
- Some low-budget films delivered massive returns
- Certain years (e.g., 1930) showed extreme outliers and required careful cleaning
- Linear regression gives decent revenue predictions (R² ≈ 0.55), though genre, star power, and marketing likely play a large role

---

## 📌 Next Steps
- Incorporate genre into regression model with one-hot encoding
- Analyze international vs. domestic revenue
- Include cast or director as predictive variables (if available)

---

👤 Created by [David Hyppolite](https://www.linkedin.com/in/davidhyppolite)  
📂 [More Projects on GitHub](https://github.com/davidhyppolite)
