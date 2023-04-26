# my-data-project

This is all about my on-going data project. 

In this project, I decided to use data to analyse data professionals. The raw data was data from a survey done by AlexTheAnalyst on YouTube. The raw data can be found here https://github.com/AlexTheAnalyst/Power-BI.

Some of the questions I am interested answering in are:

What are the most common data profession roles
What proportion of data professionals are career switchers
What was the most common salary for data professionals
What is the most preferred industry for data professionals
Level of Satisfaciton with Career
Work life Balance
The % of women working in Data
The % of ethnic minorities in Data
The average age
How difficult it is to make the career switch into Data

I decided to use Synapse Analytics to analyse the Data because it is a powerful and versatile tool for analyzing data, offering scalability, speed, integration, security, and cost-effectiveness. Synapse Analytics integrates with a wide range of data sources and tools, including Azure Data Factory, Power BI, and Azure Machine Learning. This makes it easier to bring all the data together and analyze it in one place.

STEPS

1. I created a resource group on Azure
2. Created an Azure SQL Databse and configured as a general purpose - serverless compute to keep the costs low
3. I used a public endpoint so that I can connect to my server publically or privately and deployed the Azure SQL database
4. I then used the server name to connect it to Azure Data Studio, using the log in details I created when configuring the Azure SQL Database.
5. Converted the original raw data into a CSV file so it is readable by Azure SQL DB.
6. Created an Azure SQL database in Data Studio and imported flat files from the wizard.
7. Clean up and organise the data
8. Use synapse analytics to import the database
9. Create a dashboard visualisation showing the results
