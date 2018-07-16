
MSBI stands for Microsoft Business Intelligence. The powerful suite tool developed by Microsoft which offers best solutions for BI (Business Intelligence and Data-Mining Quires. This tool uses Microsoft visual studio data tools + SQL server. It provides different processes for different tools for BI solutions.

MSBI is divided into 3 entities
•	SSIS - SQL Server Integration Services.
•	SSAS - SQL Server Analytical Services.
•	SSRS - SQL Server Reporting Services.


SSIS: SSIS is basically an integration service it integrates the data from different format like Sybase, Oracle, Text, Excel, MySQL into one format, while doing integration it first refreshes data and cleans data. This integration process is done with the help of OLTP (Online Transaction Processing) component of MS SQL Server.

SSAS: SSAS is analyze service, it analyzes the stored data. SSAS use OLAP (Online Analytical Processing) component and data mining capabilities. For analyze process it build multi-dimensional structures called CUBES and build mining models to perform data analysis and to get valuable information.

SSRS: SSRS is reporting service, Now represent analyze data in a graphical way SSRS is used, SSRS generates reports of analyze data, Reports, Plans, Dashboards, Scorecards, and Excel etc.


Business Intelligent: Business Intelligence is techniques for transforming data into information. This information helps to make quick decisions. 
From the Wikipedia: 
Business intelligence (BI) is the set of techniques and tools for the transformation of raw data into meaningful and useful information for business analysis purposes. BI technologies are capable of handling large amounts of unstructured data to help identify, develop and otherwise create new strategic business opportunities.

The difference between data and information: 
Data is row material for analysis. Data is always related to transactions or events. Once the data is analyzed it's considered to be meaningful information. 

Benefits of BI:
•	Identity Cost Drivers
•	Increase Added Value
•	Monitoring of results
•	Real time reporting
•	Predictive analysis
•	Avoiding long discussion


MSBI Tools

Microsoft provides some tools to transform your business data into information. We can use these tools with the interface of Visual Studio. 
We can download this tool: SQL Server Data Tools (SSDT)

Definition of Database: 
A database is an organized collection of data. The data are typically organized to model aspects of reality in a way that supports processes requiring information.

Database Management Systems (DBMSs) are specially designed software applications that interact with the user, other applications and the database itself to capture and analyses data. A general-purpose DBMS is a software system designed to allow the definition, creation, querying, update and administration of databases.

ETL (Extracts, Transform, and Load) Tools

ETL means that its takes the data from various source locations, maybe as a different data format (for example SQL, txt, xls and so on) and store this data into a destination (Data Warehouse).

From the Wikipedia: 
In computing, Extract, Transform and Load (ETL) refers to a process in database usage and especially in data warehousing that: 

Extracts data from homogeneous or heterogeneous data sources. 
Transforms the data for storing it in a proper format or structure for querying and analysis purpose. 
Loads it into the final target (database, more specifically, operational data store, data mart, or data warehouse). 

SQL Server Integration Service (SSIS) 
SSIS is the ETL tool from Microsoft. 
Integration Services is a platform for building high-performance data integration and workflow solutions, including extraction, transformation and loading (ETL) operations for data warehousing. 
We can process the data from various locations and various formats (source locations) and save the data into a centralized repository as a Data Warehouse/Data Mart (destination).

It includes graphical tools and wizards for building and debugging packages. 

 

Data Warehouse and Data Mart: 

This is commonly used for reporting and business analysis purposes. This system is actually the output of integrated data from multiple sources and stored into a centralized repository. The Data warehouse stores the current and historical data, so it is easy to generate trend reports, predictive analysis and comparison reports. It's very helpful for the top management to take the quick decisions about the business. 

A Data Mart means that it's a small part of a Data Warehouse and indicates only a single part (for example sales or finance). It always holds more summarized information.

SQL Server Analysis Service (SSAS) 

This is the process of converting two dimensional (rows and columns/OLTP) data into multi-dimensional data model (OLTP). This will help you to analyze the large volume of data.

Some of the advantages:
•	Multi-dimensional analysis
•	Key performance Indicator (KPI)
•	Score card
•	Slice, dice, drill down functionalities
•	Good performance
•	Security and so on.
•	The following shows the differences between On-line Transaction Processing (OLTP) and On-line Analytical Processing (OLAP).



OLTP	OLAP
Storing the current data (always a production environment)	Storing historical and current data from multiple locations
Perform all DML (create, update, read, delete)	Perform only Read
High Availability	Flexible access to data
Normalized database	De-normalized with fewer tables because of less performance with large volume of data.
Data will update frequently	Periodically update the Data
SQL Server Reporting Service

Microsoft SQL Server Reporting Services (SSRS) is an enterprise reporting platform supporting traditional and interactive reports delivered over the web or through custom applications. It supports various data sources like two dimensional and multi-dimensional.

The following are some features of SSRS:
•	Retrieve data from different source
•	Web based access to reports
•	Support for Ad-hoc reporting
•	Report builder helps to customize the reports for end user.
•	Easy subscriptions options
•	Export functionality with lots of format.
•	Display reports in various ways like tabular, chart, Gauge and so on.

