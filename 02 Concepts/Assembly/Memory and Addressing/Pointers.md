# Pointers

## What is it?

> [!abstract] Quick meaning
> Values that hold memory addresses.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Pointers**, update this same page instead of making a duplicate.

## Connected Concepts

- [[Indirect Addressing]]
- [[Passing by Reference]]
- [[Arrays]]

## Chapter Sections That Use This

- [[Chapter 1 - Basic Concepts#What Will I Learn?|Chapter 1 — What Will I Learn?]] (book page 4)
- [[Chapter 1 - Basic Concepts#Why Learn Assembly Language?|Chapter 1 — Why Learn Assembly Language?]] (book page 7)
- [[Chapter 1 - Basic Concepts#1.4 Boolean Expressions|Chapter 1 — 1.4 Boolean Expressions]] (book page 35)
- [[Chapter 1 - Basic Concepts#1.4.1 Truth Tables for Boolean Functions|Chapter 1 — 1.4.1 Truth Tables for Boolean Functions]] (book page 38)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.1.8 Direct-Offset Operands|Chapter 4 — 4.1.8 Direct-Offset Operands]] (book page 10)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.1 OFFSET Operator|Chapter 4 — 4.3.1 OFFSET Operator]] (book page 24)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#OFFSET Examples|Chapter 4 — OFFSET Examples]] (book page 24)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.4 Indirect Addressing|Chapter 4 — 4.4 Indirect Addressing]] (book page 31)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.4.4 Pointers|Chapter 4 — 4.4.4 Pointers]] (book page 35)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#TYPEDEF Operator|Chapter 4 — TYPEDEF Operator]] (book page 36)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#Example Program: Pointers|Chapter 4 — Example Program: Pointers]] (book page 37)
- [[Chapter 8 - Advanced Procedures#Passing by Reference|Chapter 8 — Passing by Reference]] (book page 5)
- [[Chapter 8 - Advanced Procedures#Base-Offset Addressing|Chapter 8 — Base-Offset Addressing]] (book page 7)
- [[Chapter 8 - Advanced Procedures#8.2.6 Reference Parameters|Chapter 8 — 8.2.6 Reference Parameters]] (book page 13)
- [[Chapter 8 - Advanced Procedures#8.2.7 LEA Instruction|Chapter 8 — 8.2.7 LEA Instruction]] (book page 14)
- [[Chapter 8 - Advanced Procedures#8.2.8 ENTER and LEAVE Instructions|Chapter 8 — 8.2.8 ENTER and LEAVE Instructions]] (book page 15)
- [[Chapter 8 - Advanced Procedures#LEAVE Instruction|Chapter 8 — LEAVE Instruction]] (book page 16)
- [[Chapter 8 - Advanced Procedures#Argument Size Mismatch|Chapter 8 — Argument Size Mismatch]] (book page 37)
- [[Chapter 8 - Advanced Procedures#Passing the Wrong Type of Pointer|Chapter 8 — Passing the Wrong Type of Pointer]] (book page 38)
- [[Chapter 8 - Advanced Procedures#Passing Immediate Values|Chapter 8 — Passing Immediate Values]] (book page 38)
- [[Chapter 6 - Conditional Processing#6.1 Boolean and Comparison Instructions|Chapter 6 — 6.1 Boolean and Comparison Instructions]] (book page 1)
- [[Chapter 6 - Conditional Processing#6.1.10 Boolean Instructions in 64-Bit Mode|Chapter 6 — 6.1.10 Boolean Instructions in 64-Bit Mode]] (book page 15)

## Cross-Language Examples


### C++
```cpp
int x = 10;
int* p = &x;
```

### Go
```go
x := 10
p := &x
```

### Python
Python hides raw memory pointers in normal code.

### Java
Java references objects but does not expose ordinary raw pointers.

### SQL
SQL does not expose CPU memory addresses.


## Database Connections

- No direct database connection added yet.

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Pointers** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
