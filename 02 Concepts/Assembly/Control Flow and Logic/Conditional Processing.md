# Conditional Processing

## What is it?

> [!abstract] Quick meaning
> Choosing different instruction paths using comparisons, flags, and jump conditions.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Conditional Processing**, update this same page instead of making a duplicate.

## Connected Concepts

- [[CMP]]
- [[TEST]]
- [[Conditional Jumps]]
- [[CPU Status Flags]]

## Chapter Sections That Use This

- [[Chapter 8 - Advanced Procedures#Comparison Instructions|Chapter 8 — Comparison Instructions]] (book page 60)
- [[Chapter 8 - Advanced Procedures#Branching Instructions|Chapter 8 — Branching Instructions]] (book page 61)
- [[Chapter 6 - Conditional Processing#6.4 Conditional Structures|Chapter 6 — 6.4 Conditional Structures]] (book page 29)
- [[Chapter 6 - Conditional Processing#Block-Structured IF Statements|Chapter 6 — Block-Structured IF Statements]] (book page 30)
- [[Chapter 6 - Conditional Processing#Logical AND Operator|Chapter 6 — Logical AND Operator]] (book page 34)
- [[Chapter 6 - Conditional Processing#Short-Circuit Evaluation|Chapter 6 — Short-Circuit Evaluation]] (book page 34)
- [[Chapter 6 - Conditional Processing#6.4.3 WHILE Loops|Chapter 6 — 6.4.3 WHILE Loops]] (book page 35)
- [[Chapter 6 - Conditional Processing#IF Statement Nested in a Loop|Chapter 6 — IF Statement Nested in a Loop]] (book page 36)
- [[Chapter 6 - Conditional Processing#6.4.4 Table-Driven Selection|Chapter 6 — 6.4.4 Table-Driven Selection]] (book page 38)
- [[Chapter 6 - Conditional Processing#6.5 Application: Finite-State Machines|Chapter 6 — 6.5 Application: Finite-State Machines]] (book page 39)
- [[Chapter 6 - Conditional Processing#6.5.1 Validating an Input String|Chapter 6 — 6.5.1 Validating an Input String]] (book page 40)
- [[Chapter 6 - Conditional Processing#6.5.2 Validating a Signed Integer|Chapter 6 — 6.5.2 Validating a Signed Integer]] (book page 41)
- [[Chapter 6 - Conditional Processing#Complete Finite-State Machine Program|Chapter 6 — Complete Finite-State Machine Program]] (book page 42)
- [[Chapter 6 - Conditional Processing#6.6 Conditional Control Flow Directives (Optional Topic)|Chapter 6 — 6.6 Conditional Control Flow Directives (Optional Topic)]] (book page 44)
- [[Chapter 6 - Conditional Processing#6.6.1 Creating IF Statements|Chapter 6 — 6.6.1 Creating IF Statements]] (book page 46)
- [[Chapter 6 - Conditional Processing#6.6.3 Compound Expressions|Chapter 6 — 6.6.3 Compound Expressions]] (book page 49)
- [[Chapter 6 - Conditional Processing#6.6.4 Creating Loops with .REPEAT and .WHILE|Chapter 6 — 6.6.4 Creating Loops with .REPEAT and .WHILE]] (book page 52)

## Cross-Language Examples


### C++
```cpp
if (x > 10) { /* ... */ }
```

### Python
```python
if x > 10:
    pass
```

### Go
```go
if x > 10 {
}
```

### Java
```java
if (x > 10) { }
```

### PostgreSQL
```sql
SELECT CASE WHEN x > 10 THEN 'large' ELSE 'small' END
FROM demo;
```


## Database Connections

- [[SQL Boolean Logic]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Conditional Processing** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
