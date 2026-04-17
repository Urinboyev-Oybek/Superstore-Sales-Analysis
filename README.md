# Superstore Sales Data Analysis 📊

This project focuses on analyzing the sales data of a "Superstore" retail chain in the United States. The primary goal is to evaluate sales performance, identify profitable and unprofitable products, and provide data-driven recommendations for business growth.

## 📂 Repository Contents

* **`Superstore_Sales_Analysis.ipynb`**: The main Jupyter Notebook containing data cleaning, manipulation, exploratory data analysis (EDA), and data visualization.
* **`Sample - Superstore.csv`**: The dataset used for the analysis. It includes information on customers, orders, product categories, sales volume, discounts, and profit.

## 🛠️ Technologies & Libraries Used

* **Python**
* **Pandas** (Data Manipulation & Cleaning)
* **Matplotlib & Seaborn** (Data Visualization)

## 💡 Key Insights & Business Recommendations

Based on the exploratory data analysis, the following key insights were discovered:

1. **Unprofitable Product Lines:** From the charts, we can see that the most significant losses came from *Tables*, *Supplies*, and *Bookcases*. If we look at their profit margins, they have been negative for almost all of the past 4 years. During 2014-2016, the company's annual profit margin increased, but it decreased in 2017 by 0.3%. This means that the overall annual profit increased mainly due to an increased sales volume. 
   * **Recommendation:** I recommend either dropping Tables, Bookcases, and Supplies from the product line or finding cheaper ways for their production and logistics. By solving this issue, the company can prevent an annual profit loss of around 8%.

2. **Impact of Discount Rates:** If we look at the Total Profit and Total Sales for each discount rate, we can observe that the profit becomes negative when the discount rate is more than 25%. Moreover, most of the profit came from sales where the offered discount rate was exactly 0% or 20%. 
   * **Recommendation:** I suggest keeping the maximum discount rate at 20% unless there is an exceptionally important contract.

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone [https://github.com/Urinboyev-Oybek/Superstore-Sales-Analysis.git](https://github.com/Urinboyev-Oybek/Superstore-Sales-Analysis.git)
2. Install the required libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```
3. Run the Jupyter Notebook:

```bash
jupyter notebook
```
Open 240219.ipynb in your browser and run the cells.
