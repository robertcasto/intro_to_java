
# Introduction to Java 
This interactive Introduction to Java course, based on Java LTS, is tailored specifically for beginners with no previous programming experience, targeting those pursuing software or data engineering careers. This course introduces fundamental concepts, ranging from writing code comments and executing arithmetic operations to exploring Java's primitive and non-primitive data types. Learners will learn to manage information by declaring variables and employing a variety of data structures. They will understand comparison operators and use them interactively to execute code based on certain conditions. The course concludes with an exploration of for and while loops as well as switch statements.

## Chapter 1: Introduction to Java
Learn why so many things are created using Java and why so many choose it. No prior knowledge is required.
### Lesson 1.1: History, Differences, Why Choose?
* Learner will be able to summarize the history of Java
* Learner will be able to identify how Java is different from other programming languages
* Learner will be able to explain the benefits of using Java
* Concepts: 
1. What is Java?
2. A history of Java
3. The benefits and uses of Java
6. Where did Java come from?
7. Differences from other programming and scripting languages
8. Where is Java used?
### Lesson 1.2: More Than a Programming Language
* Learner will be able to describe the organization of a Java file
* Learner will be able to explain the Java platform and how it runs their code
* Learner will be able to discover more information about Java versions and their features
1. Java is a platform
2. Platform agnostic
3. Platform independence: features of java
    1. Simple, Object-Oriented, Portable, Platform independent, Secured, Robust, Architecture neutral, Interpreted, High Performance, Multithreaded, Distributed, Dynamic
4. The TLA's of Java. JVM, JDK, JRE, LTS (long term support), JIT, (just in time), ...
5. Not a scripting language. Pros & Cons
6. Anatomy of a .java file
7. Classes - Have to start somewhere
8. Methods - Where the code lives in a class
9. Where to find information about different versions of Java
10. Why choose one version over another?
11. Other implementations of Java besides Oracle. Amazon, GraalVM, etc.
### Lesson 1.3: Writing and Running Java
* Learner will be able to prepare their Java development environment
* Learner will be able to create their first Java program
* Learner will be able to explain how a Java program is run
1. Every file is a class, sometimes more than one
2. We will be using a simple text editor and command line for this course.
3. Where to begin: main()
4. Writing your first program - Hello World!
    1. java output : System.out.println("Hello World!");
5. Setting up your development environment
6. Compiling your program
7. Running your program
8. How is a java program run?
   1. Class file, Classloader, Bytecode Verifier, Interpreter, Runtime, Hardware

## Chapter 2: Fundamental Concepts
The basic building blocks of the language and how they fit together.
### Lesson 2.1: Data Types - Primitive
* The learner will be able to list the basic data types and their value limits 
* The learner will be able to convert values between different data types
* The learner will be able to construct mathematical expressions
1. strongly typed language
2. primitive data types: bool, int, float, double, long, char, short, byte
    1. show how to create literals of each
    2. sizes and values of data types: limits, signed, unsigned

### Lesson 2.2: Variables - MAYBE DO THIS ONE?
* The learner will be able to create variables and assign values and expressions to them
* The learner will be able to decide on useful variable names
* The learner will be able to convert variables of one type to another
* The learner will be able to demonstrate the use of variables
1. declaring variables
2. how variables are named: camel case, snake case, _prefix, etc.
3. introducing nothing: null
4. the importance of naming: keywords, reserved, documentation
5. employing a variety of data structures
6. converting types: type casting
   1. automatic: widening (byte -> short -> char -> int -> long -> float -> double)
   2. manual: narrowing (double -> float -> long -> int -> char -> short -> byte)
7. Show how variables are used later in a program

### Lesson 2.3: Operators
* The learner will be able to identify the different types of operators available
* The learner will be able to compare two different values
* The learner will be able to construct mathematical and logic expressions
* The learner will be able to evaluate the order of operations in an expression
2. assignment operator: =
3. arithmetic operators: +, -, *, /, %, also these followed by =
4. operator precedence
5. unary operators: +, -, ++, --, !
6. equality & conditional operators: ==, !=, >, >= , <, <=
7. conditional operators: &&, ||, ternary (?:)
8. type comparison: instanceof, useful for non-primitive types
9. bitwise operators: ~, &, |, ^, <<, >>, >>>

### Lesson 2.4: Data Types - Non-Primitive
* The learner will be able to create variables that can hold many values
* The learner will be able to develop custom data structures
* The learner will be able to describe how Strings are created and how they work
* The learner will be able to explain the difference between a class, interface, and enum
1. arrays
   1. initializing arrays
   2. changing array values
   3. array length
   4. initial value of array values
   5. multi-dimensional arrays
2. class
3. interface
4. String
5. enum


## Chapter 3: Control and Flow
Comparing values and making decisions.
### Lesson 3.1: From Expressions to Statements
* Learner will be able to create statements using comparisons and expressions
* Learner will be able to distinguish between different types of statements
* Learner will be able to appraise whether an expression is ambiguous or not 
1. creating statements from expressions
2. What is a statement?
   1. How is it made?
   2. Types: assignment, increment, decrement, method invocation, object creation, declaration
3. compound expressions: ambiguous and unambiguous
### Lesson 3.2: Blocks and Scope
* Learner will be able to construct a block of statements
* Learner will be able to explain what variable scope is
* Learner will be able to identify the scope of a variable with nested blocks
4. Creating a block using {..}
5. Scope of variables
6. Nested blocks and affect on scope
### Lesson 3.3: Conditional Statements
* Learner will be able to construct a conditional statement
* Learner will be able to decide on the type of flow that should be used
* Learner will be able to assess when there are too many conditional statements
* Learner will be able to rearrange a set of comparisons to simplify how they are evaluated
1. if statement
2. if..else statement
3. Conditional branching
4. Too many conditions, introducing the switch statement
5. Fancy switch statements
6. Constructing workflows based on conditions
7. code blocks: {} syntax, intro to
### Lesson 3.4: Comments
* Learner will be able to create the 3 types of comments that are available
* Learner will be able to decide on which type of comment should be used
* Learner will be able to assess whether a comment is needed or not
* Learner will be able to describe how documentation is created from doc comments
1. // comment style
2. /* */ style
3. /** */ style
4. Which style should be used?
5. Is a comment really needed? Maybe a change to the code will eliminate need for comment?



## Chapter 4: Loops
### Lesson 4.1: `for` loop
* Learner will be able to construct the 3-statement version of a `for` loop
* Learner will be able to construct the `for..each` loop
* Learner will be able to explain the statements needed for both styles of `for` loops
* Learner will be able to construct a loop that uses each value in an array
1. for statement
2. structure of a for loop: 3 statements
3. for each loop
4. looping through an array
### Lesson 4.2: `while` and `do...while` loops
* Learner will be able to construct either a `while` or `do..while` loop construct
* Learner will be able to evaluate whether their loop will run forever
* Learner will be able to organize loops inside of other loops
1. while loop syntax
2. do..while statement
3. Avoiding infinite loops
4. Loops inside loops
### Lesson 4.4: Jump statements: `break` and `continue`
* Learner will be able to construct a jump statement in a loop
* Learner will be able to evaluate when to use a jump statement
* Learner will be able to decide between the `break` and `continue` jump statements
* Learner will be able to evaluate how long a loop will run
1. Why get out of a loop early?
2. break
3. labeled break
4. continue 
6. Estimating how long loops will run
