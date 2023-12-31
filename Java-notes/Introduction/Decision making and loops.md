
## Decision making
### If-else statement

**Example:**
```java
int score = 85; 
if (score >= 90) {
System.out.println("Excellent!"); 
}
else if (score >= 80) { 
System.out.println("Very good!"); 
} 
else if (score >= 70) { 
System.out.println("Good."); 
} 
else {
System.out.println("Needs improvement.");
}
```

### Switch statement
**Example:**
```java
char grade = 'B';
switch (grade) { 
case 'A':
	System.out.println("Excellent!"); 
	break; 
case 'B':
	System.out.println("Very good!"); 
	break; 
case 'C':
	System.out.println("Good.");
	break;
default: 
	System.out.println("Needs improvement."); 
}
```
## Loops
### For loop

**Example:**
```java
for (int i = 0; i < 10; i++) { 
System.out.println(i); // Prints numbers from 0 to 9 
}
```

### While loop

**Example:**
```java
int count = 0; 
while (count < 5) { 
System.out.println("Count: " + count); 
count++; 
}
```

### Do-while loop

```java
int choice = 0; 
do { 
System.out.println("Enter a number (1 to 5):"); 
choice = scanner.nextInt(); 
} while (choice < 1 || choice > 5);
```