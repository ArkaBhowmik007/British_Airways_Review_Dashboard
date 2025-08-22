# ✈️ British Airways Review Dashboard

## 📌 Project Overview

This project presents an **interactive Tableau dashboard** built using **British Airways review data**.
The dashboard provides insights into customer sentiment, service ratings, and overall experience across different countries.

By blending **two datasets – Countries and Reviews**, the project highlights patterns in passenger feedback and allows users to explore how satisfaction varies by region, rating categories, and customer profiles.

---

## 🎯 Objectives

* To analyze **customer reviews** of British Airways.
* To understand **regional differences** in customer satisfaction.
* To blend multiple datasets for a holistic view.
* To create an **interactive dashboard** for business decision-making.

---

## 📂 Datasets

1. **Countries Dataset**

   * Contains country-level details.
   * Used for mapping customer reviews geographically.

2. **Reviews Dataset**

   * Includes customer reviews and ratings.
   * Attributes: Review Title, Review Text, Date, Country, Rating (e.g., Value for Money, Seat Comfort, Cabin Staff, Entertainment, Food & Beverages).

---

## 🔄 Data Preparation & Blending

* **Data Cleaning:** Removed duplicates, handled missing values, and standardized fields.
* **Blending:** Linked the **Countries dataset** with **Reviews dataset** using the **Country field**.
* **Calculated Fields:** Derived metrics such as average rating, sentiment score, and % of positive/negative reviews.

---

## 📊 Dashboard Features

* 🌍 **Geographical Map:** Distribution of reviews by country.
* ⭐ **Average Ratings:** Breakdown across multiple service dimensions (Food, Comfort, Staff, Entertainment).
* 📈 **Trend Analysis:** Reviews over time.
* 📝 **Sentiment Insights:** Positive vs. Negative review distribution.
* 🔍 **Interactive Filters:** Explore data by year, rating type, and region.

---

## 🛠️ Tools & Technologies

* **Tableau Desktop / Tableau Public** – Visualization & Dashboarding
* **Excel/CSV** – Raw datasets (Countries & Reviews)

---

## 🚀 Key Insights

* Identified **top countries** contributing the most reviews.
* Found correlations between **cabin staff service** and **overall satisfaction**.
* Discovered that **value for money ratings** significantly impacted customer sentiment.
* Highlighted **time-based trends** in review scores (seasonal patterns).

---

## 📌 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/british-airways-review-dashboard.git
   ```
2. Open the `.twbx` Tableau workbook in **Tableau Desktop** or view on **Tableau Public**.
3. Interact with filters, maps, and charts to explore insights.

---

## 📷 Dashboard Preview

img src="/British_Airways.png" alt="Netflix_Dashboard"/>



---

## 🌟 Future Improvements

* Add **sentiment analysis using NLP** for deeper review text insights.
* Automate data refresh with APIs for **real-time review tracking**.
* Build predictive models to estimate **future customer satisfaction trends**.

---
