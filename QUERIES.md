1. SELECT * FROM Department;
Description: Fetches all records from the Department table.

Purpose: View all available departments in the system.

2. SELECT * FROM Gender;
Description: Retrieves all entries from the Gender table.

Purpose: Review gender options currently used in the database.

3. SELECT * FROM Employee;
Description: Lists every employee along with all their details.

Purpose: View the complete dataset of employees.

4. SELECT * FROM Employee WHERE CITY = 'OKC';
Description: Returns employees located in the city "OKC".

Purpose: Filter employees by specific location.

5. SELECT * FROM EMPLOYEE WHERE GENDERID=1 AND SALARY >=5000;
Description: Gets male employees (GENDERID=1) who earn at least $5,000.

Purpose: Analyze high-earning male employees.

6. SELECT * FROM EMPLOYEE WHERE GENDERID=2 AND SALARY >=5000;
Description: Retrieves female employees (GENDERID=2) with salaries of $5,000 or more.

Purpose: Analyze high-earning female employees.

7. SELECT ID, NAME, EMAILID, CITY FROM EMPLOYEE WHERE GENDERID=1 OR SALARY >=10000;
Description: Selects basic details of male employees or those with salaries ≥ $10,000.

Purpose: Identify either male staff or top earners across all genders.

8. SELECT * FROM EMPLOYEE WHERE GENDERID =1 AND SALARY >=2000;
Description: Lists male employees earning at least $2,000.

Purpose: Broader view of earning male employees with a lower salary threshold.

9. SELECT * FROM EMPLOYEE WHERE (CITY = 'DALLAS' AND GENDERID=1) OR (DEPARTMENTID=3);
Description: Fetches male employees from Dallas or any employee in the Payroll department (DEPARTMENTID=3).

Purpose: Combine filters based on city/gender and department.

10. UPDATE EMPLOYEE SET SALARY = 20000 WHERE DEPARTMENTID=3;
Description: Updates all employees in the Payroll department to have a fixed salary of $20,000.

Purpose: Apply a bulk salary revision for a specific department.

11. SELECT * FROM EMPLOYEE WHERE DEPARTMENTID=3;
Description: Shows employees who belong to the Payroll department.

Purpose: Validate updates or analyze department members.

12. DELETE FROM EMPLOYEE WHERE CITY = 'DALLAS';
Description: Deletes all employee records where the city is Dallas.

Purpose: Remove entries for employees based in a specific location.

13. SELECT * FROM Employee;
Description: Shows the updated list of employees after deletion and updates.

Purpose: Final check to review the current state of the Employee table.
