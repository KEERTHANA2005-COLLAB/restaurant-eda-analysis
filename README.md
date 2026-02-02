# 🍽️ Restaurant Dataset Exploratory Data Analysis (EDA)

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a restaurant dataset to uncover valuable insights about restaurant ratings, pricing trends, cuisines, and service availability such as online delivery and table booking.

The goal is to understand customer preferences and identify patterns that influence restaurant performance.

---

## Objectives
The main objectives of this project are:

- Analyze the distribution of restaurant ratings  
- Explore popular cuisines and top restaurant cities  
- Study the relationship between price range and customer satisfaction  
- Examine how services like online delivery and table booking affect ratings  
- Visualize geographical distribution of restaurants  
- Apply basic feature engineering for enhanced analysis  

---

##  Dataset Information
The dataset contains detailed information about restaurants, including:

- Restaurant Name  
- City and Location  
- Cuisines  
- Average Cost for Two  
- Price Range  
- Online Delivery Option  
- Table Booking Option  
- Aggregate Rating  
- Customer Votes  

**Dataset Size:**  
- Rows: **9,551**  
- Columns: **21**

---

##  Data Cleaning & Preprocessing
Before analysis, the dataset was checked for:

- Missing values  
- Data types and inconsistencies  
- Null entries in columns such as **Cuisines**

This step ensures the dataset is ready for meaningful exploration.

---

##  Exploratory Data Analysis Performed

###  Rating Distribution
- Studied how restaurant ratings are distributed
- Most restaurants have ratings between **3 and 4**, indicating generally positive feedback

---

###  City and Cuisine Analysis
- Identified cities with the highest number of restaurants  
- Explored the most common cuisines offered  
- Visualized top cuisines using bar charts  

---

###  Geospatial Distribution
- Used latitude and longitude data to visualize restaurant concentration  
- Major cities showed higher restaurant density  
- No strong correlation was found between location and rating  

---

###  Online Delivery & Table Booking Insights
- Compared average ratings based on service availability  
- Restaurants offering **table booking** showed slightly better ratings  
- Online delivery was more common in mid-range restaurants  

---

###  Price Range Analysis
- Analyzed affordability patterns across restaurants  
- Higher price ranges tended to receive better average ratings  
- Visual comparisons were created for deeper understanding  

---

## 🛠 Feature Engineering
To improve usability for future modeling, additional features were created:

- **Restaurant Name Length**  
- Binary encoding for:
  - Table Booking Availability  
  - Online Delivery Availability  

These engineered features help convert categorical data into machine-readable format.

---

##  Key Insights
✔ Restaurants with **online delivery** tend to have slightly higher ratings  
✔ Table booking availability is linked with improved customer feedback  
✔ Medium price-range restaurants dominate the dataset  
✔ Higher-rated restaurants generally receive more customer votes  
✔ Restaurant location does not directly influence ratings  

---

##  Visualizations Included
- Distribution of Aggregate Ratings  
- Online Delivery Availability Chart  
- Top 10 Cities with Most Restaurants  
- Top 10 Cuisines  
- Geographical Scatter Plot  
- Average Rating by Price Range  

---

##  Tools & Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Data Analysis & Visualization  
- Feature Engineering  

---

##  Conclusion
This project demonstrates how exploratory data analysis can extract meaningful insights from real-world datasets.  
It strengthened my understanding of data preprocessing, visualization, and analytical reasoning using Python.

---

##  Author
**Sonti Krishna Keerthana**  
