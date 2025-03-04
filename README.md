# Customer Segmentation and Demand Pattern Analysis

## Project Overview
This project performs customer segmentation and sales demand pattern analysis using Python. The primary goals are to identify high-value customers, frequent buyers, and occasional buyers, along with analyzing sales trends to detect peak ordering periods. The insights generated from this analysis can help businesses optimize marketing strategies, inventory management, and promotional campaigns.

## Objectives
- Segment customers into high-value, frequent, and occasional buyers using K-Means clustering.
- Analyze sales trends to identify peak ordering periods.
- Visualize customer segments and order patterns.

## Data Sources
- **customers.csv:** Contains customer information such as customer IDs and purchase history.
- **sales_data.csv:** Includes sales data with order dates, customer IDs, product IDs, and order amounts.

## Tools and Libraries Used
- Python
- pandas
- matplotlib
- seaborn
- scikit-learn (for K-Means clustering)

## Methodology
### 1. Customer Segmentation
- **Feature Extraction:**
  - Total Spend
  - Frequency of Orders
  - Recency (days since last purchase)
- **Data Normalization:** Standardizing features to ensure uniform scaling.
- **K-Means Clustering:** Customers are segmented into three groups:
  - Segment 0: Occasional buyers (low spend, low frequency)
  - Segment 1: Frequent buyers (moderate spend, high frequency)
  - Segment 2: High-value customers (high spend, frequent purchases)

### 2. Sales Trend Analysis
- Group sales data by date to observe demand patterns.
- Plot sales over time to visualize peaks and troughs.
- Identify peak sales periods for better promotional planning.

### 3. Visualizations
- Bar plot of customer segments showing average total spend.
- Line plot for sales trends over time.
- Bar plot of order trends over different time intervals.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone git@github.com:Prachi24-com/Customer_Segment_Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Run the analysis script:
   ```bash
   jupyter execute 'Customer Segmentation and Demand Analysis.ipynb'
   ```

## Results
- High-value customers have significantly higher average total spend.
- Frequent buyers place more orders but with moderate spending.
- Occasional buyers contribute the least to overall revenue.
- Peak sales periods occur in October, while demand is lowest in August.

## Future Enhancements
- Add more features for refined customer segmentation.
- Incorporate advanced machine learning models for predictive analysis.
- Perform granular sales trend analysis by week or month.

## Contributing
Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License.

