In Java, functions are referred to as methods. Here are some examples of defining and using methods in Java:

**Example:**
```java
public class MethodWithParametersExample { 
// A method that takes parameters and performs addition 
public static int add(int a, int b) {
	return a + b; 
}
public static void main(String[] args) { 
// Calling the method with arguments 
int result = add(5, 7);
	System.out.println("Sum: " + result); 
}
}
```