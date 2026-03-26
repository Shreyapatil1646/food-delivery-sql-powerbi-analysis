# food-delivery-sql-powerbi-analysis
End-to-end Food Delivery Analytics project using SQL and Power BI. This project analyzes restaurant distribution, customer ratings, pricing impact, and cuisine trends across Indian cities using Swiggy dataset to deliver actionable business insights.
#  Food Delivery Analytics Dashboard (SQL + Power BI)

## 📌 Project Overview

This project is an end-to-end **Data Analytics solution** built using the Swiggy restaurant dataset. It focuses on extracting meaningful insights related to **customer preferences, pricing strategies, restaurant distribution, and cuisine trends** across multiple cities in India.

The project combines **SQL for data extraction and transformation** with **Power BI for interactive dashboard visualization**, enabling stakeholders to make data-driven decisions.

---

## 🎯 Objectives

* Analyze restaurant distribution across cities
* Evaluate the impact of pricing on customer ratings
* Identify top restaurant chains by presence
* Understand cuisine popularity trends
* Deliver actionable insights for business growth

---

## 🛠️ Tech Stack

* **SQL** → Data extraction, filtering, aggregations
* **Power BI** → Data visualization & dashboard development
* **Power Query** → Data cleaning and transformation
* **DAX** → KPI calculations and measures

---

## 📂 Dataset

* Source: Swiggy Restaurants Dataset[https://www.kaggle.com/datasets/ashishjangra27/swiggy-restaurants-dataset] (Kaggle)
  
* Features include:

  * Restaurant names
  * City locations
  * Pricing categories
  * Customer ratings & reviews
  * Cuisine types

---

## 📊 Dashboard Features

### 🔹 KPI Metrics

* Total Restaurants: 256K+
* Active Cities: 800+
* Average Customer Rating: 3.9
* Total Reviews: 16M+
* Top Rated Restaurants: 10K

---

### 🔹 Key Visualizations

* 📈 **Price Category vs Customer Ratings**
* 🏙️ **Top Cities by Restaurant Count**
* 🍔 **Top Restaurant Chains by Presence**
* 🗺️ **Geographical Distribution Map**
* 🍜 **Cuisine Popularity Share**
* 💡 **Key Insights Panel**

---

## 🧠 Key Insights

* Major metropolitan cities dominate restaurant presence
* Higher price categories are associated with better customer ratings
* A few cuisines contribute to the majority of demand
* Leading restaurant chains maintain strong multi-city presence

---

## 🗄️ SQL Analysis (Sample Queries)

Below are examples of SQL operations performed:

```sql
-- Top cities by restaurant count
SELECT city, COUNT(*) AS total_restaurants
FROM swiggy_data
GROUP BY city
ORDER BY total_restaurants DESC;

-- Average rating by price category
SELECT price_category, AVG(rating) AS avg_rating
FROM swiggy_data
GROUP BY price_category;

-- Top restaurant chains
SELECT restaurant_name, COUNT(*) AS outlets
FROM swiggy_data
GROUP BY restaurant_name
ORDER BY outlets DESC
LIMIT 10;
```

---

## 🔄 Project Workflow

1. Data Collection (Kaggle dataset)
2. Data Cleaning (Power Query)
3. Data Transformation (SQL + Power Query)
4. Data Modeling (Power BI relationships)
5. Dashboard Development (Power BI)
6. Insight Generation

---

## 📸 Dashboard Preview

(Food Delevery Analysis.png)

---

## 📁 Repository Structure

```id="x7k2lm"
├── data/                # Raw dataset
├── sql/                 # SQL queries
├── dashboard/           # Power BI (.pbix file)
├── images/              # Dashboard screenshots
└── README.md
```

---

## 🚀 How to Run the Project

1. Download dataset from Kaggle
2. Run SQL queries for analysis (optional)
3. Load data into Power BI
4. Apply transformations using Power Query
5. Explore dashboard insights

---

## 📌 Future Enhancements

* Add time-based trend analysis
* Build predictive model for ratings
* Perform customer segmentation
* Deploy dashboard using Power BI Service

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork and improve the project.

---

## 📧 Contact

* LinkedIn: (https://www.linkedin.com/in/shreya-patil-322177306/)
* Email: (patilshreya055@gmail.com)

---

⭐ If you found this project useful, consider giving it a star!
