# ☕ Core Java

This module covers the fundamental building blocks of Java programming and establishes the foundation for advanced Java engineering.

The goal is not only to learn Java syntax, but to understand how Java behaves at runtime and how core concepts are applied in real-world software development.

> **Understand → Implement → Test → Analyze → Apply**

---

## 🎯 Learning Objectives

By completing this module, you should be able to:

- Understand Java syntax and program structure
- Understand the JDK, JRE, and JVM
- Work confidently with primitive and reference types
- Understand Java memory basics
- Use control-flow statements effectively
- Design and use methods
- Work with arrays and strings
- Understand object creation and references
- Understand `==` vs `equals()`
- Understand `equals()` and `hashCode()`
- Understand immutability
- Write clean and maintainable Java code
- Apply core Java concepts to real-world problems

---

## 📚 Topics Covered

### 1. Java Fundamentals

- Java program structure
- JDK
- JRE
- JVM
- Compilation and execution
- `main()` method
- Variables
- Constants
- Comments
- Naming conventions
- Java source code lifecycle

### 2. Data Types

- Primitive data types
- Reference types
- `byte`
- `short`
- `int`
- `long`
- `float`
- `double`
- `char`
- `boolean`
- Type casting
- Widening conversion
- Narrowing conversion
- Autoboxing
- Unboxing
- Wrapper classes

### 3. Operators

- Arithmetic operators
- Relational operators
- Logical operators
- Assignment operators
- Unary operators
- Ternary operator
- Bitwise operators
- Shift operators
- Operator precedence

### 4. Control Flow

- `if`
- `if-else`
- Nested conditions
- `switch`
- Switch expressions
- `for`
- Enhanced `for`
- `while`
- `do-while`
- `break`
- `continue`
- Conditional expressions

### 5. Methods

- Method declaration
- Parameters
- Return values
- Method invocation
- Method overloading
- Pass-by-value
- Varargs
- Recursion
- Static methods
- Instance methods
- Method design principles

### 6. Arrays

- One-dimensional arrays
- Multi-dimensional arrays
- Array declaration
- Array initialization
- Array traversal
- Array copying
- Array comparison
- `Arrays` utility class
- Common array problems
- Time and space complexity of array operations

### 7. Strings

- String creation
- String literals
- String pool
- String immutability
- String concatenation
- `String`
- `StringBuilder`
- `StringBuffer`
- String comparison
- Common string operations
- String performance considerations

### 8. Object Fundamentals

- Classes
- Objects
- Object references
- Constructors
- Default constructors
- Parameterized constructors
- `this`
- `static`
- `final`
- Object lifecycle basics
- Instance variables
- Static variables
- Instance methods
- Static methods

### 9. Object Methods

Important methods and concepts:

- `equals()`
- `hashCode()`
- `toString()`
- `==`
- Object identity
- Object equality
- Equality contract
- `equals()` and `hashCode()` relationship

### 10. Immutability

- What is immutability?
- Why immutability matters
- Immutable objects
- Designing immutable classes
- Final fields
- Defensive copying
- Benefits of immutable objects
- Immutability and thread safety
- Real-world immutable classes

### 11. Date and Time API

Modern Java date and time concepts:

- `LocalDate`
- `LocalTime`
- `LocalDateTime`
- `Instant`
- `ZonedDateTime`
- `Duration`
- `Period`
- Date formatting
- Date parsing
- Time zones
- UTC concepts

### 12. Modern Java Features

This section will cover modern Java language features such as:

- Records
- Sealed classes
- Pattern matching
- Switch expressions
- Text blocks
- Local variable type inference
- Modern collection APIs
- Other useful modern Java features

---

## 🧪 Practical Exercises

This module will include practical coding problems such as:

### Strings

- Reverse a string
- Check whether a string is a palindrome
- Count character frequency
- Find duplicate characters
- Find the first non-repeated character
- Remove duplicate characters
- Check whether two strings are anagrams

### Arrays

- Find the maximum element
- Find the minimum element
- Find the second-largest element
- Reverse an array
- Remove duplicates
- Find missing numbers
- Find duplicate numbers
- Sort an array
- Merge two arrays
- Find common elements

### Objects

- Create immutable classes
- Implement `equals()` and `hashCode()`
- Override `toString()`
- Compare objects correctly
- Design classes following clean-code principles

---

## 🏗️ Engineering Examples

The examples in this module will go beyond basic syntax.

They will demonstrate:

- Immutability
- Defensive copying
- Proper object equality
- Clean method design
- Input validation
- Meaningful naming
- Separation of responsibilities
- Avoiding unnecessary complexity
- Exception-safe code
- Maintainable code structure
- Performance considerations

