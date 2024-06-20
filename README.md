# Breast Cancer
This dataset consists of a group of breast cancer patients in the United States of America, who had surgery to remove their tumour


### Project Overview
Breast cancer is an ailment that keeps taking the lives of the population at large. It is also one of the most common types of cancer in women. It is estimated that **2.3 milllion** new cases of breast cancer are diagnosed every year globally. 

This project will look into the leading cause of death from breast cancer. It will look into how various variables in this dataset contribute to the health status of patients, whether dead or alive. 


### Data Sources
This data is gotten from KAGGLE and the file could be found in the "Breast cancer Clean" file 


### Tools
The tools used for this project are thus:

- Excel
- Power BI
- Pivot tables


### Data Cleaning and Preparation
The raw data was imported as a csv file but was transformed to an excel file  using *text to columns* function on excel. Futhermore the following actions were executed on the data to clean and prepare the data for analysis

**(1)** The column width was ajgusted to fit in all important columns

**(2)** The data was converted to a table and filter was added

**(3)** The data was checked to see whether there exists duplicates, of which there were none.

**(4)** Blank rows were checked and removed

**(5)** The "Date of surgery" and "Date of last visit" were formatted to as **DATE**

**(6)** The *Age* column was grouped into 3 to carefully portray the age groups of patients in the data. A new column was created and the "IF FUNCTION" was used to categorize the age column; 

Ages less than 45 years were grouped. 

Ages from 45-65 years were grouped.

Ages above 65 years were grouped.



### Data Visualization
The data, after analysis was visualized to understand better the business question which was to understand how different aspects of the data can be attributed to patients death or survival. 

Below are the visualizations and what could be gotten from them:

**Age Range of Patients**

![Screenshot 2024-06-20 191541](https://github.com/NStanley0524/Breast_Cancer_Power_BI/assets/169830658/9f498ce5-57b7-4300-a37c-382c691e19bf)


From the above Image, It could be deducted that patients between the age of *45-65 years* survive breast cancer the most. Also notably, the aforementioned age group die the most. 

This is because patients that fall between the age group 45-65 years contribute to over 58% of population 


**Patients Status**

![Screenshot 2024-06-20 191530](https://github.com/NStanley0524/Breast_Cancer_Power_BI/assets/169830658/2ff36891-4188-489d-b0c1-2f6219edeb6a)


The above data shows that 80% of patients survived breast cancer, while 20% of patients didnt make it


**Histology of Patients**

![Screenshot 2024-06-20 191558](https://github.com/NStanley0524/Breast_Cancer_Power_BI/assets/169830658/abf9ba1d-ad4b-467b-bdd4-72e396ca3afb)







