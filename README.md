# Capstone_Project_CustomerData
LITA_CAPSTONE_PROJECT 2: Exploring the data to bring out useful insights
---
### ***Project Title:CustomerData ANALYSIS***

---
### ***Outline***

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis ](#exploratory-data-analysis)

[Data Visualization](#data-visualization)



### ***Project Overview***
In this project, we explored the Subscription Customer data through various data analysis stages as listed in the outline above to uncover meaningful insights such as, subscription by Region, Revenue by Region, Revenue by Subscription Type, Subscription Type by Active Subscriber, Subscription Type by Inactive Subscriber, Monthly sales trends, and so on. 

---
### ***Data Sources***
---
The major data source used for this project is CustomerData.xlsx downloaded from the Incubator Hub LMS account as capstone project.

[LITA Capstone Dataset.xlsx](https://github.com/user-attachments/files/17678397/LITA.Capstone.Dataset.xlsx)


---

### ***Tools Used***
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For data Cleanling
  2. For Analysis
  3. For visualization
- SQL: for quering of data
- Microsoft Power BI [Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi)
  - For Interractive Visualization.
---

### ***Data Cleaning and Preparation***

---

1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting
---


### ***Exploratory Data Analysis***
There are 3 categories of subscription type in the data. Below are the Excel Formulas to find:
1. ** Subscriber per Subscription Type  For:**
- **Basic**
  
   ```
   =COUNTIF(D2:D75001,D74982)

   ```
- **Standard**
  
  ```
  =COUNTIF(D2:D75001,D5)
  
  ```

- **Premium**

 ``` 
   =COUNTIF(D2:D75001,D3)

 ```


---
 **Results of the formula is given below**


 		
		
![image](https://github.com/user-attachments/assets/71a002aa-35e2-47f2-a52f-4e7abed362a2)




---

Formula to find Active and Inactive Subscribers is given below:

  **Active Suscriber**
  ```
    =COUNTIF(G2:G75001,G8)

  ```

  **Inactive Subscriber**

  ```
   =COUNTIF(G2:G75001,G74981)
  
  ```

**Average Subscription Duration**


  ```
     =AVERAGE(I2:I75001)

  ```
The results from the formula is given as:  **365**


