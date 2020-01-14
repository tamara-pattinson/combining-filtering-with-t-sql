# combining-filtering-with-t-sql
If you are unable to attach the databases located in the zip file, use the following steps:

1.  Using SSMS, create 2 databases, Northwind and pubs
2.  Using SSMS, open the NorthwindObjectsAndData.SQL and execute
3.  Using SSMS, open the pubsObjectsAndData.SQL and execute

*NOTE:  If you are using older versions of SQL Server, CONCAT_WS and FETCH NEXT are not available.  
Comment out the stored procedure populate_table, 
DELETE the pubs database
Recreate the pubs database and execute the pubsObjectsAndData.SQL again.

This should create the databases as used in the examples for the course:
Combining and Filtering Data with T-SQL
