# Data-Modeler
Data Modeler – Building a Normalized Star Schema
📌 Project Overview
This project focuses on advanced Data Modeling in Power BI. The goal was to transform raw Excel datasets into a well-structured Relational Star Schema to ensure efficient data analysis and reporting.

🛠️ Key Features
Star Schema Design: Created a central Sales_Fact table connected to multiple Dimension tables.

Data Transformation: Cleaned and formatted data using Power Query (removing blanks, setting data types).

Manual Relationships: Established 1:Many relationships between Fact and Dimension tables.

Advanced Modeling: Implemented an Inactive Relationship between Returns_Fact and Date_Dim using the ReturnDateKey.

Hierarchies: Built drill-down hierarchies for Date, Geography, and Product categories.

Data Categories: Optimized geographical fields (City, State, Country) for better sorting and mapping.

📊 Verification Matrix
To ensure the model works perfectly, I used Matrix Tables to verify:

Sales Performance: Grouped by Product Category and Region.

Return Analysis: Count of return reasons by Fiscal Year.

Customer Insights: Revenue distribution across Customer Segments.
