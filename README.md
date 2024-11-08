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
There are 6 categories of Products in the data. Below are the Excel Formulas to find:
1. **Average Sales per Product For:**
- **Gloves**
  
   ```
    =AVERAGEIF($C$2:$C$9922,C9902,$H$2:H9922)

   ```
- **Hat**
  
  ```
  =AVERAGEIF($C$2:$C$9922,C4,$H$2:H9922)
  
  ```

- **Jacket**

 ``` 
 =AVERAGEIF($C$2:$C$9922,C6,$H$2:H9922)

 ```

- **Shirt**

 ``` 
 =AVERAGEIF($C$2:$C$9922,C8,$H$2:H9922)

 ```

- **Shoe**

 ``` 
 =AVERAGEIF($C$2:$C$9922,C3,$H$2:H9922)

 ```

- **Socks**

 ```
 =AVERAGEIF($C$2:$C$9922,C5,$H$2:H9922)

```

 

The results from the formulas above is given below:

**AVERAGE SALE PER PRODUCT**



 ![image](https://github.com/user-attachments/assets/29707c2f-bbca-4a83-a48b-f4e5ac29b8f5) 

 2. **Total Revenue by Region**
	There are 4 Regions in the data, below is the formula to find the total revenue for each region:
- **East**

  ```
  =SUMIF($D$2:$D$9922,D9903,$H$2:$H$9922)
  ```
- **North**
  ```
  =SUMIF($D$2:$D$9922,D2,$H$2:$H$9922)
  ```
- **South**
  ```
   =SUMIF($D$2:$D$9922,D7,$H$2:$H$9922)
  
  ```
- **West**

  ```
   =SUMIF($D$2:$D$9922,D9,$H$2:$H$9922)

  ```
The results from the formula is given below:

***Total Revenue By Region**

![image](https://github.com/user-attachments/assets/5b1936c5-ffb9-4492-b05b-c104dc398b71)
