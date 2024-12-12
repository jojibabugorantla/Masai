# Day - 01 Assignments Third Question Solution

## Q1.  Data Types

## First Question

**Prompt :-** create a variable name that store cityname in string  and another variable population of type int that stores and print the values in python 

**Answer :-**
Here’s how you can create variables to store a city name (string) and its population (integer) and then print their values in Python:

```python
# Create variables
city_name = "New York"  # String variable to store city name
population = 8419600  # Integer variable to store population

# Print the values
print("City Name:", city_name)
print("Population:", population)
```

---

### Explanation:
1. **`city_name = "New York"`**:
   - A string variable storing the name of the city.

2. **`population = 8419600`**:
   - An integer variable storing the population value.

3. **`print()`**:
   - Displays the values of the variables.

---

### Expected Output:
```
City Name: New York
Population: 8419600
```


## Second Question

**Prompt :-** create a variable that store price value in float and a Boolean that store stock is avalable or not  in python

**Answer :-**
Here’s how you can create a variable to store a price value (as a float) and another variable to store whether the stock is available (as a boolean):

```python
# Declare variables
price = 29.99  # Float variable to store the price value
stock_available = True  # Boolean variable to store stock availability

# Display the values
print("Price: $", price)
print("Stock Available:", stock_available)
```

---

### Explanation:

1. **`price = 29.99`**:
   - A float variable storing the price value.

2. **`stock_available = True`**:
   - A boolean variable storing whether the stock is available or not.

3. **`print()`**:
   - Displays both the price and the boolean value with appropriate labels.

---

### Example Output:
```
Price: $ 29.99
Stock Available: True
```

## Third Question

**Prompt :-** create a variable that stores no. of books and the book name in string output in single line combining the integer and string in python


**Answer :-**
To store the number of books as an integer and the book name as a string, and combine both in a single line of output, you can use the following Python code:

```python
# Declare variables
number_of_books = 5  # Integer variable to store the number of books
book_name = "The Great Gatsby"  # String variable to store the book name

# Combine and print the integer and string in a single line
print(f"We have {number_of_books} copies of \"{book_name}\" available.")
```

---

### Explanation:

1. **`number_of_books = 5`**:
   - Integer variable storing the number of books.

2. **`book_name = "The Great Gatsby"`**:
   - String variable storing the name of the book.

3. **`f"We have {number_of_books} copies of \"{book_name}\" available."`**:
   - This is an **f-string** (formatted string) used to dynamically combine variables into a single string for output.

---

### Example Output:
```
We have 5 copies of "The Great Gatsby" available.
```


## Fourth Question

**Prompt :-** create three variables that store number of rooms, area of the house , and is for sale print the output  and give me code in python

**Answer :-**
Here’s the complete Python code to create the three variables as requested and print their values:

```python
# Creating the variables
number_of_rooms = 4  # Number of rooms in the house (integer)
house_area = 150.0    # Area of the house in square meters (float)
is_for_sale = True    # Boolean to check if the house is for sale

# Printing the variables
print("Number of rooms:", number_of_rooms)
print("Area of the house (in m²):", house_area)
print("Is the house for sale?", is_for_sale)
```

### Example Output:
When you run the script, you should see:

```
Number of rooms: 4
Area of the house (in m²): 150.0
Is the house for sale? True
```

This demonstrates combining different data types (`integer`, `float`, and `boolean`) and printing their values.


## Q2. Operations

## First Question

**Prompt :-** create two numbers, a = 15 and b = 5. Perform and give results of addition, subtraction, multiplication, and division using these two numbers in in basic athematic operation in python

**Answer :-** Here’s the complete Python code to perform addition, subtraction, multiplication, and division with the given numbers:

```python
# Define the numbers
a = 15
b = 5

# Perform basic arithmetic operations
addition = a + b
subtraction = a - b
multiplication = a * b
division = a / b

# Print the results
print("Addition (a + b):", addition)
print("Subtraction (a - b):", subtraction)
print("Multiplication (a * b):", multiplication)
print("Division (a / b):", division)
```

### Explanation:
1. **Addition**: Adds `a` and `b`.
2. **Subtraction**: Subtracts `b` from `a`.
3. **Multiplication**: Multiplies `a` by `b`.
4. **Division**: Divides `a` by `b`.

