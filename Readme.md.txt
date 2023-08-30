Project - Azure DatalakeHouse

Divvy is a bike sharing program in Chicago, The City of Chicago makes the anonymized bike trip data publicly available for projects like this where we can analyze the data.

The purpose of project is to create a DatalakeHouse with the following steps:

Bronze: Extract data in csv format into Azure storage using Spark in Databricks in Jupyter Notebooks

Silver: Load step. Implement key features of Data Lakes on Azure process data using PySpark and Spark.SQL

Gold: Transform step. Create Fact and Dimension tables using Spark and Databricks

Files:
Readme.md - this file
Star-schema proj.4.pdf - Star-schema of the project
dimDate.ipnb - Jupyter script for creating Date dimension table
Proj4.ipnb - Jupyter scripts for creating the rest of tables.


Dimension tables:
Rider:   RiderId, First, Last, Address, Birthday, AccountStartDate, AccountEndDate, IsMember
Station: StationId, Name, Latitude, Longitude
Date: Date, Year, Quarter, Month, Day, DayOfYear, DayOfWeek, IsWeekend

Fact tables:

Payment: PaymentId, Date, Amount, RiderId
Trip: TripId, RideableType, StartAt, EndedAt, Duration, StartStationId, EndStationId, RiderId


References:
https://sparkbyexamples.com/
https://docs.microsoft.com/en-us/azure/
https://www.databricks.com/learn


