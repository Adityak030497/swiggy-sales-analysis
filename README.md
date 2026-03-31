# 🍽️ Swiggy Sales Data Analysis

## 📌 Project Overview

This project analyzes Swiggy food delivery data to uncover insights related to sales trends, customer preferences, and restaurant performance. The analysis helps understand how different factors like location, category, and ratings impact overall business performance.

---

## 🎯 Objective

* Analyze sales trends over time (daily, monthly, quarterly)
* Understand customer behavior using ratings and order patterns
* Compare performance across food categories
* Identify top-performing locations and restaurants
* Generate actionable business insights

---

## 🛠️ Tools & Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## 📂 Dataset Description

The dataset contains food order details with the following columns:

* **State** – Location of order (e.g., Karnataka)
* **City** – City name (e.g., Bengaluru)
* **Order Date** – Date of order
* **Restaurant Name** – Name of the restaurant
* **Location** – Area within the city
* **Category** – Type of food (e.g., North Indian, Snacks, Recommended)
* **Dish Name** – Name of the dish ordered
* **Price (INR)** – Price of the dish
* **Rating** – Customer rating (out of 5)
* **Rating Count** – Number of ratings

---

## 📊 Key Performance Indicators (KPIs)

* 💰 Total Revenue (Sum of Price)
* ⭐ Average Rating
* 🧾 Total Orders
* 💵 Average Order Value
* 📈 Total Ratings Count

---

## 🔄 Workflow

1. **Data Loading**
2. **Data Understanding**
3. **Data Cleaning**

   * Checked missing values
   * Removed duplicates
4. **Feature Engineering**

   * Extracted Month, Day, Quarter from Order Date
   * Created time-based trends
5. **Exploratory Data Analysis (EDA)**
6. **Data Visualization**

---

## 📈 Visualizations

* 📅 Monthly Sales Trend
* 📊 Daily Order Analysis
* 🍽️ Category-wise Distribution
* 🌍 Location-wise Revenue
* 🏙️ Top Restaurants & Cities
* 📉 Quarterly Performance

*(Add chart images in the images folder and link them here)*

---

## 🔍 Key Insights

* 📌 Sales fluctuate over time, indicating seasonal demand patterns.
* 📌 Certain days contribute more orders, suggesting peak demand periods.
* 📌 A small number of restaurants generate a large portion of revenue.
* 📌 Popular categories like North Indian and Recommended dominate sales.
* 📌 Higher-rated dishes tend to have more consistent demand.

---

## 💡 Business Recommendations

* 🚀 Promote top-performing categories to maximize revenue.
* 📅 Increase offers during low-demand days.
* 🌆 Focus marketing efforts on high-performing locations.
* ⭐ Improve low-rated dishes to enhance customer satisfaction.
* 🍽️ Highlight high-rated dishes for better conversions.

---

## 📁 Project Structure

```
swiggy-sales-analysis/
│
├── data/
│   └── swiggy_data.xlsx
│
├── images/
│   ├── monthly_trend.png
│   ├── daily_trend.png
│   └── category_distribution.png
│
├── swiggy_sales_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/swiggy-sales-analysis.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook
   ```

---

## 📌 Future Improvements

* Build an interactive dashboard (Power BI / Streamlit)
* Add restaurant-level performance analysis
* Perform rating vs price correlation analysis
* Improve category classification

---

## 🙌 Conclusion

This project demonstrates how structured data analysis can help uncover meaningful insights in the food delivery domain. It highlights patterns in customer preferences, pricing, and restaurant performance, enabling data-driven decisions.

---
