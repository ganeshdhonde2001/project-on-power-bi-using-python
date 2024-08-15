# project-on-power-bi-using-python<br>
in this practice project i used varius python libraries to - Clean and transform the collected data to ensure accuracy and consistency.<br>
<br>
some of the steps -<br>
1. Data Collection (Kaggle): - Identify data sources: CRM systems, ERP systems, spreadsheets, etc. - Gather relevant sales data, including transactional data, customer data, and product data. - Ensure data quality by addressing issues such as missing values, duplicates, and <br>
inconsistencies.<br>
<br>
3. Data Preparation: - Clean and transform the collected data to ensure accuracy and consistency. - Perform data preprocessing tasks such as filtering, sorting, and aggregating. - Normalize data formats and resolve any data quality issues. <br>
Importing Divali sales data.csv <br>
[# import csv file<br>
df = pd.read_csv('Diwali Sales Data.csv', encoding= 'unicode_escape')]<br>
<br>
3.Dataset cleaning: 
Removed empty columns from dataset:<br>
[#drop unrelated/blank columns<br>
df.drop(['Status', 'unnamed1'], axis=1, inplace=True)]
<br>
4.Data Modelling: - Design and implement a data model within Power BI using Power Query and/or DAX. - Define calculated columns and measures to derive meaningful insights from the data.<br> 
Created new column for AvgDelivery.<br>
Created new table for sales forcasting. <br>
5. Visualization Development: - Develop interactive dashboards and reports using Power BI Desktop. - Select appropriate visualizations such as bar charts, line charts, pie charts, and maps. - <br>Customize visualizations to effectively represent sales data and highlight key insights. - Incorporate slicers, filters, and drill.<br>
