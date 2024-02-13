
# Introduction to Java 
This interactive Introduction to Java course, based on Java LTS, is tailored specifically for beginners with no previous programming experience, targeting those pursuing software or data engineering careers. This course introduces fundamental concepts, ranging from writing code comments and executing arithmetic operations to exploring Java's primitive and non-primitive data types. Learners will learn to manage information by declaring variables and employing a variety of data structures. They will understand comparison operators and use them interactively to execute code based on certain conditions. The course concludes with an exploration of for and while loops as well as switch statements.

## Chapter 1: Introduction to Java
### Lesson 1.1: History, Benefits, and Differences
* Learner will be able to explain the history of Java and its benefits
* Learner will be able to compare Java with other programming languages
* Learner will be able to identify the many uses of Java in the world today 
1. What is Java?
2. A history of Java
3. The benefits and uses of Java
4. Java is a platform
5. Platform agnostic
6. Where did Java come from?
7. Differences from other programming and scripting language
8. Where is Java used?
### Lesson 1.2: Features of Java
* Learner will be able to describe the benefits offered by Java
* Learner will be able to describe the Java platform and how it runs their code
* Learner will be able to recognize how Java is organized and structured
* Learner will be able to learn about different versions of Java and their features
1. Platform independence: features of java
    1. Simple, Object-Oriented, Portable, Platform independent, Secured, Robust, Architecture neutral, Interpreted, High Performance, Multithreaded, Distributed, Dynamic
2. The TLA's of Java. JVM, JDK, JRE, LTS (long term support), ...
3. Not a scripting language. Pros & Cons
4. Anatomy of a .java file
5. Classes - Have to start somewhere
6. Methods - Where the code lives in a class
### Lesson 1.3:
* Learner will be able to setup their Java development environment
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
8. how is a java program run?
   1. Class file, Classloader, Bytecode Verifier, Interpreter, Runtime, Hardware


## Chapter 2: Fundamental Concepts

### Lesson 2.1: Data Types - Primitive
1. strongly typed language
2. primitive data types: bool, int, float, double, long, char, short, byte
    1. show how to create literals of each
    2. sizes and values of data types: limits, signed, unsigned
    3. converting types: type casting
        1. automatic: widening (byte -> short -> char -> int -> long -> float -> double)
        2. manual: narrowing (double -> float -> long -> int -> char -> short -> byte)

### Lesson 2.2: Data Types - Non-Primitive
1. arrays
   1. initializing arrays
   2. changing array values
   3. array length
   4. initial value of array values
   5. multi-dimensional arrays
2. class
3. interface
4. String
5. Enum

### Lesson 2.2: Operators
1. writing code comments: 3 types: single line, multiline, and documentation comments
2. assignment operator: =
3. arithmetic operators: +, -, *, /, %, also these followed by =
4. operator precedence
5. unary operators: +, -, ++, --, !
6. equality & conditional operators: ==, !=, >, >= , <, <=
7. conditional operators: &&, ||, ternary (?:)
8. type comparison: instanceof, useful for non-primitive types
9. bitwise operators: ~, &, |, ^, <<, >>, >>>

### Lesson 2.3: MAYBE THIS ONE SINCE IT WOULDN'T NEEDS LOTS OF GRAPHICS?
1. declaring variables
2. how variables are named: camel case, snake case, _prefix, etc.
3. introducing nothing: null
4. the importance of naming: keywords, reserved, documentation
5. employing a variety of data structures
6. casting a variable to another type


## Chapter 3: Conditions and comparisons
### Lesson 3.1: Operators and data types
1. expressions and statements
2. What is a condition?
3. What is a statement?
### Lesson 3.2:
1. assignment, ++ or --
2. What is an expression?
3. compound expressions: ambiguous and unambiguous
### Lesson 3.3:
1. if statement
2. if..else statement
3. Conditional branching
4. Too many conditions, introducing the switch statement
5. Fancy switch statements
6. Constructing workflows based on conditions
7. code blocks: {} syntax, intro to



## Chapter 4: Loops
### Lesson 4.1: `for` loop
1. for statement
2. structure of a for loop: 3 statements
3. for each loop
4. looping through an array
### Lesson 4.2: `while` loop
1. while loop syntax
2. do..while statement
3. Avoiding infinite loops
4. Loops inside loops
### Lesson 4.4: `break` and `continue` 
1. Why get out of a loop early?
2. break
3. labeled break
4. continue 
6. Estimating how long loops will run
