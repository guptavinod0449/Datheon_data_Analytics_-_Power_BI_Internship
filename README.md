# Datheon_data_Analytics_-_Power_BI_Internship

# Superstore Retail Sales — Exploratory Data Analysis (EDA)

## 1. Project Overview

This project analyzes Superstore retail sales data using Python. The main goal is to understand sales and profit performance across different product categories, regions, and customer segments.
              
The project also studies monthly sales trends and the relationship between discounts and profit.

## 2. Project Objectives

- Understand the dataset and its structure.
- Identify and handle missing values.
- Convert Order Date into the correct date format.
- Create a Year-Month column for monthly analysis.
- Calculate total Sales and Profit by Category, Region, and Customer Segment.
- Visualize monthly sales trends.
- Analyze the relationship between Discount and Profit.
- Identify useful business insights from the data.

## 3. Tools and Libraries

- **Python** — Programming language
- **Jupyter Notebook** — To write and run the analysis
- **Pandas** — Data cleaning and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization

## 4. Dataset Information

The dataset contains retail sales information, including:

- Order ID and Order Date
- Customer Name and Segment
- Product Category and Sub-Category
- Region and State
- Sales, Quantity, Discount, and Profit

The original dataset contains **10,800 rows and 21 columns**. After cleaning, **9,994 rows** remain for analysis.

## 5. Data Cleaning

The following steps were performed:

- Checked missing values in each column.
- Identified 806 rows with missing key information.
- Cleaned the dataset to retain 9,994 usable records.
- Converted Order Date into a datetime format.
- Created a Year-Month column for monthly sales analysis.
- Checked missing values after cleaning.

**Note:** 11 missing values remain in the Postal Code column. They were not filled because Postal Code was not required for the current analysis.

## 6. Data Analysis and Visualization

The project includes the following analyses:

1. **Category-wise Analysis:** Compared total Sales and Profit across product categories.
2. **Region-wise Analysis:** Compared sales and profit across different regions.
3. **Customer Segment Analysis:** Studied Consumer, Corporate, and Home Office customers.
4. **Combined Analysis:** Compared Sales and Profit by Category, Region, and Segment.
5. **Monthly Sales Trend:** Identified changes in sales over time.
6. **Discount vs. Profit:** Examined the relationship between discounts and profit.
7. **Category-wise Sales Percentage:** Compared each category's contribution to total sales.
8. **Year-wise Sales:** Compared sales across different years.

## 7. Key Business Observations

### Category-wise Sales and Profit

- Technology has the highest sales of approximately **$836,154** and the highest profit of approximately **$145,455**.
- Furniture has sales of approximately **$742,000**, but its profit is only about **$18,451**.
- This shows that higher sales do not always mean higher profit.

### Region-wise Performance

- The West region has the highest sales of approximately **$725,458** and profit of approximately **$108,418**.
- The South region has the lowest sales of approximately **$391,722**.
- The business can study the West region's performance to identify ways to improve sales in other regions.

### Customer Segment Analysis

- The Consumer segment has the highest sales of approximately **$1.16 million** and profit of approximately **$134,119**.
- Corporate sales are approximately **$706,146**.
- Home Office sales are approximately **$429,653**.
- Consumer customers contribute the largest share of sales.

### Monthly Sales Trend

- **November 2018** recorded the highest monthly sales, approximately **$118,447.82**.
- The business can use monthly sales trends to plan stock and marketing activities.

### Discount and Profit Relationship

- The correlation between Discount and Profit is approximately **-0.219**.
- This indicates a weak negative relationship between discount and profit.
- Higher discounts are generally associated with lower profit in this dataset, but correlation alone does not prove that discounts cause lower profit.

## 8. Conclusion

This project helps understand the sales and profit performance of a retail business.

The analysis shows that Technology performs well in both sales and profit, while Furniture has comparatively low profit despite strong sales. The West region and Consumer segment are important contributors to business performance.

The business can use these findings to review discount strategies, improve product profitability, and plan sales activities.

## 9. How to Run the Project

1. Install Python and Jupyter Notebook.

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Keep the dataset and notebook in the same folder.

4. Open `Superstore_Retail_eda.ipynb` in Jupyter Notebook.

5. Run the cells from top to bottom.

## 10. Project Files

- `Superstore_Retail_eda.ipynb` — Notebook containing data cleaning, analysis, and visualizations.
- `superstore_sales.csv` — Dataset used for the project.
- `README.md` — Project documentation.

---

**Project Type:** Data Analysis / Exploratory Data Analysis (EDA)
**Author:**  Vinod K Gupta
**EMAILID:** guptavinod0449@gmail.in
