# Amazon Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on Amazon product data to identify pricing trends, discount patterns, category performance, and customer value insights.

The analysis focuses on understanding how discounts, product categories, and ratings influence customer purchasing value.


## Dataset
The dataset contains Amazon product information including:
- Product Name
- Category
- Discounted Price
- Actual Price
- Discount Percentage
- Ratings



## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook



## Project Workflow

### 1. Data Cleaning
- Removed special characters from price columns
- Converted prices into numeric format
- Converted discount percentage into float values
- Handled rating datatype conversion

### 2. Exploratory Data Analysis
Performed analysis on:
- Highest and lowest priced products
- Product category distribution
- Average discounts by category
- Main category extraction
- Correlation between discounts and ratings
- Best value products based on rating and price

### 3. Data Visualization
Created visualizations for:
- Product category counts
- Discount distribution
- Average category discounts

---

## Key Insights

### Insight 1: Category Discounts
- Home Improvement products had the highest average discounts.
- Toys & Games had the lowest discount percentages.

### Insight 2: Best Value Categories
- Computers & Accessories contained the highest number of best-value products.
- These products combined good ratings with affordable pricing.

### Insight 3: Discount vs Rating
- Weak negative correlation observed between discount percentage and ratings.
- Discounts alone do not strongly influence customer ratings.

### Insight 4: Business Recommendations
- Focus marketing efforts on Computers & Accessories and Electronics categories.
- These categories show strong customer value potential and pricing opportunities.

---

## Files Included
- Amazon_Data_Analysis.ipynb
- amazon.csv
- Visualization screenshots

---

## Conclusion
This project helped in understanding:
- Real-world data cleaning
- Exploratory Data Analysis
- Business insight generation
- Correlation analysis
- Data visualization techniques

It also demonstrates how data analysis can support product and pricing decisions in e-commerce platforms.
