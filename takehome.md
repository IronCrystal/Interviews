# Triblio Pre-Interview Coding Questions

Work at your own pace, finish as much as you can!
We'll go over your answers during the technical portion of
the interview, so be prepared to explain your answers.
Please reach out if you have any questions.

## 1. FizzBuzz

Write a function that prints the numbers from 1 to 100.
But for multiples of three print “Fizz” instead of the 
number and for the multiples of five print “Buzz”.
For numbers which are multiples of both three and five print “FizzBuzz”.

```
function fizzBuzz() {
}
```

## 2. Passport Parsing

Follow the instructions found at https://adventofcode.com/2020/day/4 There are 2 parts.


## 3. SQL Questions

Here is an example of two tables in a database, given this schema,
write queries to return the desired data.

```
CREATE TABLE employees (
  employee_id INTEGER PRIMARY KEY,
  name STRING,
  salary INTEGER,
  department_id INTEGER
);

CREATE TABLE departments (
  department_id INTEGER PRIMARY KEY,
  name STRING
);
```
### Queries
- Return employee record with highest salary
- Return the highest salary in the employees table
- Return the 2nd highest salary in the employees table
- Return a range of employees based on id (i.e. 6,7,8,9,10)
- Return the employee with the highest salary and the employee's department name
- Return highest salary, employee name, department name for each department