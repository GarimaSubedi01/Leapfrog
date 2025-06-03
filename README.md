### 💻 Day 1

**Objective:** Creating a table, inserting data, and filtering based on a condition.

 ✅ Code:
CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(20) NOT NULL,
    age INT
);

INSERT INTO students (name, age) VALUES
('Max', 19),
('Robin', 21),
('Billy', 17),
('Dustin', 20);

SELECT * FROM students WHERE age > 18;
