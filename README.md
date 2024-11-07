
# SQL Analysis of Dubai's Off Plan Property Market
La Breeze Limited is a private limited company specializing in real estate investments and development. This project focuses on identifying emerging trends and opportunities within Dubai's off-plan property sector. The property data used for this analysis is publicly available on Kaggle here: [https://www.kaggle.com/datasets/alexefimik/dubai-real-estate-transactions-dataset]

Insights and recommendations are provided on the following key areas:

- **Frequency Analysis by Property:** Analysing the frequency of each off-plan property (e.g. flat, hotel, office) across regions and over time 
- **Regional Comparison Analysis:** An evaluation of average sales per square mile according to each region. Regions being judged by nearest metro station, landmark or mall
- **Property Sales Trend Analysis:** An assessment of property sales trend per square mile trends over time

The SQL queries used to inspect and clean the data for this analysis can be found here [https://github.com/Mohammed0192/Dubai-Off-Plan-Property-analysis/blob/main/SQL%20query%20code]

Targed SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The companies main database structure as seen below consists of four tables: table1, table2, table3, table4, with a total row count of X records. A description of each table is as follows:
- **Properties Table:** Dubai properties data structure consists  date, varchar and numerical data

[https://github.com/Mohammed0192/Dubai-Off-Plan-Property-analysis/issues/1#issue-2636534920]


# Executive Summary

### Overview of Findings

Across Dubai overall, hotels have remained the most expensive off-plan property purchases despite having the largest percentage decrease in average price (per square mile) in the last 3 years. There has been an apparent increase in the prices of OPP shops (per square mile) being purchased across Dubai also. Post-COVID, the average price of OPP flats has decreased but flats in the Mina Seyahi and Jumeirah Beach region have enjoyed noticeable price hikes. Another post-COVID trend are falling OPP office prices across Dubai, perhaps reflecting the post-COVID desire for workers to WFH?

![Screenshot 2024-11-05 220526](https://github.com/user-attachments/assets/7a4d0bd8-5fdf-47bb-b34e-db22b214ea44)
![Screenshot 2024-11-05 220613](https://github.com/user-attachments/assets/70ee6ad3-f62b-4fca-a72a-599587305adb)
![Screenshot 2024-11-05 220707](https://github.com/user-attachments/assets/067ff8a3-ed2c-4fdf-bf7b-11ef3296a68d)


# Insights Deep Dive
### **Growing popularity of Al-Kasir / Marina Area:**:

* **1:**  More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **2:**  More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **3**  More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **4**  More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

![Screenshot 2024-11-07 105942](https://github.com/user-attachments/assets/9269386f-c14e-4dc8-814f-cf360c23e14d)
![Screenshot 2024-11-07 103655](https://github.com/user-attachments/assets/a526734d-1beb-4fbf-bf8d-e3b69dffa3b1)


### Flats over Hotels in downtown areas:

* **OPP Hotels becoming less popular and less centralised.** Less Hotel purchases in downtown Dubai (near Dubai Mall) and prices are more competitive near Al Barsha and Al-Kasir over time.
  
* **Flats are more popular across Dubai.** OPP flats are becoming increasingly popular over time especially in downtown areas but also across Dubai (e.g. other malls like Ibn Battuta and Mirdif) .

![Screenshot 2024-11-05 223232](https://github.com/user-attachments/assets/a6a93495-45e3-4e46-b837-e2623e88890c)
![Screenshot 2024-11-05 224337](https://github.com/user-attachments/assets/cb39ec7c-bd2f-4785-995c-972928ea6c3b)



### Office properties are in less demand post-COVID:

* **Office properties were unpopular pre-COVID.** Across Dubai, some OPP Office purchases have simply stopped (e.g. near Ibn Battuta Mall). But this was exacerbated post-COVID where we see number of Offices in downtown Dubai (near Dubai Mall) match surrounding areas.
  
* **Growing Office Prices in Marina** This fits the overall trend of increased property prices in Marina/Al-Kasir area
  
![Screenshot 2024-11-07 102755](https://github.com/user-attachments/assets/b24e25cd-2035-4b0a-817f-ec514bad4e8a)
![Screenshot 2024-11-07 103342](https://github.com/user-attachments/assets/910a334f-19c5-4f8d-82d7-a4adef00c4d3)


### Growing demand for Shop properties in Jebel Ali Village (IB Mall):

* **Jebel Ali Village competitive space for OPP Shops.** OPP Shop prices near IB Mall have increased noticeably since 2021 yet the number of OPP shop purchases have remained low in that area. Higher prices with limited supply could indicate confidence among investors and developers in the area’s growth potential. 
  
* **OPP Shops are cheaper in Al-Kasir (near Marina Mall).** This reflects the popularity of Al-Kasir that the number of shops have increased in this area, causing a drop in OPP shop prices since 2019 - market saturation?

![Screenshot 2024-11-07 104641](https://github.com/user-attachments/assets/ac7c09d9-0e60-48a0-bb5a-cb9237b10dfe)
![Screenshot 2024-11-07 105046](https://github.com/user-attachments/assets/b524346d-c366-4983-aa6d-6d33fc9bc20b)

# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
