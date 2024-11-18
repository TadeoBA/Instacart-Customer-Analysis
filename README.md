# Instacart Customer Analysis 🛒

## Project Description
This project involves an exploratory data analysis (EDA) of Instacart's customer purchase data. The goal is to uncover insights about customer behavior, including purchase patterns, product popularity, and reorder trends, to provide actionable business recommendations.

## Datasets
The analysis is based on the following datasets:
- **instacart_orders.csv**: Contains information about orders, including order time and customer IDs.
- **products.csv**: Provides details about the products available on Instacart.
- **order_products.csv**: Links orders to the products purchased in each order.
- **aisles.csv**: Describes the grocery aisle categories.
- **departments.csv**: Describes the grocery department categories.

## Objectives
1. Assess and preprocess the data (handle missing values, duplicates, etc.).
2. Analyze customer purchase patterns by:
   - Day of the week.
   - Hour of the day.
   - Frequency of reorders.
3. Identify the most popular products and the ones frequently reordered.
4. Provide actionable recommendations to improve inventory management, marketing, and customer experience.

## Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn for data analysis and visualization.
- **Jupyter Notebook**: Interactive analysis environment.

## Key Steps
1. **Data Preprocessing**:
   - Handled missing values and duplicates.
   - Verified data consistency and adjusted types.
2. **Analysis**:
   - Visualized purchase behavior by day and hour.
   - Identified top products by purchase frequency and reorder rates.
   - Analyzed customer habits, such as the time between orders and the first items added to the cart.
3. **Insights**:
   - Reordering patterns revealed opportunities for targeted marketing.
   - Popular products provide inventory optimization recommendations.

## Results
- **Purchase Behavior**: Customers are most active on Saturdays and during late mornings.
- **Top Products**: Frequently reordered items include fresh produce and beverages.
- **Customer Behavior**: Reorder rates suggest strong brand loyalty for certain products.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/TadeoBA/instacart-customer-analysis.git
