IF OBJECT_ID('EMPLOYEE', 'U') IS NOT NULL
    DROP TABLE EMPLOYEE;

CREATE TABLE EMPLOYEE (
    empId INT,
    name VARCHAR(15),
    dept VARCHAR(10),
    salary INT,
    city VARCHAR(20),
    age INT
);

INSERT INTO EMPLOYEE(empId, name, dept, address, salary, age) VALUES
(1, 'Itachi', 'IT', 'Chennai', 60000, 26),
(2, 'Naruto', 'CSE', 'Madurai', 89000, 30),
(3, 'Zenitsu', 'BME', 'swordsmith', 72000, 35),
(4, 'Tanjiro', 'ECE', 'swordsmith', 40000, 45),
(5, 'Luffy', 'IT', 'onepiece', 80000, 34),
(6, 'Eren', 'IT', 'Ragako', 60000, 23),
(7, 'Light', 'IT', 'Tokyo', 50000, 56),
(8, 'Meliodis', 'AIDS', 'Bitania', 67000, 39);
SELECT*FROM EMPLOYEE
WHERE city= 'Madurai' OR city='Chennai';