### Example Output:
When you run the script, the expected results will be:

```
Addition (a + b): 20
Subtraction (a - b): 10
Multiplication (a * b): 75
Division (a / b): 3.0
```


## Second Question

**Prompt :-** create two numbers 10 and 20 and compare the two number is less than, greater then, equal in python

**Answer :-**
Here’s the Python code to compare the two numbers (`10` and `20`) and check if one is less than, greater than, or equal to the other:

```python
# Define the two numbers
num1 = 10
num2 = 20

# Compare the two numbers
if num1 < num2:
    print(f"{num1} is less than {num2}")
elif num1 > num2:
    print(f"{num1} is greater than {num2}")
else:
    print(f"{num1} is equal to {num2}")
```

### Explanation:
- **`num1 < num2`**: Checks if `num1` is less than `num2`.
- **`num1 > num2`**: Checks if `num1` is greater than `num2`.
- **`else`**: Handles the case where the two numbers are equal.

### Example Output:
When you run the script, the expected output is:

```
10 is less than 20
```

## Third Question

**Prompt :-** give two booleans is_sunny=True and is_weekend=False use logical operators to check if it is synny weekend or either of or not print  the result in python

**Answer :-**
Here’s the Python code to use logical operators (`and`, `or`, `not`) with the two boolean variables `is_sunny` and `is_weekend` and print the results:

```python
# Define the boolean variables
is_sunny = True
is_weekend = False

# Logical checks using AND, OR, and NOT
sunny_weekend = is_sunny and is_weekend  # Check if it's both sunny and a weekend
sunny_or_weekend = is_sunny or is_weekend  # Check if it's either sunny or a weekend
not_sunny = not is_sunny  # Check if it is NOT sunny

# Print the results
print("Is it both sunny AND a weekend?", sunny_weekend)
print("Is it either sunny OR a weekend?", sunny_or_weekend)
print("Is it NOT sunny?", not_sunny)
```

---

### Explanation:

1. **`is_sunny and is_weekend`**:
   - This checks if **both** conditions are true. (`is_sunny = True` and `is_weekend = False`)
   
2. **`is_sunny or is_weekend`**:
   - This checks if **either condition is true** (or both are true).
   
3. **`not is_sunny`**:
   - Negates the `is_sunny` boolean. If `is_sunny = True`, `not is_sunny` will return `False`.

---

### Example Output:

Given:

```python
is_sunny = True
is_weekend = False
```

When you run the script, you will get:

```
Is it both sunny AND a weekend? False
Is it either sunny OR a weekend? True
Is it NOT sunny? False
```


## Fourth Question

**Prompt :-** create p=50 and q=3 give the reulut for modulo operator in python


**Answer :-** The **modulo operator** in Python is represented by the symbol `%`. It returns the remainder of the division of one number by another.

Here’s the Python code to compute the modulo operation with `p = 50` and `q = 3`:

```python
# Define the numbers
p = 50
q = 3

# Perform the modulo operation
result = p % q

# Print the result
print("The result of 50 % 3 is:", result)
```

---

### Explanation:

- **`p % q`**: This computes the remainder when `p` is divided by `q`.
  - Example: \( 50 \div 3 = 16 \) remainder \( 2 \).
  
---

### Example Output:

When you run the script, the expected output will be:

```
The result of 50 % 3 is: 2
```

## Q3. **Conditional Statements**

## First Question

**Prompt :-**  create temperature = 35. check if the temperature is above 30 and prints It's a hot day otherwise print It's not that hot in python

**Answer :-**
Here’s the Python code to check if the temperature is above 30 and print the corresponding message:

```python
# Define the temperature
temperature = 35

# Check if the temperature is above 30
if temperature > 30:
    print("It's a hot day")
else:
    print("It's not that hot")
```

---

### Explanation:
1. **`if temperature > 30:`**: Checks if the temperature is greater than 30.
2. **`print("It's a hot day")`**: Executes if the condition is `True`.
3. **`else:`**: Executes if the condition is `False`.
4. **`print("It's not that hot")`**: Executes if the temperature is 30 or below.

---

### Example Output:

Given:

```python
temperature = 35
```

When you run the script, the expected output will be:

```
It's a hot day
```

