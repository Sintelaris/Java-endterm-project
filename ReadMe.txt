This program must to make cashier work easier and add new employees to database to give access for everyone only via ID and password for each member in organisation.
Only Сashier can take orders.
Only Manager can delete and add new employees.


Java project consist from 6 classes and 1 interface.
1) "Main" class launches the program.
2) "Application" interface provides "example" for "Supermarket_order_helper" class.
3) "Supermarket_order_helper" class executes main console, sessions for Manager and Cashier, stores application version and end program.
4) "Start_session" class is default session for every possible member, didn't used directly in this version of program.
5) Manager_start_session class starts Manager working session.
6) Cashier_start_session class starts Cashier working session.
7) ConnectDatabase class allows connecting to databases flexibly and simply.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
NECESSARY!!!

Standart ID and password for Cashier: 
ID: "2"
Password: "0000";

Standart ID and password for Manager: 
ID: "1"
Password: "0000";

To use this program you need to create two databases with 

"Supermarket" database:
Host: "localhost"
Port: "5432"
Name: "Supermarket"
Username: "postgres"
Password: "12455689"
and query data from "Data for 'Supermarket' database.txt"


"Supermarket_employees" database:
Host: "localhost"
Port: "5432"
Name: "Supermarket_employees"
Username: "postgres"
Password: "12455689"
and query data from "Data for 'Supermarket_employees' database.txt"







