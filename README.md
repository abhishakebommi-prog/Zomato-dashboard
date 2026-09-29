# 🍽️ Zomato Restaurant Analytics 

> An end-to-end exploratory data analysis and interactive Power BI dashboard evaluating global restaurant performance, customer satisfaction metrics, and digital delivery trends.

---

## 🚀 Overview
This project analyzes Zomato's global restaurant dataset to uncover market trends, pricing strategies, and customer sentiment. Built for portfolio presentation and recruiter evaluation, it combines robust data modeling (Star Schema), advanced DAX measures, and clean UI/UX design principles to deliver actionable business insights.

---

## 📊 Key Features & Dashboard Preview
* **Executive KPI Cards:** Total restaurants (~9.5K), total votes, and volume-weighted average ratings.
* **Geographic Drill-Downs:** Interactive maps and city-level distribution rankings (highlighting high-density hubs like New Delhi).
* **Operational Analytics:** Donut charts tracking the adoption rate of **Online Delivery** and **Table Booking** features.
* **Pricing & Cuisine Distributions:** Histogram and bar charts analyzing average costs for two and popular cuisine categories.

---

## 🛠️ Tech Stack & Architecture
* **Data Modeling:** Star Schema (Fact table: `Restaurants`; Dimension tables: `Countries`, `Calendar`).
* **ETL & Data Prep:** Power Query (Data cleaning, type validation, and error handling).
* **Visualization:** Power BI (Custom thematic styling, slicer filter panels, and responsive layout).
* **Data Analysis Language:** DAX (Custom iterators and aggregations).

---

## 📈 Key DAX Measures
To ensure customer satisfaction scores accurately reflect review volume rather than unweighted averages, a custom weighted rating measure was implemented:

## Screenshot of dashboard
* **Dashboard look like https://github.com/abhishakebommi-prog/Zomato-dashboard/blob/main/snapshot%20zomato.png
