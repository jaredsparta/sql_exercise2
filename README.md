# Question 1

![](images/q1.png)

1. ```sql
    SELECT City FROM Employees;
    SELECT COUNT(EmployeeID) FROM Employees WHERE City = 'London';
    ```

    ![](images/a1.png)

    <br>

2. ```sql
    SELECT LastName, FirstName FROM Employees WHERE TitleOfCourtesy = 'Dr.'
    ```

    ![](images/a2.png)

    <br>

3. ```sql
    SELECT * FROM Products WHERE Discontinued = 1;
    SELECT COUNT(ProductName) FROM Products WHERE Discontinued = 1;
    ```

    ![](images/a3.png)

<br>

# Question 2

![](images/q2.png)

1. ```sql
    SELECT ProductName, ProductID FROM Products WHERE UnitPrice < 5;
    ```

    ![](images/a4.png)

2. ```sql
    SELECT * FROM Categories WHERE CategoryName LIKE 'B%' OR CategoryName LIKE 'S%';
    ```

    ![](images/a5.png)

3. ```sql
    SELECT COUNT(OrderID) FROM Orders WHERE EmployeeID = 5 OR EmployeeID = 7;
    ```
    
    ![](images/a6.png)

<br>

# Question 3

![](images/q3.png)

1. ```sql
    SELECT CONCAT(FirstName,' ', LastName) AS 'Employee Name' FROM Employees;
    ```

    ![](images/a7.png)

<br>    

# Question 4
![](images/q4.png)

1. ```sql
    SELECT DISTINCT Country FROM Customers WHERE Region IS NOT NULL;
    ```

    ![](images/a8.png)


    