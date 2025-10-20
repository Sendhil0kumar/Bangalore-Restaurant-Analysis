# Exploratory Data Analysis of Bangalore's Restaurant Market

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Zomato Bangalore Restaurants dataset. The project dissects various factors like location, cuisine, cost, and customer ratings to uncover strategic insights into Bangalore's competitive food industry.

---

## 🎯 Key Questions Addressed

This analysis was framed as a market research study to answer critical questions for a new restaurant venture:
1.  **Market Landscape**: Which locations in Bangalore have the highest density of restaurants and the most satisfied customers?
2.  **Competitive Analysis**: What are the most common and highest-rated restaurant types and cuisines?
3.  **Customer Preferences**: What factors, such as cost or cuisine, correlate with high ratings?
4.  **Pricing Strategy**: What is the typical price point for dining, and what is the relationship between cost and customer satisfaction?

---

## 🛠️ Methodology & Tools

* **Methodology**: The analysis follows the **Cross-Industry Standard Process for Data Mining (CRISP-DM)** framework.
* **Tools**: The project is implemented in a Jupyter Notebook using Python.
* **Libraries**:
    * **pandas** for data manipulation and cleaning.
    * **Matplotlib** and **Seaborn** for data visualization.
    * **WordCloud** for textual analysis of cuisines.

---

## 📈 Key Findings & Insights

* **Tier 1 Locations Identified**: **Koramangala** and **Indiranagar** were identified as top-tier locations, having both a high volume of restaurants and the highest average customer ratings.
* **Quality Over Price**: The analysis revealed only a **weak positive correlation between cost and rating**. This indicates that customers value quality and experience over price, presenting an opportunity for high-quality, affordable restaurants to thrive.
* **Market is Competitive**: The distribution of ratings is skewed towards the high end (avg. ~3.8), showing that the Bangalore market has high standards and a low tolerance for poor quality.
* **Healthy Food is a Niche**: While the market is dominated by North Indian and Chinese cuisines, "Healthy Food" exists as a smaller, less saturated niche, indicating a potential market opportunity.

---

## ⚠️ Data Limitations

It is important to note that this dataset is approximately **7 years old** (circa 2018). While specific restaurant listings and prices will be outdated, this analysis treats the data as a **historical benchmark** to understand the fundamental, long-term structure of Bangalore's food market. Core patterns such as neighborhood characteristics, dominant cuisines, and general customer price sensitivity are likely to remain relevant.

---

## 🚀 How to Run This Project

### 1. Download the Dataset
This project requires the Zomato Bangalore dataset, which is not included in this repository due to its large size.

* **Download the data from Kaggle:** [Zomato Bangalore Restaurants Dataset](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
* From the link, download the `zomato.csv` file.

### 2. Clone the Repository
Clone this repository to your local machine.
```bash
git clone [(http://localhost:8888/tree)](https://github.com/Sendhil0kumar/Bangalore-Restaurant-Analysis.git)