## Second Question

**Prompt :-**  create age = 18 check if the person is old enough to vote Print Eligible to vote if the condition is met, otherwise print Not eligible to vote in python

**Answer :-** Here’s the Python code to check if the person is old enough to vote:

```python
# Define the age
age = 18

# Check if the person is old enough to vote
if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
```

---

### Explanation:
1. **`if age >= 18:`**: Checks if the age is 18 or older.
2. **`print("Eligible to vote")`**: Prints this if the condition is `True`.
3. **`else:`**: Executes if the condition is `False`.
4. **`print("Not eligible to vote")`**: Prints this if the condition is not met.

---

### Example Output:

Given:

```python
age = 18
```

When you run the script, the expected output will be:

```
Eligible to vote
```

## Third Question

**Prompt :-**  give score=70 check score greate than 50 pass otherwise fail in python

**Answer :-** Here’s the Python code to check if a score is greater than 50 to determine if the person has passed or failed:

```python
# Define the score
score = 70

# Check if the score is greater than 50
if score > 50:
    print("Pass")
else:
    print("Fail")
```

---

### Explanation:
1. **`if score > 50:`**: Checks if the score is greater than 50.
2. **`print("Pass")`**: Executes if the condition is `True`.
3. **`else:`**: Executes if the condition is `False`.
4. **`print("Fail")`**: Executes if the score is 50 or below.

---

### Example Output:

Given:

```python
score = 70
```

When you run the script, the expected output will be:

```
Pass
```


## Q4. **Loops**
## First Question

**Prompt :-** n = 5 print number up to n in python

**Answer :-** Here’s the Python code to print numbers up to `n = 5`:

```python
# Define n
n = 5

# Print numbers from 1 up to n
for i in range(1, n + 1):
    print(i)
```

---

### Explanation:
1. **`range(1, n + 1)`**: Generates numbers from `1` to `n` (inclusive).
2. **`for i in range(1, n + 1):`**: Loops over each number in the range.
3. **`print(i)`**: Prints each number during the loop.

---

### Example Output:

When `n = 5`, the expected output will be:

```
1
2
3
4
5
```

## Second Question

**Prompt :-** count = 3 print hello three times using while loop in pyhton

**Answer :-** Here’s the Python code to print `"Hello"` three times using a `while` loop:

```python
# Define the count
count = 3

# Initialize a counter
i = 0

# Use a while loop to print "Hello" three times
while i < count:
    print("Hello")
    i += 1
```

---

### Explanation:
1. **`while i < count:`**: The loop will continue as long as `i` is less than `count`.
2. **`print("Hello")`**: Prints the message on each iteration.
3. **`i += 1`**: Increments the counter `i` by 1 on each iteration to ensure the loop will terminate after three iterations.

---

### Example Output:

When you run the script, the expected output will be:

```
Hello
Hello
Hello
```

## Third Question

**Prompt :-** n = 4 print all the even numbers in python

**Answer :-** Here’s the Python code to print all even numbers up to `n = 4`:

```python
# Define n
n = 4

# Print all even numbers from 1 to n
for i in range(2, n + 1, 2):  # Start at 2, go up to n, increment by 2
    print(i)
```

---

### Explanation:
1. **`range(2, n + 1, 2)`**:
   - **Start at 2**: The first even number.
   - **End at `n + 1`**: Ensures we go up to the number `n`.
   - **Increment by 2**: Only selects even numbers.
2. **`for i in range(2, n + 1, 2):`**: Loops over all even numbers up to `n`.

---

### Example Output:

When `n = 4`, the expected output will be:

```
2
4
```

## Q3. ** Nested Loops**
## First Question

**Prompt :-** rows = 3 and cols = 4 print * for the rectangle in python

**Answer :-** Here’s the Python code to print a rectangle of asterisks (`*`) with `rows = 3` and `cols = 4`:

```python
# Define the number of rows and columns
rows = 3
cols = 4

# Loop through the rows
for i in range(rows):
    # Print '*' for the number of columns in each row
    print('*' * cols)
```

---

### Explanation:
1. **`for i in range(rows):`**: Loops over each row.
2. **`print('*' * cols)`**:
   - Repeats the `*` character `cols` times to form the columns in that row.
   - This creates the horizontal pattern for each row.

