# Task3
/*CREATE TABLE tsk3
( RollNo Int primary key,
Name varchar(10),
Class varchar(5),
Marks Int);*/

/*Insert into tsk3
(RollNo,Name,Class,Marks)
Values(1,'Tapsya','BCA',89),
(2,'Pallvi','MBA',95),
(3,'Sakshi','Btech',80),
(4,'Varun','BCA',100),
(5,'Priya','BA',55),
(6,'Rahul','MA',62),
(7,'Abhinav','BCA',43);*/

/*Select * from tsk3 Where Rollno=1;*/

/*Select * from tsk3 Where Class='BCA' And Marks>90;*/
/*Select *  from tsk3 Where Marks>70 Or Class='BCA';*/
/*Select * from tsk3 Where Name Like '%i';*/
/*Select * from tsk3 Where Marks Between 80 And 100;*/
Select * from tsk3 order by Marks Desc;
 
