# JS-function-3
Topics
Destructuring for finding the highest salary.
Destructuring for swapping values.
Problem Statements
Highest Paid: Define a function highestPaid that takes an array of employee objects, 'employees', as a parameter. Use destructuring to find the employee with the highest salary. Return the employee object with the highest salary.
Example Invocation:

javascript

const employees = [
  { name: "John Doe", age: 30, department: "HR", salary: 50000 },
  { name: "Jane Smith", age: 28, department: "Finance", salary: 60000 },
  { name: "Alex Johnson", age: 35, department: "IT", salary: 70000 },
];

console.log(highestPaid(employees)); // Output: { name: 'Alex Johnson', age: 35, department: 'IT', salary: 70000 }
Destructuring to Swap: Define a function destructuringToSwap that takes an array of employee objects, 'employees', as a parameter. Use destructuring to swap the values of the first and last employees in the array. Return the modified 'employees' array.
Example Invocation:

const employees = [
  { name: "John Doe", age: 30, department: "HR", salary: 50000 },
  { name: "Jane Smith", age: 28, department: "Finance", salary: 60000 },
  { name: "Alex Johnson", age: 35, department: "IT", salary: 70000 },
];

console.log(destructuringToSwap(employees)); // Output: [ { name: 'Alex Johnson', age: 35, department: 'IT', salary: 70000 }, { name: '
