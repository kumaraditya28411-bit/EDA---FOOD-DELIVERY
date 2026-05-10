# Hungry Hours: Analyzing Peak Ordering Trends and Customer Preferences

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a food delivery dataset to uncover patterns in customer behavior, peak ordering times, and service preferences. By analyzing variables such as meal categories, cuisines, and delivery ratings, the project aims to provide insights into what drives consumer choices in the online food delivery ecosystem.

## 📊 Key Research Questions
* Which meal categories (Lunch, Snacks, Dinner, Breakfast) are most popular?
* Do customers prefer Vegetarian or Non-Vegetarian options?
* What is the ideal "Maximum Wait Time" for a customer before satisfaction drops?
* How significantly do restaurant ratings influence a user's decision to order?

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `pandas` (Data Manipulation)
  * `numpy` (Numerical Computing)
  * `matplotlib` & `seaborn` (Data Visualization)

## 🗂️ Dataset Description
The analysis was conducted on a dataset containing 499 rows and 23 columns, including:
* **Demographics:** Age, Gender, Marital Status, Occupation, Family Size.
* **Order Details:** Frequently ordered meal category, Preference (Veg/Non-Veg), Order Value, Delivery Time.
* **Feedback/Sentiments:** Restaurant Rating, Delivery Rating, Health Concerns, Late Delivery, and Influence of Rating.

## 🚀 Data Cleaning Process
1. **Handling Missing Values:** Identified 12 total null values across columns like Gender, Occupation, and Maximum Wait Time. These rows were dropped to ensure data integrity.
2. **Column Standardization:** Stripped whitespace from column names for easier indexing.
3. **Data Types:** Ensured numerical columns (Age, Ratings, Order Value) and categorical columns were correctly formatted.

## 📈 Key Insights & Observations
* **Peak Trends:** **Lunch** is the dominant ordering period, followed closely by **Snacks**.
* **Dietary Preference:** A massive majority of users prefer **Non-Veg foods** for Lunch and Dinner.
* **Patience Threshold:** Most customers expect their food within **30 to 45 minutes**. Willingness to wait drops significantly after the 60-minute mark.
* **The Rating Effect:** Approximately **75.8%** of customers are influenced by ratings, proving that digital reputation is critical for restaurant success.

## 📝 Conclusion
The analysis suggests that food delivery platforms should optimize their logistics for the lunch rush and snacks period. Furthermore, maintaining high ratings is not just a "nice-to-have" but a primary driver of customer acquisition.

---
**Author:** Aditya Kumar  