---

## 🧠 Interview Concepts

Important Java interview concepts will be documented with explanations and practical examples.

Examples include:

### Java Fundamentals

- Why is Java platform independent?
- What is the difference between JDK, JRE, and JVM?
- How does Java code execute?
- What happens when Java code is compiled?
- What is bytecode?

### Data Types

- Primitive vs reference types
- What is autoboxing?
- What is unboxing?
- What is type casting?
- Widening vs narrowing conversion

### Strings

- Why is String immutable?
- What is the String pool?
- String vs StringBuilder vs StringBuffer
- How does string concatenation work?

### Objects

- `==` vs `equals()`
- Why should `hashCode()` be overridden when `equals()` is overridden?
- What is object identity?
- What is object equality?
- What happens when an object is created?

### Methods

- Is Java pass-by-value or pass-by-reference?
- Method overloading vs method overriding
- Static vs instance methods
- What is recursion?

### Memory

- Stack vs heap
- What is a reference variable?
- Where are objects stored?
- What is garbage collection?

---

## 🔬 Experiments & Analysis

Where useful, this module will contain small experiments to understand Java behavior.

Examples:

- String pool behavior
- Object identity
- `==` vs `equals()`
- Integer caching
- Mutable vs immutable objects
- Pass-by-value behavior
- Array performance
- String concatenation performance
- Object creation
- Stack and heap concepts

The purpose is to **observe Java behavior through code rather than relying only on theory**.

---

## 📂 Planned Structure

```text
01-core-java/
│
├── README.md
│
├── 01-java-fundamentals/
│   ├── README.md
│   └── src/
│
├── 02-data-types/
│   ├── README.md
│   └── src/
│
├── 03-operators/
│   ├── README.md
│   └── src/
│
├── 04-control-flow/
│   ├── README.md
│   └── src/
│
├── 05-methods/
│   ├── README.md
│   └── src/
│
├── 06-arrays/
│   ├── README.md
│   └── src/
│
├── 07-strings/
│   ├── README.md
│   └── src/
│
├── 08-object-fundamentals/
│   ├── README.md
│   └── src/
│
├── 09-object-methods/
│   ├── README.md
│   └── src/
│
├── 10-immutability/
│   ├── README.md
│   └── src/
│
├── 11-date-time/
│   ├── README.md
│   └── src/
│
└── 12-modern-java/
    ├── README.md
    └── src/
```

---

## 🛠️ Technology

This module uses:

- Java
- Maven
- JUnit 5
- Git
- GitHub

---

## 🧪 Testing Strategy

Practical examples will gradually include tests using:

- JUnit 5
- Assertions
- Parameterized tests
- Boundary testing
- Edge-case testing

Example:

```text
Input
   ↓
Application Logic
   ↓
Expected Result
   ↓
JUnit Test
   ↓
Pass / Fail
```

---

## 📈 Code Quality Principles

The code in this module aims to follow:

- Meaningful naming
- Small and focused methods
- Clear responsibilities
- Avoiding unnecessary duplication
- Appropriate comments
- Clean formatting
- Simple solutions before complex solutions
- Testable code
- Maintainable code

---

## 🎓 Training Perspective

This module is also designed from a technical-training perspective.

The learning approach is:

```text
Concept
   ↓
Explanation
   ↓
Simple Example
   ↓
Hands-on Exercise
   ↓
Real-world Example
   ↓
Testing
   ↓
Code Review
   ↓
Interview Discussion
```

The objective is to connect **learning with practical engineering**.

---

## 🚧 Current Status

**In Progress**

This module is being developed progressively.

New examples, exercises, tests, experiments, and engineering notes will be added over time.

---

## 🚀 Future Improvements

Planned additions include:

- Advanced Java memory experiments
- JVM demonstrations
- More performance experiments
- Advanced object design
- Modern Java examples
- Real-world coding problems
- Interview-focused exercises
- Benchmarking examples
- Additional automated tests

---

## 👨‍💻 Author

**Abhishek Jha**

Lead Technical Trainer with 8+ years of experience in technical training, mentoring, Java, React, Spring Boot, and full-stack engineering.

Current areas of focus include:

- Java Engineering
- Spring Boot
- React
- Full-Stack Development
- Software Architecture
- System Design
- Python
- Generative AI
- LLM Applications
- RAG
- AI Engineering

---

## 📫 Connect

- GitHub: [@abhishek-jha-tech](https://github.com/abhishek-jha-tech)
- LinkedIn: Add your LinkedIn profile URL here

---

> **Don't just learn Java syntax. Understand how Java works.**
