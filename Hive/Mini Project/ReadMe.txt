Dear Participant,

Please find below the Mini Project of Big Data on Hadoop. Please note this is an individual assignment. Kindly complete it before it's deadline.

Dataset : Consultentdata -943 Records.txtView in a new window

Analyse Employee Dataset using Hadoop

Using Hadoop command move all those employees data into HDFS directory "/user/your_user_name/employees_data" directory
Create an external Hive table "employees_Table" representing this "employees_data". This table will have 4 fields id,age,gender,role and salary.
create a new bucketed table "Consultant_Table_Bucket" having 4 buckets on the field salary. This table should store the data into columnar format ORC
Insert all those employees whose salary is greater than 5000 into bucketed table "Consultant_Table_Bucket" from "employees_Table" table. While inserting into "Consultant_Table_Bucket" table you need to convert "consultant" role into "BigData Consultant" role.
  6. Write a Hive query to find out Max, min salary of "BigData Consultant" from the       "Consultant_Table_Bucket" table