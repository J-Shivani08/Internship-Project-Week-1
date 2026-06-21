# Internship-Project-Week-1
Week 1 Internship Project: House Price Prediction using Linear Regression and Random Forest models. Analyzed key drivers like total area and air conditioning.
# Internship Project — Week 1: House Price Prediction

## 📋 Project Overview
This repository contains the deliverables for Week 1 of the Internship Project. The objective was to build and evaluate a regression model to estimate house values using a real-world housing dataset, identifying the primary features that drive property valuation.

## 🔍 Key Insights & Summary (Task 5)
* **Most Influential Features:** A property's total **area (square footage)** is the single strongest driver of its final price. Secondary critical features include the availability of **air conditioning**, the number of **bathrooms**, and placement in a **preferred neighborhood area**.
* **Model Accuracy (Plain Terms):** The standard **Linear Regression** model achieved an **R² score of 0.6529**, meaning it successfully explains approximately **65.3%** of the price variations in the dataset. 
* **Data Surprises:** Cosmetic elements like furnishing status had significantly less weight in final market price variance than foundational structural features like **basements** or **guestrooms**.
* **Strategic Recommendation:** Real estate businesses looking to optimize ROI should focus on **acquiring larger-footprint properties and retrofitting them with central air conditioning systems** within high-demand preferred areas, rather than spending heavily on premium interior furnishing styles.

## 📊 Deliverables Included
* `Week1.ipynb`: Cleaned, well-documented Jupyter Notebook including data preprocessing, model execution, and performance evaluation metrics (MAE, RMSE, R²).
* `/charts`: Automatically generated and saved visualization plots:
  1. Price Distribution Histogram
  2. Area vs. Price Scatter Plot
  3. Air Conditioning Box Plot
  4. Model Accuracy Comparison Bar Chart
  5. Ranked Feature Influence Infographic Chart
