# NorthwindOracleDatabase
A Direct Export of MSSQL Northwind sample database to Oracle 19c 

# Date: 14.06.2025

This sample database was exported directly from MS SQL to Oracle database 19c. I have dropped invalid objects, modified the PLSQL to fix the views and procedures and as on the time the DDL from 19c was creaetd, there were no invalid objects.

## Instructions##

-1. Create a new schema 'NORTHWIND' on tablespace EXAMPLE
-2. Use Oracle SQL Developer. Open, inspect and execute to create the objects
-3. All the procedures return ref_cursors, adjust your application accordingly or change the procedure for your preferred returned values.

