# Coupon Acceptance Analysis  
**Project for Assignment 5.1: Will the Customer Accept the Coupon?**  
_First Practical Application Assignment_  
Course: **Professional Certificate in Machine Learning and Artificial Intelligence by Berkeley**  
**By: Erfan Maleki**

---

##  Overview
This project analyzes customer behavior to predict whether they will accept in-vehicle coupons under various conditions such as time of day, weather, passengers, destination, and coupon type.  
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation).

---

##  Objective
The main goal is to identify the differences between customers who accept coupons and those who do not and provide actionable recommendations for targeted marketing strategies.

---

##  Dataset Details
The dataset includes:
- **Destination**: Home, work, or no urgent place
- **Time of Day**
- **Passenger**: Alone, Friend, Partner, or Kid
- **Weather**: Sunny, Rainy, or Snowy
- **Coupon Type**: Coffee House, Bar, Carry-out, and Restaurants
- **Target Variable (Y)**:  
  - `1` → Accepted the coupon  
  - `0` → Did not accept the coupon  

---

##  Tools and Libraries
- **Python**
- **pandas** – Data handling
- **matplotlib & seaborn** – Visualizations
- **Jupyter Notebook** – Interactive analysis

---

##  Key Insights
- Coffee House and Carry-out coupons have the **highest acceptance rates**.
- Younger customers (**ages 21–30**) are most likely to accept coupons.
- Drivers with friends or partners show higher acceptance rates.
- Acceptance rates are higher in clear weather.
- Expensive restaurant coupons have the lowest acceptance rates.

---

##  Recommendations
- Focus promotions on **Coffee House** and **Carry-out coupons** for younger drivers.
- Offer discounts during **weekends and social trips**.
- Avoid promoting expensive restaurant coupons during **bad weather**.
- Use **context-aware targeting** for improved conversion rates.

---

##  Repository Structure


| File                                | Description                                  |
|-------------------------------------|----------------------------------------------|
| `Practical_Application_1.ipynb`     | Main Jupyter Notebook with analysis          |
| `in-vehicle-coupon.csv`             | Dataset used for the project                 |
| `Coupon Acceptance Analysis.docx`   | Extended report with code and plots          |
| `README.md`                         | Project description and instructions         |
| `LICENSE`                           | MIT License                                  |




## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/erfmlk/coupon-acceptance-analysis.git
   cd coupon-acceptance-analysis



