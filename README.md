

Employees Data

1. Write a query to create the Employees table

ANS: CREATE TABLE EMPLOYEES
(
EMPLOYEE_ID INT (10) PRIMARY KEY,
NAMES CHAR(20),
MONTHS INT (10),
SALARY INT(10)
);

INSERT INTO EMPLOYEES VALUES (12228, "RAHUL", 15,10000), 
(33645, "AMIT", 1, 15000), (45692, "ADITI", 17,18000),
(56188, "PAVAN", 11, 21000);
SELECT * FROM EMPLOYEES;
 

Q2.i) Count the total no. of employees.

ANS: SELECT COUNT(*) AS TOTAL_EMPLOYEES FROM EMPLOYEES;


  
ii) Find the salary of Rahul.  

ANS: SELECT NAMES,SALARY FROM EMPLOYEES WHERE EMPLOYEE_ID = 12228;


                                                                                                
iii) Set Amit’s months to 12.

ANS: UPDATE EMPLOYEES SET MONTHS = 12 WHERE EMPLOYEE_ID = 33645;

                    
                                                                                                             
iv) Find the sum of salaries of all employees.

ANS: SELECT SUM(SALARY) AS TOTAL_SALARY FROM EMPLOYEES;
                           
              

v) Find no. of employees whose name starts with ‘A’.

ANS: SELECT COUNT(*) AS EMP_NAME_WITH_A FROM EMPLOYEES WHERE NAMES LIKE 'A%';


      
 

       






