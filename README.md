Business_Intelligence_Internship_Project_iNeuron

# Amazon Sales Data Analysis with Python and Power BI

### Problem Statement:
The management team at Amazon wants to understand market behavior and sales trends for gaining a competitive advantage. The project's objective is to create a simple report on year-wise and month-wise sales trends, aiming to identify the key factors influencing sales. To achieve this, they plan to utilize the Business Intelligence tool Power BI for visualizing the sales data.

### Data Description:

The Dataset consists of following columns:

1.	Discount Amount: Discount on every ordered item
2.	Date: Ordered Date
3.	Item: Name of the item ordered
4.	List Price: The price at which the item is listed.
5.	Sales Amount: Total amount of sales for particular item.
6.	Sales Cost Amount: Amount spent for conversion of Sale
7.	Sales Margin Amount: Margin amount on each item sold
8.	Sales Quantity: Total number of items sold
9.	Sales Representative: Representative under whom sale is completed.

### Tools Used
- **Programming Language: Python**
- **Python Libraries: Numpy, Pandas**
- **Business Intelligence Tools: Excel, Power BI**

### Project Steps

##### Data Import & Data Cleaning
The given dataset is in an Excel file with some impurities. To prepare the data for creating visuals, we import it into a Jupyter Notebook for cleaning. Data cleaning is a crucial step to handle missing values and incorrect data types. We use Python's Pandas library for data cleaning, ensuring the dataset is ready for visualization purposes.

##### Data Importing in Power BI
In Power BI, we have options to connect to our dataset via various options such as SQL Server, MYSQL, excel or CSV files. We have our clean data in CSV file. We will import it in Power BI with import data option and start working with it. 

##### Data Transformation in Power BI
Once the data is imported in Power BI, we do ‘transform data’ i.e. using Power Query editor to perform certain operation on to the data. Ensuring correct data types, creating custom/conditional columns are some fundamental task performed in Power Query.

##### Creating a Report in Power BI
A report is created in Power BI with various charts depicting Sales insights for particular year, month and so on. We created Slicers, Data Cards, Sales Trend for Year and Month, Table for top ordered item, top performing sales representatives and relationship between different variables that directly or indirectly impact sales.

##### Deployment in Power BI
In Power BI, You can directly publish the report online to your workstation. You can also save the file in ‘.pbix’ version and can update the content of your Power BI apps using a deployment pipeline, giving you more control and flexibility when it comes to your app's lifecycle. Use the publish or view button in the workspace card to publish or view the app in a specific pipeline stage.
