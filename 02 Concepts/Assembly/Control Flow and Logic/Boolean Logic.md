# Boolean Logic

## What is it?

> [!abstract] Quick meaning
> Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Boolean Logic**, update this same page instead of making a duplicate.

## Connected Concepts

- [[AND]]
- [[OR]]
- [[XOR]]
- [[NOT]]
- [[Binary Numbers]]
- [[ALU]]

## Chapter Sections That Use This

- [[Chapter 1 - Basic Concepts#1.4 Boolean Expressions|Chapter 1 — 1.4 Boolean Expressions]] (book page 35)
- [[Chapter 1 - Basic Concepts#NOT|Chapter 1 — NOT]] (book page 35)
- [[Chapter 1 - Basic Concepts#AND|Chapter 1 — AND]] (book page 36)
- [[Chapter 1 - Basic Concepts#OR|Chapter 1 — OR]] (book page 37)
- [[Chapter 1 - Basic Concepts#1.4.1 Truth Tables for Boolean Functions|Chapter 1 — 1.4.1 Truth Tables for Boolean Functions]] (book page 38)
- [[Chapter 3 - Assembly Language Fundamentals#DUP Operator|Chapter 3 — DUP Operator]] (book page 27)
- [[Chapter 3 - Assembly Language Fundamentals#Using the DUP Operator|Chapter 3 — Using the DUP Operator]] (book page 38)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.1 OFFSET Operator|Chapter 4 — 4.3.1 OFFSET Operator]] (book page 24)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.3 PTR Operator|Chapter 4 — 4.3.3 PTR Operator]] (book page 26)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.4 TYPE Operator|Chapter 4 — 4.3.4 TYPE Operator]] (book page 28)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.5 LENGTHOF Operator|Chapter 4 — 4.3.5 LENGTHOF Operator]] (book page 28)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.3.6 SIZEOF Operator|Chapter 4 — 4.3.6 SIZEOF Operator]] (book page 29)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#TYPEDEF Operator|Chapter 4 — TYPEDEF Operator]] (book page 36)
- [[Chapter 5 - Procedures#USES Operator|Chapter 5 — USES Operator]] (book page 15)
- [[Chapter 5 - Procedures#GetTextColor|Chapter 5 — GetTextColor]] (book page 27)
- [[Chapter 5 - Procedures#SetTextColor|Chapter 5 — SetTextColor]] (book page 36)
- [[Chapter 8 - Advanced Procedures#8.4.2 ADDR Operator|Chapter 8 — 8.4.2 ADDR Operator]] (book page 26)
- [[Chapter 8 - Advanced Procedures#8.6.1 Stack Affected by the USES Operator|Chapter 8 — 8.6.1 Stack Affected by the USES Operator]] (book page 52)
- [[Chapter 6 - Conditional Processing#6.1 Boolean and Comparison Instructions|Chapter 6 — 6.1 Boolean and Comparison Instructions]] (book page 1)
- [[Chapter 6 - Conditional Processing#6.1.5 XOR Instruction|Chapter 6 — 6.1.5 XOR Instruction]] (book page 8)
- [[Chapter 6 - Conditional Processing#6.1.10 Boolean Instructions in 64-Bit Mode|Chapter 6 — 6.1.10 Boolean Instructions in 64-Bit Mode]] (book page 15)
- [[Chapter 6 - Conditional Processing#Logical AND Operator|Chapter 6 — Logical AND Operator]] (book page 34)

## Cross-Language Examples


### C++
```cpp
bool allowed = loggedIn && !blocked;
```

### Python
```python
allowed = logged_in and not blocked
```

### Go
```go
allowed := loggedIn && !blocked
```

### Java
```java
boolean allowed = loggedIn && !blocked;
```

### PostgreSQL
```sql
SELECT TRUE AND NOT FALSE;
```


## Database Connections

- [[SQL Boolean Logic]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Boolean Logic** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
