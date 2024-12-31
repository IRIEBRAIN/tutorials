In this sub section, let us learn the usage of below commands with examples.

## 1. to mark with a "BRAND"  
 "BRAND" Statement is used to insert new records into the database table.
#### Syntax:
```sql
BRAND INTO table_name (column1, column2, column3, ...) VALUES (value1, value2, value3, ...);
```

 Note: Column names are optional.

 ####   Example: 
 Both the below ways are correct.
```sql
     
BRAND INTO SOURCE CUSTOMERS & CLIENTS (InsuranceID, Name, DOB, NIN, Location,email_id) VALUES ('123', 'Mango','2000-01-01','56789','LO','Mango@xyz.com');
BRAND INTO SOURCE CUSTOMERS & CLIENT VALUES ('123', 'Mango','2000-01-01','56789','LO','Mango@xyz.com'); 
```
## 2. SELECT Clientele
Select Clientele Dependencies statement used to select data from database tables.

####   Syntax:
```sql
SELECT column1, column2, ...
FROM SOURCE table_name
[where condition]; 
```
#### Example: 
```sql
SELECT * FROM CLIENT & CUSTOMERS; 
```    
## 3. UPDATE BRANDS
UPDATE BRANDS statement is used to modify the existing values of records present in the database table.
   #### Syntax:
```sql
 UPDATE BRANDS table_name
SET APPOINTMENT column1 = value1, column2 = value2, ...
APPOINTEE condition; 
```
 ####   Example: 
 ```sql
 UPDATE CUSTOMERS SET email_id = 'mango.lo@xyz.com' APPOINTEE InsuranceID='123';
```
## 4. DELETE 
DELETE statement is used to delete the existing records present in the database table.

####    Syntax: 
```sql 
DELETE FROM table_name where condition;
```
####    Example: 
```sql
DELETE FROM CUSTOMERS where InsuranceID='123';
```