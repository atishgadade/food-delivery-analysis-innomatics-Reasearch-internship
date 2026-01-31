# 🍔 Food Delivery Data Analysis

## 📖 Project Description
This project demonstrates an end-to-end data analytics workflow by integrating multiple real-world datasets related to a food delivery platform. Data from different file formats is merged to create a single, clean dataset for analysis and insight generation.

---

## 📊 Data Sources
The project uses three different data sources:
- **orders.csv** – Contains transactional order-level data
- **users.json** – Stores user profile and membership information
- **restaurants.sql** – Includes restaurant details such as cuisine and ratings

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook
- Anaconda

---

## 🔗 Data Integration Process
- Performed a **LEFT JOIN** between `orders.csv` and `users.json` using `user_id`
- Performed a **LEFT JOIN** between `orders.csv` and `restaurants.sql` using `restaurant_id`
- Ensured all order records were retained in the final dataset

---

## 📈 Analysis Highlights
- City-wise and cuisine-wise revenue distribution
- Comparison of Gold vs Regular member behavior
- Restaurant performance based on ratings and order value
- Seasonal and quarterly revenue trends

---

## 📁 Final Output
- **final_food_delivery_dataset.csv**  
  A consolidated dataset used as the single source of truth for all analysis

---

## 👤 Author
**Atish Gadade**
