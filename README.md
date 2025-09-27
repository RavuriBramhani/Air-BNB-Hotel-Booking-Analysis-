# Air-BNB-Hotel-Booking-Analysis

# Airbnb Hotel Booking Analysis 🏨

## 📌 Project Overview
The hospitality industry has been transformed by online platforms that facilitate short-term lodging and tourism.  
This project focuses on analyzing **New York City Airbnb data** to extract meaningful insights about property types, neighborhoods, pricing, host activity, and customer satisfaction.  

By performing **data cleaning, exploratory data analysis (EDA), and visualizations**, the study helps stakeholders understand the dynamics of Airbnb’s marketplace.

---

## 🎯 Objectives / Questions Answered
This project aims to uncover insights from the Airbnb Open Data by answering the following:

1. What are the different property types in the dataset?  
2. Which neighborhood group has the highest number of listings?  
3. Which neighborhood group has the highest average prices?  
4. Is there a relationship between the construction year of property and price?  
5. Who are the top 10 hosts by calculated host listing count?  
6. Are hosts with verified identities more likely to receive positive reviews?  
7. Is there a correlation between the price of a listing and its service fee?  

---

## 📂 Dataset
- File format: `.xlsx`  
- Contains Airbnb listings with columns such as:  
  - `property_type`  
  - `neighbourhood_group`  
  - `price`  
  - `construction_year`  
  - `host_id`  
  - `host_identity_verified`  
  - `review_scores_rating`  
  - `service_fee`  

> ⚠️ Ensure that your dataset is uploaded into **Google Colab** before running the code.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas** (Data Manipulation)  
- **Seaborn & Matplotlib** (Visualization)  
- **Google Colab** (Execution Environment)  
- **OpenPyXL** (for reading Excel files)  

---

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload the notebook (`airbnb_analysis.ipynb`) and the dataset (`airbnb_data.xlsx`).  
3. Install required libraries:
   ```bash
   !pip install pandas matplotlib seaborn openpyxl
