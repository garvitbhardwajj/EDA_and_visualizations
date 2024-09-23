[tableau Public link](https://public.tableau.com/views/EnhanceManufacturingEfficiency_17212301507850/Employee?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


# Manufacturing

### **Case Study: Enhancing Manufacturing Efficiency Through Data-Driven Insights**

### **Background**

You are a data analyst at ProManu Analytics, a consultancy firm specializing in manufacturing analytics. Your team has been provided with two datasets: 'Manufacturing Production Data' and 'Employee Performance Metrics'. The 'Manufacturing Production Data' dataset encapsulates detailed information about various products, including production dates, costs, quantities, and warehouse locations. The 'Employee Performance Metrics' dataset offers insights into the workforce, covering departments, salaries, performance ratings, and countries of operation.

In a manufacturing landscape where efficiency, cost management, and employee performance are intricately linked, your analytical expertise is essential. Your challenge is to explore these datasets to identify trends and insights that could streamline manufacturing processes, optimize resource allocation, and enhance employee productivity.

### **Objective**

Your mission is to utilize Tableau's robust capabilities to craft a compelling narrative from the provided datasets. This task will encompass thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate aim is to construct an interactive and intuitive dashboard in Tableau that showcases your key discoveries, offering concise, actionable insights into the optimization of hotel operations and performance.

### **Data Source:**

[ManufacturingDataset1.xlsx](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/2c405c7e-5f47-4a5a-a251-5d21e69dd123/ManufacturingDataset1.xlsx)

The "ManufacturingDataset1.xlsx" file contains the following columns:

1. **ProductID**: A unique identifier for each product.  (Primary Key)
2. **ProductType**: The type of the product (e.g., Electronics, Furniture).
3. **ProductionDate**: The date when the product was manufactured.
4. **ProductionCost**: The cost of producing the product.
5. **CountryOfOrigin**: The country where the product was manufactured.
6. **QuantityProduced**: The quantity of the product produced.
7. **WarehouseLocation**: The location of the warehouse where the product is stored.

[ManufacturingDataset2.xlsx](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/ba0db762-3ef8-429f-a237-8b446856bf63/ManufacturingDataset2.xlsx)

The "ManufacturingDataset2.xlsx" file contains the following columns:

1. **EmployeeID**: A unique identifier for each employee.
2. **Department**: The department in which the employee works.
3. **HireDate**: The date when the employee was hired.
4. **Salary**: The salary of the employee.
5. **CountryOfOperation**: The country where the employee operates.
6. **ProductID**: A unique identifier for products, corresponding to 'ProductID' in "ManufacturingDataset1.xlsx".  (Foreign Key)
7. **PerformanceRating**: The performance rating of the employee (out of 10).
8. **Employee Training Record:** Training records for each employee.

### **Part 1: Data Cleaning, Modeling, and Advanced Analysis in Tableau**

1. **Data Preparation**
    - Import both datasets into Tableau. Perform a preliminary examination of the data. Identify any data quality issues or inconsistencies.
    - Perform necessary cleaning steps, such as handling missing values, normalizing text fields or handling outliers in 'ProductionCost' and 'Salary'.
2. **Hierarchies in Production Data**: Create a hierarchy in ManufacturingDataset1 with 'ProductionDate', 'ProductType', and 'WarehouseLocation'. How does this aid in data exploration?
3. **Calculated Fields for Cost Analysis**: Create a calculated field to determine the cost per unit produced. What variations do you observe across different 'ProductTypes'?
4. **Grouping Employees**: Group employees in ManufacturingDataset2 by 'Department'. Analyze the salary distribution within each department.
5. **Bin Creation for Salary Analysis**: Create bins for 'Salary' to categorize employees into different salary ranges. What does this reveal about salary distribution in the organization?
6. **Dynamic Date Filters**: Implement dynamic date filters to analyze production and employee data over different time periods.
7. **Trend Analysis of Production Cost**: Analyze the trend of 'ProductionCost' over time. Are there any notable patterns or seasonal effects?
8. **Correlation Analysis**: Investigate the relationship between 'QuantityProduced' and 'ProductionCost'. Is there a correlation?
9. **Performance Rating Analysis**: Analyze the distribution of 'PerformanceRating' across different 'Departments'. What patterns emerge?
10. **Product Type Distribution**: Create a visualization to show the distribution of different 'ProductTypes'. Which type is most commonly produced?
11. **Employee Tenure Calculation**: Calculate the tenure of each employee in ManufacturingDataset2 from their 'HireDate' to the current date.
12. **Aggregate Functions for Department Analysis**: Calculate the average performance rating and total salary expenditure for each 'Department'. What insights can you gather about departmental performance?
13. **Top N Analysis for Products**: Identify the top 5 products with the highest production costs. What characteristics do these products share?
14. **Parameter Control for Product Analysis**: Create a parameter control to filter data by 'CountryOfOrigin'. How does the production profile change by country?
15. **LOD Expressions for Detailed Insights**: Use Level of Detail expressions to calculate the average salary of employees for each 'CountryOfOperation' regardless of the department.
16. **Predictive Analysis for Salary Increases**: Using trend lines, predict future salary trends in the company. How does this vary by department?
17. **Cluster Analysis for Employee Performance**: Apply Tableau's clustering feature to group employees based on performance and salary. What patterns emerge from this analysis?
18. **Market Basket Analysis for Products and Warehouses**: Conduct a market basket analysis to find associations between 'ProductType' and 'WarehouseLocation'. Are certain products predominantly produced in specific warehouses?
19. **Custom Date Parsing for Production Analysis**: Create a custom date parsing calculation to analyze production data by week, month, and quarter. What seasonal trends can you identify?
20. **Complex Calculations for Employee Training Analysis**: Develop a complex calculated field to count the number of trainings each employee has attended. Correlate this with their performance ratings.

(Note: Show Vizualizations wherever possible in Part 1)

### **Part 2: Dashboard Building**

1. **Comprehensive Manufacturing Dashboard**
    - Create a dashboard in Tableau showcasing key metrics such as production costs, employee distribution, performance ratings, and product trends. Include filters for department, country, and product type.
2. **Dashboard Design and Functionality**
    - Focus on the dashboard's design and functionality. Ensure it is user-friendly, visually appealing, and provides interactive elements.
3. **Time-Based Analysis in Dashboard**
    - Incorporate time-based analysis in your dashboard, such as production trends over time and salary progression.
4. **Interactive Analysis of Employee Data**
    - Create an interactive section for analyzing employee data, including performance, department distribution, and salary trends.
5. **Visualization of Production and Cost Data**
    - Implement visualizations that display production volumes and cost data effectively, providing insights into efficiency and trends.
6. **Key Insights and Data Storytelling**
    - Provide a section summarizing key insights or stories from the data. Highlight significant findings or trends that emerged from your analysis.
