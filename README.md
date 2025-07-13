# 🎬 IMDB Data Analysis & Prediction

Welcome to the IMDB Data Analysis project!
This project explores trends, patterns, and predictive insights using IMDB movie data spanning from the 1950s to the present. We analyze data, visualize insights, and build machine learning models to forecast movie profitability, rating, and age restrictions.

---

## 📌 Project Overview

We break the project into three key phases:

### 🗂 Phase 0: Data Gathering

* Web scraping using **Selenium** to automate browser interaction.
* Extracted rich movie metadata: title, year, duration, genre, budget, rating, metascore, gross, and more.
* Performed data cleaning, parsing, and structured dataset creation.

### 📊 Phase 1: Data Analysis

* **Exploratory Data Analysis (EDA)** with visualizations to understand key characteristics.
* Explored correlations, distributions, and genre-specific insights.

### 🤖 Phase 2: Modeling

* Built regression and classification models to:

  * Predict **rating**, **profit**, and **age restriction**.
  * Categorize movies based on financial performance and rating buckets.

---

## 🎯 Goals

* Understand what makes a movie successful in terms of profit and ratings.
* Analyze how genres, budget, and metascore influence profitability.
* Predict key attributes like rating and age restriction using machine learning.

---

## 🔍 Key Findings

* ✅ **Profit and budget** are positively correlated.
* 📉 Genres like **Mystery** show declining average ratings over the decades.
* 🤑 **Animation** consistently ranks among the top genres by average profit.
* 🎯 Higher **ratings** and **metascores** often align with profitable films.
* 📅 In recent decades, directors have become better at producing profitable movies.

---

## 📈 Models & Performance

### 🔬 Regression Models:

* **Linear, Ridge, Lasso, Gradient Boosting** and **Neural Networks**.
* Best performance: **Gradient Boosting** with R² ≈ 0.64 on test set.

### 🧠 Neural Network:

* Built custom neural network for regression.
* Achieved R² ≈ 0.62 — decent performance with room for tuning.

### 🌲 Random Forest Classifier:

* Used for classification tasks (e.g., age restriction).
* Applied **SMOTE** to balance the dataset.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
