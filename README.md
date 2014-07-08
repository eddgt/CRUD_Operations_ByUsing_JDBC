CRUD( Create Read Update Delete) Operations By Using JDBC
=========================================================

Step1: Create Student table

CREATE TABLE STUDENT
   (ID NUMBER(19,0) NOT NULL, 
	  NAME VARCHAR2(255 CHAR), 
	  AGE NUMBER(10,0), 
	  PRIMARY KEY (ID));
	  
	  
Output:
---------------------------------------------------------

Before Update : Student [studentId=2, studentName=Ranga, age=20]
After Update : Student [studentId=2, studentName=RangaReddy, age=25]

