# Day - 01 Assignments First Question Solutions

## Q1. Create and Access Object Properties

**Prompt :-** 
    create book object with properties title, author, publishedyead print them and next i want to update the pubished year and print only updated value write code JavaScript

**Answer :-**
Here's the JavaScript code that follows your request:

```JavaScript
// Create a JavaScript object named book
const book = {
  title: "The Great Gatsby",
  author: "F. Scott Fitzgerald",
  publishedYear: 1925
};

// Print the original properties
console.log("Title:", book.title);
console.log("Author:", book.author);
console.log("Published Year:", book.publishedYear);

// Update the publishedYear property
book.publishedYear = 2024;

// Print only the updated publishedYear value
console.log("Updated Published Year:", book.publishedYear);
```

This will output:  
```
Title: The Great Gatsby
Author: F. Scott Fitzgerald
Published Year: 1925
Updated Published Year: 2024
```

## Q2. Add Methods to Objects
**Prompt :-** Create an object employ with name, position, salary then write a method raise the salary by 10 percent and print original salary and updated salary as output in JavaScript

**Answer :-**
Here’s a JavaScript implementation with the requested structure:

```JavaScript
// Create an employee object with a method to raise the salary
let employee = {
    name: "John Doe",
    position: "Software Engineer",
    salary: 50000,

    // Method to raise salary by 10%
    raiseSalary: function() {
        console.log("Original Salary: $" + this.salary);
        this.salary *= 1.10; // Increase salary by 10%
        console.log("Updated Salary: $" + this.salary.toFixed(2));
    }
};

// Call the method to raise the salary and print the results
employee.raiseSalary();
```

### Explanation:
1. The `employee` object includes the properties `name`, `position`, `salary`, and a method `raiseSalary`.
2. The `raiseSalary` method:
   - Logs the original salary.
   - Updates the `salary` property by multiplying it by `1.10` (a 10% increase).
   - Logs the updated salary, formatted to two decimal places using `.toFixed(2)`.
3. The method is invoked as `employee.raiseSalary()` to update the salary and print the results. 

This approach encapsulates the functionality within the object, aligning with object-oriented programming principles.


## Q3. Nested Objects
**Prompt :-** write an object university with values name, location, and departments that departments should be and array each  container a head and print all the departments only in a single line seperated with cama in JavaScript

**Answer :-**
Here’s how you can create the `university` object and print the departments in a single line, separated by commas:

```JavaScript
// Create a university object
let university = {
    name: "Tech University",
    location: "New York",
    departments: [
        { name: "Computer Science", head: "Dr. Smith" },
        { name: "Mathematics", head: "Dr. Johnson" },
        { name: "Physics", head: "Dr. Brown" },
        { name: "Chemistry", head: "Dr. White" }
    ]
};

// Extract and print department names in a single line separated by commas
let departmentNames = university.departments.map(dept => dept.name).join(", ");
console.log("Departments: " + departmentNames);
```

### Explanation:
1. **Object Structure**:
   - The `university` object includes `name`, `location`, and `departments`.
   - The `departments` property is an array of objects, where each object represents a department with a `name` and `head`.

2. **Extracting Department Names**:
   - The `map()` function iterates through the `departments` array, extracting the `name` of each department.
   - The `join(", ")` method combines the department names into a single string, with each name separated by a comma.

3. **Output**:
   - The final string is printed with the `console.log` statement.

#### Example Output:
```
Departments: Computer Science, Mathematics, Physics, Chemistry
```

## Q4. Object Destructuring
**Prompt :-** 
wrte an car object  with properties make, model, year, and price. Use object destructuring to extract make and model into separate variables and print them.

**Answer :-**
Here’s how you can create a `car` object and use object destructuring to extract `make` and `model`:

```JavaScript
// Create a car object
const car = {
    make: "Toyota",
    model: "Camry",
    year: 2022,
    price: 25000
};

// Destructure the make and model properties into separate variables
const { make, model } = car;

// Print the extracted values
console.log("Make:", make);
console.log("Model:", model);
```

### Explanation:
1. **Object Structure**:
   - The `car` object has properties `make`, `model`, `year`, and `price`.

2. **Object Destructuring**:
   - The syntax `{ make, model } = car` extracts the `make` and `model` properties from the `car` object into separate variables named `make` and `model`.

3. **Output**:
   - The `console.log` statements print the values of `make` and `model`.

#### Example Output:
```
Make: Toyota
Model: Camry
```

## Q5. Object Destructuring
**Prompt :-** create a sutedent object with properties name, age and grade. and next add a new property email with value and print all output
**Answer :-**
Here’s how you can create a `student` object, add a new property, and print all its properties:

```JavaScript
// Create a student object with initial properties
const student = {
    name: "Alice Johnson",
    age: 20,
    grade: "A"
};

// Add a new property email
student.email = "alice.johnson@example.com";

// Print all properties and their values
for (let key in student) {
    console.log(`${key}: ${student[key]}`);
}
```

### Explanation:
1. **Object Initialization**:
   - The `student` object is created with properties `name`, `age`, and `grade`.

2. **Adding a New Property**:
   - The `email` property is added to the object using dot notation: `student.email = "value"`.

3. **Printing Properties**:
   - A `for...in` loop iterates through the object’s keys.
   - The keys and their values are printed using template literals.

#### Example Output:
```
name: Alice Johnson
age: 20
grade: A
email: alice.johnson@example.com
```