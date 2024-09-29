# e-Commerce(Target) Sales Analysis

   ![image](https://github.com/user-attachments/assets/481c1ba9-2aa2-457f-837f-470056b3719e)

### **Project Overview**:
**Target** is a globally recognized brand and a leading retailer in the United States, known for offering exceptional value, inspiration, innovation, and a unique shopping experience. In the highly competitive world of e-commerce, businesses face the challenge of understanding customer behavior, optimizing product offerings, and maximizing sales performance across regions. 

This project done using **SQL & Python** involves the analysis of a large e-commerce dataset by performing data transformation, querying, and visualization to address business-critical questions. The process is broken down into two main components:
1. **Data Transfer to MySQL**: The dataset is obtained from Kaggle [e-Commerce(Target) sales Dataset](https://www.kaggle.com/datasets/devarajv88/target-dataset). This dataset focuses on Target's operations in Brazil, covering 100,000 orders placed between 2016 and 2018. It includes detailed information on order status, pricing, payment and shipping performance, customer locations, product attributes, and customer reviews. Data from CSV files is loaded into a MySQL database using Python, creating a structured environment for efficient querying.
2. **Data Analysis and Visualization**: Using SQL and Python, 15 business queries are solved, and the results are visualized to uncover insights regarding sales trends, customer behavior, and product performance.

### **Tasks Completed**:
- **Data Transfer**: 
  - Loaded the CSV data into a MySQL database by establishing a connection using Python’s `pymysql` library.
  - Created and populated tables like `customers`, `orders`, and `products` in MySQL to allow for structured data storage and analysis.
  
- **SQL Queries**:
  - Solved **15 business queries** to answer key questions regarding product performance, regional sales distribution, customer purchasing trends, and revenue generation.
  
- **Data Visualizations**:
  - Created several visualizations to better understand the data and communicate trends.
  - Visualizations included customer distribution by region, sales performance over time, top-performing sellers, and top buyers each year.

### **Analysis file**: [Click here](https://github.com/Tan-Tripathi/e-Commerce_Sales-Python_sql-Project/blob/main/e-Commerce(Target)%20Sales%20project_python%2Bsql.ipynb)

### **Key Insights**:
1. **Top-Performing Products**:
   - Certain products consistently generate higher revenue across regions, allowing the business to focus on stocking and promoting these items.
   
2. **Geographic Sales Trends**:
   - Sales performance varies significantly across different cities and regions. Specific regions showed consistently higher customer engagement and revenue generation, pointing to potential areas for targeted marketing campaigns.

3. **Customer Purchasing Patterns**:
   - No customers make another purchase within 6 months of their first purchase. Also, product price doesn't seem to affect the number of times a product has been purchased by the customers. This insight could be useful for tailored marketing and promotions.

4. **Seasonal Sales Variations**:
   - Sales trends revealed significant fluctuations during different times of the year, suggesting the presence of seasonal demand spikes. This is critical for adjusting inventory levels and ensuring stock availability during peak periods.

### **Recommendations**:
- **Inventory Management**: Based on the insights from product and sales performance, optimize inventory management by stocking high-demand products in regions that show strong sales trends. Also, prepare for seasonal sales spikes.

- **Customer Loyalty Programs**: High-value and frequent customers should be offered loyalty programs, discounts, or personalized promotions to encourage repeat business, as these customers generate a large portion of revenue.
  
- **Targeted Marketing Campaigns**: Leverage geographic and customer behavior insights to design region-specific marketing campaigns and promotions to maximize customer engagement and increase sales.

- **Predictive Analytics**: Consider using machine learning models for sales forecasting based on historical data. This could help predict future sales trends and customer behavior, enabling more informed decision-making.
  
- **Automate Reporting**: Automating SQL queries for periodic reporting would provide continuous insights into business performance, helping stakeholders keep track of key metrics like revenue, customer growth, and product demand.

---

This project showcases how the combination of SQL and Python can be used to extract meaningful insights from e-commerce sales data. By transferring the data to a MySQL database and solving business-critical queries, the project provides actionable insights into product performance, customer behavior, and regional sales trends. These insights can be applied to enhance inventory management, tailor marketing efforts, and optimize overall business operations.
