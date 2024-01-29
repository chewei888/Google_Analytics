# Google_Analytics
The objective of this project is to extract data from Google Analytics and import it into Azure SQL Database for further usage. The data schema and connection have been updated to the latest version of Google Analytics, GA4. 

The extracted data from GA4 includes the following metrics: 
* Total Users
* Sessions
* Transactions
* Screen Page Views

The Python script will perform the following operations:
1. Retrieve the data from GA4
2. Transform the data as required
3. Load the transformed data into the cloud database
