# MIS-311
## Introduction to Business Analytics

### **Data Overview**  
- Source of data: Government Agencies and Statistical Organizations; International organizations.  
- Number of rows: 202 rows  
- Number of columns: 5 columns  
The context: Cost of living data basically tells us how much it really costs to live in a certain place. It's not just about rent; it's about groceries, transportation, and all the stuff that makes up daily life. This info is super important for everyone from governments trying to keep the economy healthy to companies deciding where to set up shop, and even for us regular folks figuring out where we can afford to live comfortably. It's all about understanding how far your money goes, and what kind of life you can build in a particular city or town.  

 ### **Data Cleaning**
* Missing values: 4 values  
Average monthly income: 2 missing values ( C162, C178)  
Region: 2 missing values ( E26, E39)  
=> Handling missing values:
 Average monthly income: should be deleted because only 2 lines are missing in 201 → does not greatly affect the overall.
 Region: should be deleted because duplicates do not provide additional information and cause errors when calculating averages, totals, and statistical analysis. The four missing values ​​account for approximately 1.98% of the total 202 values.  
 After deletion, there are 198 rows and 5 columns left.  
* Duplicate rows: 2 rows  
=> Handling duplicate rows: delete the 2 duplicate rows because they do not carry additional information and do not affect the analysis. The two duplicate rows account for about 0.99% of the total 202 rows. Duplicate rows cause statistical bias, degrade machine learning model performance due to redundant data learning, and disrupt record uniqueness while consuming storage space. Therefore, removing them is necessary to ensure accurate and efficient analysis.  
=> After deletion, there are 196 rows and 5 columns left.  

### **Descriptive Statistics**  

<p align="center">
  <img src="https://github.com/HoaiAnh2/MIS-311/blob/main/Screenshot%202025-05-15%20221727.png" alt="Thống kê thu nhập và chi phí" />
</p>



The average monthly income (4264.53) is higher than the average living cost (3703.59), showing that the standard of life is positive. However, the large standard deviation in both indicators reflects the difference in income and costs among individuals or areas is quite high.

- Insight 1: Cost of living is too high relative to income  
The cost of living is very high relative to income in many regions, especially Asia and North America, indicating serious financial stress for people in these regions.  

<p align="center">
  <img src="https://github.com/HoaiAnh2/MIS-311/blob/main/Screenshot%202025-05-17%20191911.png" alt="Ảnh bạn muốn" />
</p>

The chart shows that Asia (70.3%) and North America (71%) have the highest cost of living to average income ratios, meaning that a large portion of income is eaten up by essential expenses. Meanwhile, South America (15.3%) and Africa (18.4%) have lower ratios, but this may be because average incomes are too low to reflect higher living standards.  

- Insight 2: The Difference in Cost of Living Between Regions
Places with developed economies often come with higher standards of living, which translates into significantly higher costs of living. Conversely, low-cost countries often reflect low consumer prices and different economic structures.


The chart compares total cost of living and total annual income across countries and regions. Mexico has the highest cost of living but low income. Canada and South Africa have lower costs of living, but higher incomes in Canada. Australia has both high cost of living and high incomes. Overall, there are significant financial differences between locations.
