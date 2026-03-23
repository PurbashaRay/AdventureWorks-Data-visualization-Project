## <u>PROJECT OVERVIEW</u>

This is a comprehensive and collaborative project leveraging the industry-standard Microsoft AdventureWorks database as a real-world business scenario.
The project demonstrates teamwork in exploring realistic business data, performing data extraction, cleaning, and transformation processes, and generating meaningful insights through structured analysis.
Using AdventureWorks as the foundation, we applied practical data analysis techniques to simulate real-world business intelligence workflows and decision-making processes

## <u>PROJECT OBJECTIVES</u>

- Apply SQL to extract, join, filter, and aggregate data from relational tables.<br>
- Use Python for data cleaning, transformation, and exploratory analysis.<br>
- Analyze real-world business scenarios using the Microsoft AdventureWorks dataset.<br>
- Generate actionable insights to support data-driven decision-making.<br>
- Demonstrate end-to-end data analytics workflow from data processing to insight generation.<br>

## <u>Key Business Questions</u>

The analysis aims to answer the following:

**Q1.  What are the regional sales in the best performing country?** <br> 

![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q1.png) <br>

<small>We have analysed the data and the bar chart shows that USA is the best performing country for this company, and a deeper analysis shows that the Southwest regions is performing the best, with around 2.7 millions in revenue.</small><br>

**Q2.  What is the relationship between annual leave taken and bonus?** <br>

![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q2.png) <br>

The scatter plot shows that the points are widely scattered with no visible upward or downward trend, showing that there is no correlation between the attribution of a bonus and the amount of Annual Leave days taken. In our view, the bonuses are then likely influenced by performance, sales achievements, or Commissions, rather than Annual Leave taken.<br>

**Q3.  What is the relationship between Country and Revenue?**  <br>

![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q3.png)<br>

After converting all currencies to USD, we observe that some countries contribute substantially more revenue than others: North America is ahead with USA and Canada, which indicates that the company’s sales performance is not evenly distributed geographically. Countries with larger or more active sales territories generate the highest revenue, while others show much lower totals. Overall, the relationship demonstrates that a country is an important factor in revenue generation, with certain markets driving most of the company's income<br>

**Q4.  What is the relationship between sick leave and Job Title?** <br>
![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q4.png)<br>

We found that only individuals with PersonType ‘EM’ (Employee) and ‘SP’ (Sales Person) appear in the HumanResources. Employee table, meaning they are the only ones with real job titles and recorded sick-leave hours.  All other PersonTypes do not represent internal staff, which is why they were excluded.
The bar chat shows is a significant discrepancy in the amount of sick leave taken by people of PersonType ‘EM’ and ‘SP’, with people of PersonType ‘EM’ registering almost twice the amount of sick hours than people of PersonType ‘SP’.<br>

**Q5.  What is the relationship between store trading duration and revenue?** <br>
![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q6.png)<br>

For this analysis, we have converted all currencies to USD in order to provide a fair comparison between the stores.
The data displayed in this scatter plot shows that there is no clear relationship between how long a store has been trading and the amount of revenue it generates. Stores with both short and long trading histories are spread across the full range of revenue levels, with no visible trend upward or downward. This suggests that factors other than trading duration— such as store size, location, or staffing—are likely driving revenue performance, rather than simply how long the store has been open.<br>

**Q6.  What is the relationship between the size of the stores, number of employees and revenue?** <br>
![image](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/01fa671ba0b3d1a05a4c55ed85ed90becce22837/image/Q7.png)<br>

The analysis shows a clear positive relationship between store size, number of employees, and annual revenue. Larger stores employ more staff and consistently generate higher revenue. Likewise, stores with more employees tend to earn more. Overall, bigger stores with larger teams deliver stronger financial performance.
<br>

## <u>TOOLS & TECHNOLOGY</u>

- SQL (queries, joins, aggregates, subqueries, CTEs)<br>
- Python (Pandas, NumPy, Matplotlib/Seaborn for visualizations)<br>
- AdventureWorks Database (Microsoft SQL Server)<br>
- SQL Server Management Studio<br>
- VS Code/Jupyter Notebook <br>

## <u>CONCLUSION</u>

This project provided hands-on experience with end-to-end data analytics using the AdventureWorks database.
Working together allowed us to explore data comprehensively, solve analytical challenges as a team, and deliver actionable insights based on real-world business scenarios.



**Project Analysis, SQL and python codes can be found in the [Project Report](https://github.com/PurbashaRay/AdventureWorks-Data-visualization-Project/blob/b049600d3f589f7b37011dfb86a09f6eb12d3ce8/Project%20Report.pdf)**
