# Sales-Report - Power BI


# DATA CLEANING AND TRANSFORMATION


Introduction:
In the pursuit of showcasing proficiency in data manipulation and visualisation, this report details the process of data cleaning and transformation undertaken using Power BI. The dataset utilised for this demonstration was extracted from Microsoft SQL Management Studio in .CSV format.
Data Extraction:
The initial step involved extracting the dataset from Microsoft SQL Management Studio into Power BI. This facilitated a seamless transition of the data for subsequent analysis and visualisation.

<img width="1460" alt="Screenshot 2023-12-31 at 3 33 36 pm" src="https://github.com/alex3381/Sales-Report-Power-BI-/assets/59268114/b600c4ca-3e7d-4879-bcd0-8b102cfc34e6">



Data Cleaning:
The subsequent phase cantered on data cleaning, wherein the Power Query functionality was employed. The primary focus of this phase was to enhance data integrity and coherence.
* 		Transformation of Prize Size Column:
* 		The 'Transform and Replace Value' feature within Power Query was utilised to modify the values within the Prize Size column. This step aimed to standardise and optimise the representation of prize sizes.
* 		Creation of New Column for Day Name:
* 		A new column was generated using Power Query to capture the abbreviated representation of days. Specifically, the formula used for this purpose was Order Day = UPPER(LEFT(Results[Day Name], 3)), effectively splitting the Day Name column and creating a new column with three-letter representations of the corresponding days.
* 		Date Formatting:
* 		The date values within the dataset were formatted to ensure consistency and compatibility with analytical processes. This step is crucial for accurate temporal analysis and visualization.
* 		Removal of Empty Columns:
* 		Extraneous or redundant columns were identified and removed from the dataset to streamline the information and enhance its relevance to the analytical objectives.
* 		Addition of Supplementary Columns:
* 		To augment the dataset's informational richness, additional columns were added strategically. This step involved the inclusion of pertinent data points to facilitate comprehensive analysis and visualization.
Conclusion:
In conclusion, the meticulous process of data cleaning and transformation using Power BI underscores the commitment to data quality and analytical precision. This endeavor not only ensures the integrity of the dataset but also lays the foundation for insightful and meaningful data visualization, thereby contributing to informed decision-making processes.

https://github.com/alex3381/Sales-Report-Power-BI-/assets/59268114/809a8147-97d7-4ae9-8440-69f477efaed7



# Problem Statement and Key Performance Indicators (KPIs) Requirements:
In pursuit of a comprehensive understanding of our business performance, we aim to analyze pivotal indicators within our pizza sales data. Our focus revolves around calculating specific metrics, including but not limited to:
A). Total Revenue: The summation of the total price of all pizza orders. B). Average Order Value: The mean amount expended per order, derived by dividing the total revenue by the total number of orders. C). Total Pizzas Sold: The cumulative quantity of all pizzas sold. D). Total Orders: The aggregate count of placed orders. E). Average Pizzas Per Order: The mean number of pizzas sold per order, ascertained by dividing the total number of pizzas sold by the total number of orders.

# Charts Requirement:
In an effort to glean insights and comprehend key trends from our pizza sales data, we have outlined specific chart creation requirements, encompassing: Daily Trend for Total Orders: The generation of a bar chart depicting the daily trend of total orders over a designated time period. This chart aims to unveil patterns or fluctuations in order volumes on a daily basis.
Monthly/Hourly/Weekly Trend for Total Orders: The development of a line chart illustrating the hourly trend of total orders throughout the day, facilitating the identification of peak hours or periods of heightened order activity.
Percentage of Sales by Pizza Category: The creation of a pie chart showcasing the distribution of sales across diverse pizza categories. This chart is instrumental in providing insights into the popularity of various pizza categories and their overall contribution to sales.
Percentage of Sales by Pizza Size: The generation of a pie chart representing the percentage of sales attributed to distinct pizza sizes. This chart aids in comprehending customer preferences for pizza sizes and their consequential impact on sales.
Total Pizzas Sold by Pizza Category: The crafting of a funnel chart presenting the cumulative number of pizzas sold for each pizza category. This chart facilitates a comparative analysis of the sales performance among different pizza categories.
Top 5 Best Sellers by Revenue, Total Quantity, and Total Orders: The development of a bar chart spotlighting the top 5 best-selling pizzas based on Revenue, Total Quantity, and Total Orders. This chart serves as a valuable tool for identifying the most popular pizza options.
Bottom 5 Best Sellers by Revenue, Total Quantity, and Total Orders: The creation of a bar chart featuring the bottom 5 worst-selling pizzas based on Revenue, Total Quantity, and Total Orders.

