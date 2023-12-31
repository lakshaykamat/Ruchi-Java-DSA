## JAVA
Java is a **programming language** and a **platform**. Java is a high level, robust, object-oriented and secure programming language.

Java was developed by _Sun Microsystems_ (which is now the subsidiary of Oracle) in the year 1995. _James Gosling_ is known as the father of Java. Before Java, its name was _Oak_. Since Oak was already a registered company, so James Gosling and his team changed the name from Oak to Java.

## Compile time

![[Pasted image 20231230123506.png]]
At compile time, the Java file is compiled by Java Compiler (It does not interact with OS) and converts the Java code into bytecode.

## Runtime 

![[Pasted image 20231230123442.png|200]]

## JDK
■ Provide Environment to develop and run the java program. It is a package that includes:-
1. Development tools :- To provide an environment to run your program.
2. **JRE** :- To Execute your program.
3. **A compiler** :- javac
4. **Archiver** :- Jar
5. **Docs generator** :- Javadoc
6. Interpreter/loader
## JRE
■ It is an installation package that provides environment to only run the program.
It consist of:-
1. Deployment technology
2. User interface toolkit
3. Integration libraries
4. Base libraries
5. **JVM** :- Java virtual Machine
## JVM Execution
■ **Interpreter**
→ Line by line execution
→ When one method is called many times it will interpret again and
again
■ **JIT**
Those methods that are repeated, JIT provides direct machine code so that interpretation is not required.
→ Makes execution Faster.
→ Garbage collector
