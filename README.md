# Instagram Ad-hoc Analysis

This project was developed as part of my **T-Lab** experience to explore data analysis using SQL (via SQLite) and Python. The goal was to extract insights from a relational database containing customer, order, product, and supplier data, through a mix of SQL queries and Python based visualizations.



### Market.db


![ERD Diagram](/images/Northwind_E-R_Diagram.png)  
*ERD Diagram of Market Database*

## Objectives

- Write and run advanced **SQL queries** using SQLite
- Analyze customer behavior and ordering patterns across countries
- Identify correlations between **customers**, **suppliers**, **order quantities**, and **revenue**
- Visualize data to support business insights




## Tools & Technologies

- **SQLite** – For database storage and SQL querying
- **Pandas** – For loading and manipulating SQL query outputs
- **Matplotlib** & **Seaborn** – For plotting and correlation visualization
- **Jupyter Notebook / VS Code** – For analysis and experimentation



## Key Analyses & Findings

- **USA, Germany, and France** have the highest number of customers and also rank high in supplier counts, showing a **moderate positive correlation** between customer and supplier numbers. However, the relationship isn't proportional, some countries have **many customers but few suppliers**, and vice versa.

- One example of imbalance: a country with **9 customers** had only **1 supplier**, while another with **just 2–3 customers** had **2 suppliers**.

- **Scatterplot analysis** shows **no strong correlation** between total orders and number of customers without orders. For instance, **USA** had the **highest orders (2139)** and also the **most non-ordering customers (5)**.

- In product analysis, there is a **positive correlation** between **order quantity** and **revenue**,products ordered more frequently generally yield higher revenue. A few outliers exist, such as products with **low quantity (~20)** but **high revenue (~6000)**.

- **Top Suppliers by Order Count**:
  - **Plutzer Lebensmittelgroßmärkte AG** 
  - **Pavlova, Ltd.**
  - **Specialty Biscuits, Ltd.**


## Conclusion

This project provided valuable hands-on experience in querying relational databases, analyzing business data, and visualizing key insights. Through exploring customer behavior, supplier distribution, and product performance, I was able to uncover meaningful patterns and exceptions that reflect real-world business challenges. The combination of SQL and Python helped build a strong foundation in data analytics and critical thinking.


