SQL aggregate functions : AVG(), COUNT(), MIN(), MAX(), and SUM().
Except for the COUNT() function, SQL aggregate functions ignore null.
Example : AVG()-------SELECT  department_name, ROUND(AVG(salary), 0) avg_salary FROM employees
        INNER JOIN departments USING (department_id) GROUP BY department_name ORDER BY department_name;
        
        
Difference Between MySQL and Oracle:
        https://www.javatpoint.com/mysql-vs-oracle

Diffrences Between MySQL and NoSQL:
      https://www.tutorialspoint.com/difference-between-sql-and-nosql#:~:text=Difference%20between%20SQL%20and%20NoSQL%20%20%20,Brewers%20%20...%20%202%20more%20rows%20
