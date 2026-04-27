# U.S. Nicotine (E-Cigarette) Consumption Trend Analysis — 2020–2025

## Project Overview

This project presents a comprehensive analysis of U.S. e-cigarette consumption trends from 2020 to 2025 using a multi-dimensional retail dataset.

The objective is to uncover market dynamics, consumer behavior patterns, regulatory impacts, and pricing trends through structured analysis and interactive visualizations.

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Plotly
* Jupyter Notebook
* Kaggle

---

## Dataset Description

The dataset spans approximately 70 months (2020–2025) and includes:

* 51 U.S. states
* 10 major e-cigarette brands
* 2 product types (Disposable and Refillable)
* 7 flavor categories

### Feature Engineering

* Extracted time-based features:

  * Year
  * Month
  * Quarter
* Enabled longitudinal and seasonal analysis

---

## Analytical Pipeline

Developed an 8-stage analytical workflow:

1. National consumption trends
2. Product type evolution
3. Flavor category analysis
4. Brand market share tracking
5. State-level geographic analysis
6. Regulatory impact assessment
7. Price trend modeling
8. Cross-dimensional insights

---

## Key Insights

* Total unit sales grew by approximately 20.8%
* Revenue exceeded $3.4B by 2024
* Average prices increased from about $9 to over $14
* Disposable products expanded from 15% to 68% market share
* JUUL market share declined significantly (from ~45% to below 18%)
* Flavor bans reduced sales by around 14% in affected states
* Top 5 states accounted for roughly 38% of total sales

---

## Data Visualization

Interactive dashboards were built using Plotly, including:

* Choropleth maps for geographic distribution
* Stacked area charts for market trends
* Funnel charts for product transitions
* Scatter plots for price-demand relationships

---

## Business Value

* Highlights emerging product trends
* Evaluates regulatory effectiveness
* Tracks competitive brand dynamics
* Supports pricing and market strategy decisions
* Identifies high-performing geographic regions

---

## Project Structure

```bash
US-Nicotine-Trend-Analysis/
│
├── data/
├── notebooks/
├── README.md
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/US-Nicotine-Trend-Analysis.git
```

2. Navigate to the folder:

```bash
cd US-Nicotine-Trend-Analysis
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

* Time-series forecasting (ARIMA, Prophet)
* Predictive modeling for demand
* Dashboard deployment (Streamlit or Power BI)
* Integration with external policy datasets
