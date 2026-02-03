\# SQL Injection



\## What it is

SQL Injection a users input is improperly handled and included in database queries.



\## Why it happens 

* Lack of prepared statements
* Direct string concatenation
* Insufficient input validation



\## Exploitation (high level)

An attacker manipulates input to alter the intended SQL query logic, which allows unauthorized access to data in the SQL database or authentication bypass of the SQL database.



\## Detection

* Unexpected query behavior
* SQL errors in responses / logs
* Automated scanners
* Manual parameter testing



\## Mitigation

* Use prepared statements
* Parameterized queries 
* Least privilege database accounts 
