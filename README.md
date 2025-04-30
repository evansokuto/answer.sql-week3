# answer.sql-week3

CREATE TABLE Customers (
    CustomerID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Age INT,
    Country VARCHAR(50)
);

INSERT INTO Customers (CustomerID, FirstName, LastName, Age, Country)
VALUES (1, 'Harry', 'Potter', 31, 'UK');

INSERT INTO Customers (CustomerID, FirstName, LastName, Age, Country)
VALUES
    (2, 'Hermione', 'Granger', 30, 'UK'),
    (3, 'Ron', 'Weasley', 31, 'UK');

    UPDATE Customers
SET Age = 32
WHERE CustomerID = 1;
UPDATE Customers
SET FirstName = 'Harry', Country = 'USA'
WHERE CustomerID = 1;