---

### Example Output:

When `rows = 3` and `cols = 4`, the expected output will be:

```
****
****
****
```

## Second Question

**Prompt :-** given n=3 print the numbers from 1 to n in each row in python 

**Answer :-** Here’s the Python code to print numbers from `1` to `n` in each row with `n = 3`:

```python
# Define n
n = 3

# Loop to print numbers from 1 to n in each row
for i in range(n):
    for j in range(1, n + 1):  # Inner loop to print numbers from 1 to n
        print(j, end=' ')
    print()  # Move to the next line after printing the row
```

---

### Explanation:
1. **Outer Loop (`for i in range(n):`)**:
   - Loops over the rows.
2. **Inner Loop (`for j in range(1, n + 1):`)**:
   - Prints numbers from `1` to `n` in the current row.
   - **`end=' '`**: Prevents a new line after each number, ensuring they are printed on the same line.
3. **`print()`**:
   - After the inner loop finishes printing numbers for a row, this moves to the next row.

---

### Example Output:

When `n = 3`, the expected output will be:

```
1 2 3 
1 2 3 
1 2 3 
```

## Third Question

**Prompt :-** n=3 print a triangle with * in python

**Answer :-** Here’s the Python code to print a **right-angled triangle** made of `*` symbols with `n = 3`:

```python
# Define the number of rows
n = 3

# Loop through each row
for i in range(1, n + 1):  # Loop from 1 to n
    print('* ' * i)  # Print '*' for each column in the row
```

---

### Explanation:
1. **`for i in range(1, n + 1):`**:
   - Loops from 1 through `n`. Each iteration represents a new row.
2. **`print('* ' * i)`**:
   - Prints `i` asterisks (`*`) for each row, forming the triangle shape.
   - The multiplication `* i` repeats the asterisk `i` times on the current row.

---

### Example Output:

When `n = 3`, the expected output will be:

```
* 
* * 
* * * 
```


## Q3. **Arrays**
## First Question

**Prompt :-** create an array of fruits and display first and last fruit in pyhton

**Answer :-** Here’s how you can create an array (list) of fruits in Python and display the first and last fruit:

```python
# Create an array (list) of fruits
fruits = ["Apple", "Banana", "Cherry", "Mango", "Grapes"]

# Display the first and last fruit
print("First fruit:", fruits[0])  # Index 0 for the first element
print("Last fruit:", fruits[-1])  # Index -1 for the last element
```

---

### Explanation:
1. **`fruits[0]`**:
   - Accesses the first element in the list.
2. **`fruits[-1]`**:
   - Accesses the last element in the list.

---

### Example Output:

When you run the script, the expected output will be:

```
First fruit: Apple
Last fruit: Grapes
```


## Second Question

**Prompt :-** create an array of number and print the sum of array in python

**Answer :-** Here’s how you can create an array (list) of numbers in Python and calculate their sum:

```python
# Create an array (list) of numbers
numbers = [1, 2, 3, 4, 5]

# Calculate the sum of the array
total_sum = sum(numbers)

# Print the result
print("The sum of the array is:", total_sum)
```

---

### Explanation:

1. **`numbers = [1, 2, 3, 4, 5]`**:
   - Creates a list of numbers.
2. **`sum(numbers)`**:
   - Built-in Python function that calculates the sum of all the elements in the list.
3. **`print()`**:
   - Displays the calculated sum.

---

### Example Output:

When you run the script, the expected output will be:

```
The sum of the array is: 15
```

## Third Question

**Prompt :-** create an array of four colors and print all the colors in a new line in python

**Answer :-** Here’s how you can create an array (list) of four colors and print each color on a new line:

```python
# Create an array of colors
colors = ["Red", "Blue", "Green", "Yellow"]

# Print each color on a new line
for color in colors:
    print(color)
```

---

### Explanation:
1. **`colors = ["Red", "Blue", "Green", "Yellow"]`**:
   - This is the given array containing four colors.
   
2. **`for color in colors:`**:
   - Loop through each item in the `colors` array.
   
3. **`print(color)`**:
   - Prints the current color on a new line during each iteration.

---

### Example Output:

When you run the script, the expected output will be:

```
Red
Blue
Green
Yellow
```