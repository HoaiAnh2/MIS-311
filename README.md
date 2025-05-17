# MIS-311
## Introduction to Business Analytics

### **Data Overview**  
- Source of data: Government Agencies and Statistical Organizations; International organizations.  
- Number of rows: 202 rows  
- Number of columns: 5 columns  
The context: Cost of living data basically tells us how much it really costs to live in a certain place. It's not just about rent; it's about groceries, transportation, and all the stuff that makes up daily life. This info is super important for everyone from governments trying to keep the economy healthy to companies deciding where to set up shop, and even for us regular folks figuring out where we can afford to live comfortably. It's all about understanding how far your money goes, and what kind of life you can build in a particular city or town.  

 ## **Data Cleaning**
* Missing values: 4 values  
Average monthly income: 2 missing values ( C162, C178)  
Region: 2 missing values ( E26, E39)  
=> Handling missing values:  
- Average monthly income: should be deleted because only 2 lines are missing in 201 → does not greatly affect the overall.
- Region: should be deleted because duplicates do not provide additional information and cause errors when calculating averages, totals, and statistical analysis. The four missing values ​​account for approximately 1.98% of the total 202 values.  
=> After deletion, there are 198 rows and 5 columns left.  
* Duplicate rows: 2 rows  
=> Handling duplicate rows: delete the 2 duplicate rows because they do not carry additional information and do not affect the analysis. The two duplicate rows account for about 0.99% of the total 202 rows. Duplicate rows cause statistical bias, degrade machine learning model performance due to redundant data learning, and disrupt record uniqueness while consuming storage space. Therefore, removing them is necessary to ensure accurate and efficient analysis.  
=> After deletion, there are 196 rows and 5 columns left.  

