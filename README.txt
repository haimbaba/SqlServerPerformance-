This Mechanism was built for improve ETL performance when loading data to SQL SERVER Database.
You should drop all metadata table (Primary keys Indexes ) before loading data and then create it again when you finish loading data.
In case that creating fails it  because your data have problems (For Example you load not unique values to column that define as Primary Key).

How to build Mechanism:
Zip file contains 5 SQL queries. Run it on your Database in this order.

Testing
Zip File contain Testing file to check it. I run it on AdventureWorks Database.
Table Name - ContactType

NOTE:
I run all this  mechanism from sa user
If you get any errors probably it cause by privileges issues. 
