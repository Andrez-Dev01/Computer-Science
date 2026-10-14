# Character Representation

## What is it?

> [!abstract] Quick meaning
> The idea that characters are stored as numeric codes in memory.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Character Representation**, update this same page instead of making a duplicate.

## Connected Concepts

- [[ASCII]]
- [[Bits and Bytes]]

## Chapter Sections That Use This

- [[Chapter 1 - Basic Concepts#1.3 Data Representation|Chapter 1 — 1.3 Data Representation]] (book page 13)
- [[Chapter 1 - Basic Concepts#1.3.8 Character Storage|Chapter 1 — 1.3.8 Character Storage]] (book page 29)
- [[Chapter 1 - Basic Concepts#ANSI Character Set|Chapter 1 — ANSI Character Set]] (book page 29)
- [[Chapter 1 - Basic Concepts#Unicode Standard|Chapter 1 — Unicode Standard]] (book page 30)
- [[Chapter 1 - Basic Concepts#ASCII Strings|Chapter 1 — ASCII Strings]] (book page 30)
- [[Chapter 1 - Basic Concepts#Using the ASCII Table|Chapter 1 — Using the ASCII Table]] (book page 31)
- [[Chapter 1 - Basic Concepts#ASCII Control Characters|Chapter 1 — ASCII Control Characters]] (book page 31)
- [[Chapter 1 - Basic Concepts#Terminology for Numeric Data Representation|Chapter 1 — Terminology for Numeric Data Representation]] (book page 32)
- [[Chapter 3 - Assembly Language Fundamentals#3.1.6 String Literals|Chapter 3 — 3.1.6 String Literals]] (book page 6)
- [[Chapter 3 - Assembly Language Fundamentals#Defining Strings|Chapter 3 — Defining Strings]] (book page 27)
- [[Chapter 4 - Data Transfers Addressing and Arithmetic#4.5.5 Copying a String|Chapter 4 — 4.5.5 Copying a String]] (book page 42)
- [[Chapter 7 - Integer Arithmetic#7.5 ASCII and Unpacked Decimal Arithmetic|Chapter 7 — 7.5 ASCII and Unpacked Decimal Arithmetic]] (book page 38)
- [[Chapter 7 - Integer Arithmetic#ASCII Decimal and Unpacked Decimal|Chapter 7 — ASCII Decimal and Unpacked Decimal]] (book page 39)
- [[Chapter 6 - Conditional Processing#Character String Example|Chapter 6 — Character String Example]] (book page 40)

## Cross-Language Examples


### C++
```cpp
char c = 'A';
int code = static_cast<unsigned char>(c);
```

### Python
```python
code = ord('A')
```

### Go
```go
code := rune('A')
```

### Java
```java
char c = 'A';
int code = c;
```

### PostgreSQL
```sql
SELECT ascii('A');
```


## Database Connections

- [[SQL Text and Encoding]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Character Representation** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
