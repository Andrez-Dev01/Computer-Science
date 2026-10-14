# Passing by Reference

## What is it?

> [!abstract] Quick meaning
> Passing an address so a procedure can access or modify the caller's original object.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Passing by Reference**, update this same page instead of making a duplicate.

## Connected Concepts

- [[Procedure Parameters]]
- [[Pointers]]
- [[ADDR]]
- [[Arrays]]

## Chapter Sections That Use This

- [[Chapter 2 - x86 Processor Architecture#Real-Address Mode|Chapter 2 — Real-Address Mode]] (book page 9)
- [[Chapter 2 - x86 Processor Architecture#Address Space|Chapter 2 — Address Space]] (book page 9)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.4 Indirect Addressing|Chapter 4 — 4.4 Indirect Addressing]] (book page 31)
- [[Chapter 8 - Advanced Procedures#Passing by Reference|Chapter 8 — Passing by Reference]] (book page 5)
- [[Chapter 8 - Advanced Procedures#Passing Arrays|Chapter 8 — Passing Arrays]] (book page 5)
- [[Chapter 8 - Advanced Procedures#8.2.6 Reference Parameters|Chapter 8 — 8.2.6 Reference Parameters]] (book page 13)
- [[Chapter 8 - Advanced Procedures#8.4 INVOKE, ADDR, PROC, and PROTO|Chapter 8 — 8.4 INVOKE, ADDR, PROC, and PROTO]] (book page 24)
- [[Chapter 8 - Advanced Procedures#8.4.2 ADDR Operator|Chapter 8 — 8.4.2 ADDR Operator]] (book page 26)
- [[Chapter 8 - Advanced Procedures#8.4.6 Example: Exchanging Two Integers|Chapter 8 — 8.4.6 Example: Exchanging Two Integers]] (book page 36)

## Cross-Language Examples


### C++
```cpp
void f(int& x) { x++; }
```

### Go
```go
func f(x *int) { (*x)++ }
```

### Python
Normal Python has no C++-style reference parameter; mutable objects can still be changed through a shared object reference.

### Java
Java has no C++-style reference parameters.

### PostgreSQL
Database functions normally exchange values, rows, or database state rather than raw memory references.


## Database Connections

- No direct database connection added yet.

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Passing by Reference** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
