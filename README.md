# Sales Data

ETL using Power Query and Power Pivot

ETL stands for **Extract, Transform and Load** - it is a data integration process that combines, cleans and organizes data from multiple sources into a single, consistent data set and prepare it for storage and data analytics.
## 🛠 Step by Step 

- Loaded data from different sources (excel, csv and text files):

![Data](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/Data.JPG)

- Performed transformations on Power Query:

![PowerQuery](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/PoweQuery.JPG)

Structured the tables using a Star Schema, centralising the fact table and linking it to multiple dimension tables. Commonly used in data warehousing and business intelligence applications.

  **Fact table:** contains the data that needs to be analysed (they typically have more records and fewer attributes)

  **Dimension tables:** contain the attributes related to the facts (they usually have more attributes and fewer records)
  
- Loaded the data on Excel adding some tables to the Model (to allow access to the data) and leaving some tables as "connection only" (because they are only needed for transformation).

![Connections](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/Connections.JPG)

- Using Power Pivot

  1- As a best practice, created a Calendar table to utilise Time Intelligence functions. In Power Pivot, there is a function that automatically scans the entire dataset and generates the appropriate date table.

  2- Created the relationship between the tables:

![Diagram](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/DiagramView.JPG)

- Created Calculated Measures using DAX (Data Analysis Expressions):

![Measures](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/Measures.JPG)

- Used Pivot Tables and Pivot Charts to create a report:

![Report](https://raw.githubusercontent.com/anapsoliveira/SalesData-PowerQueryPowerPivot/main/images/Report.JPG)

## Advantage

- The raw data on the source files can be updated anytime and the new information will be transformed and refreshed automatically.
## Author 👋

- [@anapsoliveira](https://www.github.com/anapsoliveira)

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/anapsoliveira)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anapsoliveira/)
