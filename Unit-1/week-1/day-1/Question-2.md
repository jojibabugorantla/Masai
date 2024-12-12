# Day - 01 Assignments Second Question Solution

## Q1. Basic Function Declaration

**Prompt :-** write a function to subtract a, b it return the difference and test different inputs in JavaScript

**Answer :-** Here's a complete example of a JavaScript function `subtract(a, b)` that subtracts two numbers and returns their difference. The code also includes various test cases to check different inputs:

```JavaScript
// Function to subtract two numbers
function subtract(a, b) {
  return a - b; // Return the difference
}

// Testing the function with different inputs
console.log("Test 1: 10 - 5 =", subtract(10, 5));       // Expected output: 5
console.log("Test 2: 0 - 7 =", subtract(0, 7));        // Expected output: -7
console.log("Test 3: 15 - 15 =", subtract(15, 15));    // Expected output: 0
console.log("Test 4: -5 - 5 =", subtract(-5, 5));      // Expected output: -10
console.log("Test 5: 100 - (-50) =", subtract(100, -50)); // Expected output: 150
console.log("Test 6: -20 - (-30) =", subtract(-20, -30)); // Expected output: 10
console.log("Test 7: 50 - 100 =", subtract(50, 100));  // Expected output: -50
console.log("Test 8: 0 - 0 =", subtract(0, 0));        // Expected output: 0
console.log("Test 9: 123 - 321 =", subtract(123, 321)); // Expected output: -198
```

---

### Explanation:

1. **Function `subtract(a, b)`**:
   - Takes two numbers `a` and `b`.
   - Computes the difference `a - b`.
   - Returns the calculated difference.

2. **Test Cases**:
   - **Test 1**: Subtract two positive numbers (`10 - 5`).
   - **Test 2**: Subtract a larger number from 0 (`0 - 7`).
   - **Test 3**: Subtract two equal numbers (`15 - 15`).
   - **Test 4**: Subtract a positive number from a negative number (`-5 - 5`).
   - **Test 5**: Subtract a negative number from a positive number (`100 - (-50)`).
   - **Test 6**: Subtract two negative numbers (`-20 - (-30)`).
   - **Test 7**: Subtract a larger number from a smaller number (`50 - 100`).
   - **Test 8**: Subtract zero from itself (`0 - 0`).
   - **Test 9**: Subtract a larger number from a smaller number (`123 - 321`).

---

You can run this code in any modern browser's JavaScript console or Node.js environment to see the results. Each test will output the expected difference for validation.


## Q2. Function with Default Parameters

**Prompt :-** write a function that greet(name="Guest") to user if no user is passed then print default one in JavaScript

**Answer :-**Here’s a JavaScript function `greet(name = "Guest")` that greets a user. If no name is passed to the function, it will print the default greeting for `"Guest"`:

```JavaScript
// Function to greet a user
function greet(name = "Guest") {
  console.log(`Hello, ${name}!`);
}

// Test cases
greet(); // No name passed; should print "Hello, Guest!"
greet("Alice"); // Name provided; should print "Hello, Alice!"
greet("Bob"); // Name provided; should print "Hello, Bob!"
```

---

### Explanation:
1. **Function `greet(name = "Guest")`**:
   - The `name` parameter has a default value of `"Guest"`.
   - If no name is provided when calling the function, `"Guest"` will be used as the default value.

2. **`console.log()`**:
   - This is used to print the greeting message to the console.

3. **Test cases**:
   - `greet()` will call the function without any argument, so the default name (`"Guest"`) will be used.
   - `greet("Alice")` and `greet("Bob")` pass specific names as arguments, so those will be used in the greeting.

---

### Expected Console Output:
```
Hello, Guest!
Hello, Alice!
Hello, Bob!
```



## Q3. Function Expression

**Prompt :-** write a function to divide to numbers a b that return result as a / b = result  division of 20 by 4 in JavaScript.

**Answer :-**
Here’s a JavaScript function that takes two numbers (`a` and `b`), divides them, and returns the result in the format `a / b = result`. We'll then use it to perform the division of `20 / 4`:

```javascript
// Function to divide two numbers and return the result in a formatted string
function divide(a, b) {
  if (b === 0) {
    return "Division by zero is not allowed.";
  }
  return `${a} / ${b} = ${a / b}`;
}

// Test the function with 20 divided by 4
console.log(divide(20, 4)); // Expected output: "20 / 4 = 5"
```

---

### Explanation:

1. **Function `divide(a, b)`**:
   - Performs division `a / b`.
   - Includes a check to ensure `b` is not zero to avoid a runtime error (division by zero).
   - Returns the string formatted as `"a / b = result"`.

2. **Test Case**:
   - We use `divide(20, 4)` to test the division of 20 by 4.

---

### Expected Console Output:
```
20 / 4 = 5
```



## Q4. Callback Functions

**Prompt :-** write a function to processnumbers(number, callback) that callback for every number and the callback funtion return square of number  that only prints square of number 
in  javascript 

**Answer :-** Here's how you can define a `processNumbers` function that takes an array of numbers and a callback function. The callback will return the square of each number, and the function will print only the square of each number:

```javascript
// Function to process numbers with a callback
function processNumbers(numbers, callback) {
  for (let i = 0; i < numbers.length; i++) {
    const result = callback(numbers[i]); // Call the callback function
    console.log(result); // Print the returned square
  }
}

// Callback function to return the square of a number
function getSquare(number) {
  return number * number;
}

// Test with an array of numbers
const numbersArray = [1, 2, 3, 4, 5];
processNumbers(numbersArray, getSquare);
```

---

### Explanation:

1. **`processNumbers(numbers, callback)`**:
   - Loops through the array of numbers.
   - Calls the provided `callback` function for each number.
   - Prints the result (square of the number) returned by the callback.

2. **`getSquare(number)`**:
   - This is the callback function that computes and returns the square of a given number.

3. **Test**:
   - We test the function with the array `[1, 2, 3, 4, 5]`.

---

### Expected Console Output:
```
1
4
9
16
25
```


## Q5. Anonymous Function in Array Method

**Prompt :-** create an anonymous function that returns multiples of 3 the input values in an array the output containe the output is original array and new array in javascript

**Answer :-** Here’s how you can create an anonymous function that takes an input array, calculates multiples of 3 for each number, and returns both the original array and the new array of multiples:

```javascript
// Function that returns the original array and multiples of 3 in a new array
const processNumbers = (function(numbers) {
  // Map over numbers and return multiples of 3
  const multiplesOfThree = numbers.map(function(number) {
    return number * 3;
  });
  
  // Return both the original and new array
  return {
    originalArray: numbers,
    multiplesOfThree
  };
})([1, 2, 3, 4, 5]); // Input array

// Log the output
console.log("Original Array: ", processNumbers.originalArray);
console.log("Multiples of 3: ", processNumbers.multiplesOfThree);
```

---

### Explanation:

1. **Anonymous IIFE (Immediately Invoked Function Expression)**:
   - The anonymous function is executed immediately using `()`.
   - It processes the array and returns an object containing the original array and its multiples of 3.

2. **`.map()`**:
   - The map method computes the multiples of 3 by multiplying each number in the array by `3`.

3. **Return an object**:
   - The returned object contains:
     - `originalArray`: The input array.
     - `multiplesOfThree`: The new array containing the computed multiples.

---

### Expected Console Output:
```
Original Array:  [1, 2, 3, 4, 5]
Multiples of 3:  [3, 6, 9, 12, 15]
```