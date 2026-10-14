# Signed Integers

## What is it?

> [!abstract] Quick meaning
> Integer representations that can store positive and negative values.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Signed Integers**, update this same page instead of making a duplicate.

## Connected Concepts

- [[Unsigned Integers]]
- [[Two's Complement]]
- [[Sign Extension]]
- [[SAR]]
- [[IMUL]]
- [[IDIV]]

## Chapter Sections That Use This

- [[Chapter 1 - Basic Concepts#1.3 Data Representation|Chapter 1 — 1.3 Data Representation]] (book page 13)
- [[Chapter 1 - Basic Concepts#Unsigned Binary Integers|Chapter 1 — Unsigned Binary Integers]] (book page 15)
- [[Chapter 1 - Basic Concepts#Converting Between Unsigned Binary and Decimal|Chapter 1 — Converting Between Unsigned Binary and Decimal]] (book page 16)
- [[Chapter 1 - Basic Concepts#Translating Unsigned Decimal Integers to Binary|Chapter 1 — Translating Unsigned Decimal Integers to Binary]] (book page 17)
- [[Chapter 1 - Basic Concepts#Converting Between Unsigned Hexadecimal and Decimal|Chapter 1 — Converting Between Unsigned Hexadecimal and Decimal]] (book page 21)
- [[Chapter 1 - Basic Concepts#Converting Unsigned Decimal to Hexadecimal|Chapter 1 — Converting Unsigned Decimal to Hexadecimal]] (book page 23)
- [[Chapter 1 - Basic Concepts#1.3.6 Signed Binary Integers|Chapter 1 — 1.3.6 Signed Binary Integers]] (book page 24)
- [[Chapter 1 - Basic Concepts#Two’s-Complement Representation|Chapter 1 — Two’s-Complement Representation]] (book page 24)
- [[Chapter 1 - Basic Concepts#Hexadecimal Two’s Complement|Chapter 1 — Hexadecimal Two’s Complement]] (book page 25)
- [[Chapter 1 - Basic Concepts#Converting Signed Binary to Decimal|Chapter 1 — Converting Signed Binary to Decimal]] (book page 25)
- [[Chapter 1 - Basic Concepts#Converting Signed Decimal to Binary|Chapter 1 — Converting Signed Decimal to Binary]] (book page 26)
- [[Chapter 1 - Basic Concepts#Converting Signed Decimal to Hexadecimal|Chapter 1 — Converting Signed Decimal to Hexadecimal]] (book page 26)
- [[Chapter 1 - Basic Concepts#Converting Signed Hexadecimal to Decimal|Chapter 1 — Converting Signed Hexadecimal to Decimal]] (book page 26)
- [[Chapter 1 - Basic Concepts#Maximum and Minimum Values|Chapter 1 — Maximum and Minimum Values]] (book page 27)
- [[Chapter 1 - Basic Concepts#Terminology for Numeric Data Representation|Chapter 1 — Terminology for Numeric Data Representation]] (book page 32)
- [[Chapter 7 - Integer Arithmetic#Signed Division|Chapter 7 — Signed Division]] (book page 7)
- [[Chapter 7 - Integer Arithmetic#7.3.1 Unsigned Integer Multiplication (MUL)|Chapter 7 — 7.3.1 Unsigned Integer Multiplication (MUL)]] (book page 18)
- [[Chapter 7 - Integer Arithmetic#7.3.2 Signed Integer Multiplication (IMUL)|Chapter 7 — 7.3.2 Signed Integer Multiplication (IMUL)]] (book page 20)
- [[Chapter 7 - Integer Arithmetic#Using IMUL in 64-Bit Mode|Chapter 7 — Using IMUL in 64-Bit Mode]] (book page 23)
- [[Chapter 7 - Integer Arithmetic#IMUL Examples|Chapter 7 — IMUL Examples]] (book page 24)
- [[Chapter 7 - Integer Arithmetic#Comparing MUL and IMUL to Bit Shifting|Chapter 7 — Comparing MUL and IMUL to Bit Shifting]] (book page 25)
- [[Chapter 7 - Integer Arithmetic#7.3.4 Unsigned Integer Division (DIV)|Chapter 7 — 7.3.4 Unsigned Integer Division (DIV)]] (book page 26)
- [[Chapter 7 - Integer Arithmetic#7.3.5 Signed Integer Division (IDIV)|Chapter 7 — 7.3.5 Signed Integer Division (IDIV)]] (book page 28)
- [[Chapter 7 - Integer Arithmetic#The IDIV Instruction|Chapter 7 — The IDIV Instruction]] (book page 29)

## Cross-Language Examples


### C++
```cpp
#include <cstdint>
std::int32_t x = -5;
```

### Python
```python
x = -5   # Python integers are not limited to 32 bits
```

### Go
```go
var x int32 = -5
```

### Java
```java
int x = -5;
```

### PostgreSQL
```sql
SELECT -5::INTEGER;
```


## Database Connections

- [[SQL Integer Types]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Signed Integers** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
