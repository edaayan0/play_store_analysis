# 📱 Google Play Store App Analysis

This repository contains an Exploratory Data Analysis (EDA) of the Google Play Store dataset. The project explores the dynamics of the mobile app market by analyzing app categories, ratings, reviews, and installation trends using Python's data science ecosystem.

## 🚀 Project Overview
The main goal of this analysis is to understand what makes an app successful on the Play Store. The notebook covers:
* **Data Cleaning:** Handling missing values, removing duplicates, and converting data types (e.g., converting "Installs" and "Price" to numeric values).
* **Statistical Analysis:** Distribution of app ratings and category-wise performance.
* **Visualization:** Creating insightful charts using Seaborn, Matplotlib, and interactive Plotly graphs.

## 📊 Dataset
The dataset is sourced from **Kaggle**: [Google Play Store Apps](https://www.kaggle.com/datasets/shivamb/netflix-shows). It contains details for over 10,000 apps, including:
- **Category:** Genre of the app (e.g., Family, Game, Tools).
- **Rating:** Average user rating.
- **Reviews:** Number of user reviews.
- **Installs:** Number of user downloads.
- **Type:** Free or Paid.
- **Content Rating:** Target audience (Everyone, Teen, etc.).

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** - `Pandas` & `NumPy` for data manipulation.
  - `Matplotlib` & `Seaborn` for static visualization.
  - `Plotly` for interactive data exploration.

## 📈 Key Insights
* **Rating Distribution:** Most apps maintain a high rating, with a peak frequency around 4.2 to 4.5.
* **Market Share:** Analyzed the top-performing categories (e.g., "Family" and "Game" categories often lead in volume).
* **Data Integrity:** Identified and cleaned approximately 1,474 missing values in the "Rating" column to ensure accurate analysis.

