In Java, data types are used to define the type of data that a variable can hold. Here are some common data types in Java, along with examples:

## 1. **Primitive Data Types:**
   - **int:** Used to store integer values.
     ```java
     int age = 25;
     ```

   - **double:** Used to store floating-point numbers.
     ```java
     double price = 19.99;
     ```

   - **char:** Used to store a single character.
     ```java
     char grade = 'A';
     ```

   - **boolean:** Used to store true or false values.
     ```java
     boolean isJavaFun = true;
     ```

   - **byte:** Used to store small integer values.
     ```java
     byte smallNumber = 120;
     ```

   - **short:** Used to store short integer values.
     ```java
     short population = 5000;
     ```

   - **long:** Used to store large integer values.
     ```java
     long bigNumber = 1234567890L; // Note the 'L' suffix for long literals
     ```

   - **float:** Used to store floating-point numbers (less commonly used than double).
     ```java
     float height = 5.8f; // Note the 'f' suffix for float literals
     ```

## 2. **Reference Data Types:**
   - **String:** Used to store a sequence of characters.
     ```java
     String greeting = "Hello, Java!";
     ```

   - **[[Arrays]]**: Used to store a collection of elements of the same type.
     ```java
     int[] numbers = {1, 2, 3, 4, 5};
     ```

   - **Object:** Instances of classes are reference types.
     ```java
     // Assuming there's a class called Person
     Person person = new Person("John", 25);
     ```

   - **Wrapper Classes:** These are classes that encapsulate primitive data types.
     ```java
     Integer num = 10; // Wrapper class for int
     Character letter = 'C'; // Wrapper class for char
     ```

These examples demonstrate the basic usage of different data types in Java. It's important to choose the appropriate data type based on the kind of data you want to store, as it affects the memory usage and behavior of your program.