# Software Used:
MS Office/Excel: Version 2021 MS SQL Server: 19.0 SQL Server Management Studio - 19.0.20209.0 Power BI: June 2023 Version 
S/N SQL-MS SQL SERVER EXCEL POWER BI TABLEAU 1 ✓ Creating Database ✓ Connecting to SQL Server ✓ Connecting to SQL Server ✓ Connecting to SQL Server 2 ✓ Creating Table ✓ Pivot Table ✓ Data Cleaning ✓ Data Cleaning 3 ✓ Select ✓ Pivot Charts ✓ Data Modelling ✓ Creating Model 4 ✓ Date name ✓ VLOOKUP ✓ Data Processing ✓ Metadata 5 ✓ Date part ✓ Date Functions ✓ Power Query ✓ Calculated Fields 6 ✓ Cast ✓ Text Functions ✓ Date Tables ✓ Calculates Measures 7 ✓ Decimal ✓ Logical Functions ✓ Time Intelligence Function ✓ LOD Functions 8 ✓ Month ✓ Calculated Fields ✓ DAX ✓Date Functions 9 ✓ Hour ✓ Creating KPI's ✓ DAX ✓ Text Functions 10 ✓ Quarter ✓ Creating Charts ✓ Date Function ✓ Date Part 11 ✓ Day ✓ Conditional Formatting ✓ Text Function ✓ Creating Charts 12 ✓ Group by ✓ Custom Charts ✓ Filter Function ✓ KPI's 13 ✓ Order by ✓ Formatting Charts ✓ Calculate ✓Formatting Charts 14 ✓ Decimal ✓ Lay outing Dashboard ✓ SUM/SUMX ✓ Actions Filters 15 ✓ Limit ✓ Creating Background ✓ Creating KPI's ✓URL Filters 16 ✓ Count ✓ Filter Connections ✓ New Card Visual ✓ Navigators 17 ✓ Distinct ✓ Dynamic charts ✓ Creating Charts ✓ Tiled/Floating Containers 18 ✓ CTE. ✓ Dynamic Dashboard ✔ Formatting visuals ✓ Objects 19 ✓ Partition ✓ Creating Functions ✓ Creating Dashboards 20 ✓ Navigations

Recommendation:
1. Continuous Monitoring and Evaluation: Regularly execute the provided SQL queries to gather KPIs and assess trends. This will enable real-time insights into the business performance, aiding in timely decision-making.
2. Utilize Visualization Tools Effectively: Leverage Power BI or Tableau to create visual representations of the obtained data. This will enhance the interpretability of trends and patterns, providing a more accessible means for stakeholders to grasp the information.
3. Dynamic Filtering for Deeper Analysis: Implement dynamic filters, such as Month, Quarter, and Week, to allow for a more granular analysis of data. This will provide the flexibility to delve deeper into specific timeframes and uncover nuanced trends.
4. Refine Decimal Precision for Clarity: When calculating percentages and sales figures, consider refining decimal precision for clarity in the visualization. This ensures that the presented data is not only accurate but also easily interpretable.
5. Top and Bottom Performers Analysis: Regularly assess the top and bottom performing pizzas based on Revenue, Total Quantity, and Total Orders. This analysis can offer valuable insights into customer preferences and guide marketing and inventory management strategies.

Conclusion:
In conclusion, the recommended approach involves a combination of SQL queries for robust data gathering and visualization tools for dynamic dashboard analysis using Power BI. The provided queries cover key metrics and chart requirements, offering a comprehensive understanding of pizza sales data. By implementing the outlined recommendations, the organization can derive actionable insights, enhance decision-making processes, and adapt strategies to optimize overall business performance. Regular monitoring and refinement of analytical methods will contribute to sustained success in the dynamic landscape of the pizza sales industry.


