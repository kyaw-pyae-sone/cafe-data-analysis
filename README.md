# Analysis of Cafe's Dirty Data ☕

This project focuses on the end-to-end data mining process, starting from raw, "dirty" cafe sales data to generating actionable association rules.

## 📌 Project Overview
The goal of this project is to clean a messy sales dataset and perform **Market Basket Analysis** to understand customer purchasing patterns.

### Key Features:
* **Data Preprocessing:** Handled missing values, removed unnecessary columns like "Payment Method," and corrected data types.
* **Outlier Detection:** Used Z-scores to identify and filter out noise from the transaction data.
* **Data Visualization:** Created visual breakdowns of top-selling items to identify trends.
* **Association Rule Mining:** Implemented algorithms to find dependencies between items (e.g., if a customer buys a Sandwich, how likely are they to buy Tea?).

## 🛠️ Tools Used
* **Python** (Jupyter Notebook)
* **Pandas & NumPy** for data manipulation.
* **Matplotlib** for data visualization.

## 📊 Results
The project successfully identified 244 association rules. For example:
* **Rule:** {Smoothie, Sandwich} -> {Tea}
* **Support:** 0.8
* **Confidence:** 0.94
* **Lift:** 1.01 (Indicates a positive dependency).

## 📂 Data Source
The dataset used in this analysis is the **Dirty Cafe Sales** dataset sourced from **Kaggle**. 
* **Source:** [https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training]
* **Description:** This dataset was specifically chosen for its "dirty" nature to demonstrate advanced data cleaning and preprocessing techniques in a real-world retail context.
