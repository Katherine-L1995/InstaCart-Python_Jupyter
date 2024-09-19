**Instacart Customer Orders Analysis**

In this Data Study, I analyzed an Instacart customer order dataset using Python and Jupyter Notebooks. The goal was to explore customer behaviors, clean and prepare data, and provide actionable insights to answer key business questions for Instacart's marketing and operations teams.

**Project Overview**

In this analysis, I imported and explored datasets related to customer orders and products, focusing on tasks such as:

*Data Import and Exploration:* Loaded and examined the orders and products datasets, identifying key variables for analysis.


*Data Cleaning:* Addressed missing values, mixed types, and duplicates. Renamed columns with unintuitive names for better clarity.

**Grouping and Aggregation:**

  Used aggregation functions to generate descriptive statistics, such as the aggregated mean of the "order_number" column grouped by "department_id."

  Derived new columns from the aggregated values to enrich the dataset.

  *Subsetting and Analysis:*
   
    Analyzed the busiest hours for placing orders.
    Investigated product categories such as breakfast items and dinner party essentials.
    Explored department sales for alcohol, deli, beverages, and meat/seafood.
    
**Customer Behavior Insights:**

  Created a loyalty flag using the transform() and loc() functions, identifying Loyal, Regular, and New Customers.
  Analyzed the differences in spending habits across these customer segments.
  Created a spending flag based on the average price of products purchased, categorizing customers as either "High Spenders" or "Low Spenders."
  Developed an order frequency flag to classify customers as Frequent, Regular, or Non-frequent based on the median days between orders.
  Customer Profiling for Marketing:
  Provided customer segmentation insights to help Instacart target users for specific marketing campaigns, ads, and sales promotions.

  *Data Merging:* Combined customer, product, and order datasets for a comprehensive analysis, enriching the data with loyalty, spending, and order frequency flags.

  *Data Visualizations:* Generated visual representations to enhance insights and reporting.

  *Exporting Data:* Exported the cleaned and wrangled datasets as CSV and pickle files for future analysis.

**Key Insights**

  Identified peak hours for order placements and differences in customer spending habits.
  Created customer segments based on loyalty, spending behavior, and order frequency.
  Analyzed product categories to provide recommendations for targeted marketing strategies.

**Tools Used**
  *Python:* For data cleaning, manipulation, and aggregation.
  
  *Pandas:* For dataframe operations, merging, and creating new columns.
  
  *Matplotlib/Seaborn:* For data visualization.
  
  *Jupyter Notebooks:* To document the process and provide a structured workflow.

**Data Sources**

  The datasets used in this analysis were provided as part of the CareerFoundry course, including orders, products, and department information.
