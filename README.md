# 📊 Google Play Store Analytics Dashboard

## 🔍 Overview

This project analyzes the Google Play Store dataset to extract insights on app performance, user engagement, and category trends. It includes **6 advanced visualizations** and a **time-controlled HTML dashboard** built using Python and Plotly.

---

## 🚀 Features

* Data cleaning & feature engineering (Installs, Size_MB, Revenue)
* Sentiment integration (Subjectivity)
* Complex multi-condition filtering
* 6 interactive Plotly visualizations:

  1. Bubble Chart (Size vs Rating vs Installs)
  2. Choropleth Map (Top categories by installs)
  3. Time Series (MoM growth >20%)
  4. Stacked Area (Cumulative installs, growth >25%)
  5. Grouped Bar (Ratings vs Reviews)
  6. Dual-Axis (Installs vs Revenue, Free vs Paid)
* Unified dashboard with **time-based visibility (IST)** using JavaScript

---

## 🧠 Tech Stack

* Python (Pandas, NumPy)
* Plotly (Interactive charts)
* HTML + JavaScript (Dashboard & time controls)

---

## 📁 Project Structure

```
data/                # Raw datasets
notebooks/           # Analysis notebook
outputs/             # All HTML charts + dashboard
report/              # Final internship report (PDF)
```

---

## 📊 How to Run

1. Clone the repository:

```
git clone https://github.com/<your-username>/google-playstore-analytics-dashboard.git
```

2. Open `notebooks/analysis.ipynb` and run all cells
3. Open `outputs/dashboard.html` in a browser

---

## ⏰ Time-Based Dashboard Logic

| Time (IST) | Visible Chart |
| ---------- | ------------- |
| 1–2 PM     | Dual Axis     |
| 3–5 PM     | Grouped Bar   |
| 4–6 PM     | Stacked Area  |
| 5–7 PM     | Bubble Chart  |
| 6–8 PM     | Choropleth    |
| 6–9 PM     | Time Series   |

---

## 📌 Key Insights

* High-rated apps tend to cluster between 10–40 MB sizes
* Significant install growth observed in select categories (MoM > 20%)
* Paid apps generate higher revenue but lower install volume

---

## 📎 Deliverables

* Interactive Dashboard (`outputs/dashboard.html`)
* 6 Visualization Files
* Internship Report (PDF)

---

## 👤 Author

Harshith Reddy Godha
