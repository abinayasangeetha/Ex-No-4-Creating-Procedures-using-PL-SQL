# Ex. No: 4 Creating Procedures using PL/SQL

### AIM:
To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
create or replace procedure insert_emp_data AS
begin
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (1,'ABINAYA','Finance',60000);
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (2,'RADHA','MD',65000);
insert into employeetbl1 (Empid,Empname,Dept,Salary)
values (3,'KRISHNA','HR',75000);
commit;
end;
/
Procedure created.

begin
insert_emp_data;
end;
/

PL/SQL procedure successfully completed.
### Output:
![dbms op4](https://github.com/abinayasangeetha/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393675/5d85fefa-22aa-4026-bcda-ae76ddf223c4)
![Screenshot 2023-09-30 194332](https://github.com/abinayasangeetha/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393675/956624c1-7d4a-452e-854b-ee8f16a00d91)

### Result:
To create a procedure using PL/SQL is executed successfully.
