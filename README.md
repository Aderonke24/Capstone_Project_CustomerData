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
There are 3 categories of subscription type in the data, which are Basic, Standard, and Premium.

Below are the Excel Formulas to find in each of the subscription type:
 **Subscriber per Subscription Type  For:**
1.  **Basic**
  
   ```
   =COUNTIF(D2:D75001,D74982)

   ```
2.  **Standard**
  
  ```
  =COUNTIF(D2:D75001,D5)
  
  ```

3.  **Premium**

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
---

Results are given below:
1. **Number of Active subscribers**

   

![image](https://github.com/user-attachments/assets/59723fe3-f47b-42c9-921c-4aa2d9d52649)


2. **Number of Inactive subscribers**


![image](https://github.com/user-attachments/assets/c9a1b2b2-6b91-4a69-ab09-e26791855de9)

---

Formula to find Number of **Active** Subscribers for each subscription type is given below:

1.  **Basic**
  ```
  
=COUNTIFS(D2:D75001,"Basic",G2:G75001,"FALSE")

 ```

2. **Standard**

 ```
=COUNTIFS(D2:D75001,"Standard",G2:G75001,"FALSE")

 ```

3. **Premium**

```

=COUNTIFS(D2:D75001,"Premium",G2:G75001,"FALSE")

```

---
Result is given below:


![image](https://github.com/user-attachments/assets/760f8203-9495-4190-816b-e0ca009c719c)


---

To get the number of **Inactive** subscribers for each subscription type, we just subtract number active suscriber (for each type) from Total number of subscriber as seen below:

**Basic** 
```
=Q8-T14
```


**Standard** 
```
=Q9-T17
```

**Premium** 
```
=Q10-T20
```
---
Result is given below:

![image](https://github.com/user-attachments/assets/411cc9c3-6049-41d5-a852-1755e4408a32)

Therefore Judging by the Active and Inactive subscriber analysis done above, **Basic Subscription** is the Most Popular subscription type, since it has the Highest number of Active Subscriber which is  **26,250** and the Total Number of Basic subscriber is **37,500**

**Average Subscription Duration**


  ```
     =AVERAGE(I2:I75001)

  ```
The results from the formula is given as:  **365**
---
### **EXCEL DASHBOARD**
---



![Screenshot 2024-11-12 142639](https://github.com/user-attachments/assets/b4a9b192-d2db-41ae-875d-11b9b0cda071)


![Screenshot 2024-11-12 142801](https://github.com/user-attachments/assets/93871354-df9e-492e-88bc-9668683db2b4)
