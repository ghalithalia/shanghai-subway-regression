# 🚇 Shanghai Housing Price & Metro Distance Regression

This project explores the relationship between **housing price (per m²)** and **proximity to metro stations** in Shanghai.

The goal was to test whether real estate prices tend to decrease as the distance from the nearest subway station increases.

📍 Author: **Thalia Ghali**  
📅 Spring 2025 – UTSEUS, Shanghai University

---

## 📌 Summary

We used a cleaned dataset of 1,500+ real estate listings from Anjuke (2017) and calculated the **shortest distance** to the nearest metro station for each listing.

Then we performed a **linear regression** using:

- **X-axis**: Distance to subway (in meters)
- **Y-axis**: Housing price per m²

---

## 📉 Methodology

- Spatial filtering of housing data to focus on Shanghai
- Creation of a distance matrix to the subway network
- Regression model built with `Seaborn` and `Statsmodels`
- Statistical interpretation: R² score, coefficients, significance
- Visual analysis of scatterplots and regression lines

---

## 📄 Full Report

📥 [Click here to read the full PDF](./report/subway-price-regression-ghali.ipynb)

---

## 📊 Results

- The model shows a **weak negative correlation** between price and subway distance.
- R² score is relatively low, indicating other urban variables are likely more influential.
- The study suggests that proximity to metro **might not be sufficient alone** to predict pricing in Shanghai.

---

## 🛠 Tools

- Python (Pandas, Seaborn, Statsmodels)
- GIS data for housing and metro stations
- Visual interpretation of statistical outputs

---

Want to explore the notebook version or build on this? Reach out or check the notebook folder!
