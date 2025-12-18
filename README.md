# Customer Segmentation Project
Customer Segmentation is a data analytics project focused on grouping customers into distinct segments based on their behavior and characteristics. This project helps businesses understand customer patterns, improve marketing strategies, and make data-driven decisions.

* OBJECTIVES
1.Analyze customer data to identify trends and patterns
2.Segment customers into meaningful groups
3.Enable targeted marketing and personalization
4.Support better business decision-making

* DATASET DESCRIPTION:
The dataset includes customer-related information such as demographics, purchasing behavior, transaction frequency, and spending patterns. The data was cleaned and prepared before analysis.

*🧹DATA CLEANING & PREPROCESSING:
 1.Removed duplicate records
 2.Handled missing and null values
 3.Standardized column names and formats
 4.Ensured data accuracy and consistency

* 📊 ANALYSIS & METHODOLOGY:
 1.Performed Exploratory Data Analysis (EDA)
 2.Identified key attributes influencing customer behavior
 3.Segmented customers based on similarities
 4.Analyzed each segment to extract actionable insights

* 📈 VISUALIZATION & DASHBOARD:
 1.Created visualizations to represent customer segments
 2.Highlighted key metrics and trends
 3.Improved interpretability for business stakeholders

* DAX FUNCTIONS USEDs:
  1.Total Customers = COUNTROWS('Customer_Segmentation')
  2.Total Countries = DISTINCTCOUNT(Customer_Segmentation[country])
  3.Total companies = DISTINCTCOUNT(Customer_Segmentation[company_name])
  4.Total Departments = DISTINCTCOUNT(Customer_Segmentation[department])
  
* NOTE: Power BI (.pbix) files cannot be previewed directly on GitHub. Dashboard screenshots are included for reference.

* 🛠 TOOLS & TECHNOLOGIES USED:
  Python
  Power BI
  Pandas, NumPy
  CSV / Excel
  Git & GitHub

*  PROJECT STRUCTURE:
 Customer-Segmentation/
│
├── data/
│ └── customer_data.csv
├── notebooks/
│ └── customer_segmentation_analysis.ipynb
├── ddashboard/
│ └── customer_segmentation.pbix
├── screenshots/
│ └── dashboard_preview.png
├── README.m

* ✅ KEY OUTCOMES:
 1.Identified distinct customer segments
 2.Provided insights for targeted marketing
 3.Improved understanding of customer behavior
