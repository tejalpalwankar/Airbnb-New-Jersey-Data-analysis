# 🏠 Airbnb Data Insights – Jersey City

**Visual Analytic Dashboards Project | IST 737.M002 – Fall 2024**

This project leverages **Tableau** and **Python** to provide a comprehensive analysis of Airbnb listings in **Jersey City, New Jersey**. It includes interactive dashboards and exploratory data analysis to uncover pricing trends, room type patterns, host behavior, and more.

---

## 📊 Project Description

The analysis focuses on:

- 📈 **Pricing patterns**
- 🛏️ **Room type distribution**
- 🏙️ **Neighborhood trends**
- 💬 **Review volume**
- 🧑‍💼 **Host activity and verification**

Interactive Tableau dashboards are paired with Python-based EDA to uncover actionable insights for Airbnb stakeholders.

---

## 🧪 Python-Based Analysis

Alongside Tableau, a Jupyter notebook was used for cleaning, exploring, and analyzing the Airbnb dataset.

### 🔧 Dataset Cleaning & Preprocessing
- Null value handling and column selection
- Normalization of pricing and availability data

### 📊 Exploratory Insights
- **Correlation Analysis**: 
  - *Reviews per month* moderately correlates with *availability_365*, indicating more available listings receive more reviews.
  - *Price* shows weak correlation with review count and availability, suggesting other factors like amenities or location may drive pricing strategy.

### 🎻 Violin Plot:
- Visualization of **neighborhood vs. availability**, revealing distribution of stay frequency across locations.

The notebook provides additional plots, groupings, and analysis to complement the Tableau dashboards.

---

## 📁 Data Sources

All data was sourced from [Inside Airbnb](https://insideairbnb.com/get-the-data/):

| File | Description |
|------|-------------|
| [`listings.csv.gz`](https://data.insideairbnb.com/united-states/nj/jersey-city/2024-09-21/data/listings.csv.gz) | Detailed listings data |
| [`calendar.csv.gz`](https://data.insideairbnb.com/united-states/nj/jersey-city/2024-09-21/data/calendar.csv.gz) | Availability and price data |
| [`reviews.csv.gz`](https://data.insideairbnb.com/united-states/nj/jersey-city/2024-09-21/data/reviews.csv.gz) | Detailed review-level data |
| [`listings.csv`](https://data.insideairbnb.com/united-states/nj/jersey-city/2024-09-21/visualisations/listings.csv) | Summary metrics for listings |
| [`reviews.csv`](https://data.insideairbnb.com/united-states/nj/jersey-city/2024-09-21/visualisations/reviews.csv) | Aggregated review summaries |

---

## 📌 Dashboards Overview
![image](https://github.com/user-attachments/assets/9b5a2803-d0ff-4dc4-85ee-ce0c9bd89893)

### 📍 Dashboard 1 – Market Overview
- Total listings, average prices, and host counts.
- Map-based spatial distribution.
- Room-type-wise average pricing trends.
![1734495739271](https://github.com/user-attachments/assets/2fadb5bf-609c-42b8-a8cc-682968777240)


### 💰 Dashboard 2 – Pricing Analysis
- Seasonal and daily price patterns.
- Neighborhood and room-type pricing breakdowns.
- Heatmap of average prices across days/months.
![1734495738119](https://github.com/user-attachments/assets/6fd0f88c-fbc1-4292-bcc9-eace80268b17)


### 👤 Dashboard 3 – Host Analysis
- Superhost vs Regular host metrics.
- Host verification status and financial performance.
- Top contributing hosts and their impact.
![1734495737580](https://github.com/user-attachments/assets/72751615-fade-4db6-a49a-2268c6dd9242)

---

## ✅ Key Takeaways

- High-performing neighborhoods identified via pricing and review trends.
- Seasonal pricing strategies validated through weekday/month breakdown.
- Host verification and superhost status correlate with guest engagement.

---

## 🧠 Conclusion

This dual approach—**Tableau for visual storytelling** and **Python for exploratory data analysis**—equips stakeholders with deeper, more holistic insights into the Airbnb rental landscape in Jersey City.
