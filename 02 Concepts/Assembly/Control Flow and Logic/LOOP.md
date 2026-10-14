# LOOP

## What is it?

> [!abstract] Quick meaning
> An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **LOOP**, update this same page instead of making a duplicate.

## Connected Concepts

- [[ECX]]
- [[Conditional Jumps]]

## Chapter Sections That Use This

- [[Chapter 3 - Assembly Language Fundamentals#Array of 16-Bit Words|Chapter 3 — Array of 16-Bit Words]] (book page 28)
- [[Chapter 3 - Assembly Language Fundamentals#3.5.2 Calculating the Sizes of Arrays and Strings|Chapter 3 — 3.5.2 Calculating the Sizes of Arrays and Strings]] (book page 38)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#Word and Doubleword Arrays|Chapter 4 — Word and Doubleword Arrays]] (book page 11)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.4.2 Arrays|Chapter 4 — 4.4.2 Arrays]] (book page 32)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.5 JMP and LOOP Instructions|Chapter 4 — 4.5 JMP and LOOP Instructions]] (book page 37)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#Creating a Loop|Chapter 4 — Creating a Loop]] (book page 38)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.5.2 LOOP Instruction|Chapter 4 — 4.5.2 LOOP Instruction]] (book page 39)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#Nested Loops|Chapter 4 — Nested Loops]] (book page 40)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.5.3 Displaying an Array in the Visual Studio|Chapter 4 — 4.5.3 Displaying an Array in the Visual Studio]] (book page 40)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#to display an array.|Chapter 4 — to display an array.]] (book page 41)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.5.4 Summing an Integer Array|Chapter 4 — 4.5.4 Summing an Integer Array]] (book page 41)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.6.2 64-Bit Version of SumArray|Chapter 4 — 4.6.2 64-Bit Version of SumArray]] (book page 44)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#Loops|Chapter 4 — Loops]] (book page 48)
- [[Chapter 5 - Procedures#Testing the ArraySum Procedure|Chapter 5 — Testing the ArraySum Procedure]] (book page 14)
- [[Chapter 8 - Advanced Procedures#Passing Arrays|Chapter 8 — Passing Arrays]] (book page 5)
- [[Chapter 8 - Advanced Procedures#ArrayFill Example|Chapter 8 — ArrayFill Example]] (book page 13)
- [[Chapter 8 - Advanced Procedures#ArraySum Example|Chapter 8 — ArraySum Example]] (book page 35)
- [[Chapter 8 - Advanced Procedures#8.5.4 Example: ArraySum Program|Chapter 8 — 8.5.4 Example: ArraySum Program]] (book page 43)
- [[Chapter 8 - Advanced Procedures#ArraySum|Chapter 8 — ArraySum]] (book page 45)
- [[Chapter 8 - Advanced Procedures#The _arraysum Module|Chapter 8 — The _arraysum Module]] (book page 49)
- [[Chapter 6 - Conditional Processing#Loop until Key Pressed|Chapter 6 — Loop until Key Pressed]] (book page 24)
- [[Chapter 6 - Conditional Processing#6.3 Conditional Loop Instructions|Chapter 6 — 6.3 Conditional Loop Instructions]] (book page 27)
- [[Chapter 6 - Conditional Processing#LOOPZ and LOOPE Instructions|Chapter 6 — LOOPZ and LOOPE Instructions]] (book page 28)
- [[Chapter 6 - Conditional Processing#6.3.2 LOOPNZ and LOOPNE Instructions|Chapter 6 — 6.3.2 LOOPNZ and LOOPNE Instructions]] (book page 28)
- [[Chapter 6 - Conditional Processing#6.4.3 WHILE Loops|Chapter 6 — 6.4.3 WHILE Loops]] (book page 35)
- [[Chapter 6 - Conditional Processing#IF Statement Nested in a Loop|Chapter 6 — IF Statement Nested in a Loop]] (book page 36)
- [[Chapter 6 - Conditional Processing#6.6.4 Creating Loops with .REPEAT and .WHILE|Chapter 6 — 6.6.4 Creating Loops with .REPEAT and .WHILE]] (book page 52)
- [[Chapter 6 - Conditional Processing#Loop Containing an IF Statement|Chapter 6 — Loop Containing an IF Statement]] (book page 53)

## Cross-Language Examples


### C++
```cpp
for (int i = 0; i < 10; ++i) { }
```

### Python
```python
for i in range(10):
    pass
```

### Go
```go
for i := 0; i < 10; i++ { }
```

### Java
```java
for (int i = 0; i < 10; i++) { }
```

### PostgreSQL
SQL is normally set-oriented:
```sql
SELECT * FROM generate_series(0, 9);
```


## Database Connections

- No direct database connection added yet.

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **LOOP** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
