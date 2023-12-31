## **What are arrays?**

- Arrays are collections of elements of the same data type, stored in contiguous memory locations.
- They allow you to group multiple values under a single variable name, making it easier to organize and access data.

**Syntax :**
```java
datatype[] arrayName = new datatype[size];
```
Or
```java
datatype[] arrayName = {value1, value2, value3, .....};
```

- Primitive (int, char, etc.) are stored in stack.
- All the other objects are stored in heap memory.
- In an array, since we can change the object, hence it is mutable.
### Accessing Java Array Elements 

#### 1. Arrays.toString() method

- This static method from the `java.util.Arrays` class converts an array into a string representation that includes the array's elements enclosed in square brackets and separated by commas.
```java
 int[] numbers = {1, 2, 3, 4, 5};
 System.out.println(Arrays.toString(numbers)); // output: [1, 2, 3, 4, 5]
```

#### 2. Looping 
```java
 // accessing the elements of the specified array  
 int[] numbers = {1, 2, 3, 4, 5};
 for (int i = 0; i < numbers.length; i++)  
 System.out.print(numbers[i] + " "); //output: 1 2 3 4 5
```

### Understanding the syntax

```java
Datatype[] variable_name = new datatype[size];
```
In this step, a new object is created in the heap memory during runtime. the new keyword is used to create a new object.
Example:
```java
int[] number = new int[6]
```

![[Pasted image 20231230183035.png]]

### Types of arrays
#### Single-Dimensional Arrays

- Store elements in a linear sequence, like a list.
- **Example:**

```java
int[] numbers = {10, 25, 17, 8};  // Array of integers
String[] names = {"Alice", "Bob", "Charlie"};  // Array of strings
```
#### Two-Dimensional Arrays

- Store elements in multiple dimensions, like a table or grid.
- **Example:**
```java
int[][] matrix = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};  // 2D array (3 rows, 4 columns)
```
