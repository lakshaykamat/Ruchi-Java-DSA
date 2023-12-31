## Scanner class
- The Scanner class provides a way to read input from various sources, including the keyboard, files, and strings.
- It's part of the `java.util` package, so you need to import it before using it.

#### Steps to use it:

1. **Import the class:**

```java
import java.util.Scanner;
```

2. **Create a Scanner object:**

```java
Scanner scanner = new Scanner(System.in);  // Reads from keyboard input
```

3. **Read input using methods:**

- **next():** Reads a single word (until a space).
- **nextLine():** Reads an entire line (until Enter).
- **nextInt():** Reads an integer.
- **nextDouble():** Reads a double (floating-point number).
- **nextBoolean():** Reads a boolean value (true or false).

**Example:**
```java
System.out.print("Enter your name: ");
String name = scanner.nextLine();
System.out.print("Enter your age: ");
int age = scanner.nextInt();
System.out.println("Hello, " + name + "! You are " + age + " years old.");
```