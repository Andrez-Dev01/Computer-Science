# Recursion

## What is it?

> [!abstract] Quick meaning
> A procedure or function calling itself, with each active call keeping its own return information and state.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Recursion**, update this same page instead of making a duplicate.

## Connected Concepts

- [[CALL]]
- [[Runtime Stack]]
- [[Stack Frame]]
- [[Local Variables]]

## Chapter Sections That Use This

- [[Chapter 8 - Advanced Procedures#8.3 Recursion|Chapter 8 — 8.3 Recursion]] (book page 20)
- [[Chapter 8 - Advanced Procedures#Endless Recursion|Chapter 8 — Endless Recursion]] (book page 20)
- [[Chapter 8 - Advanced Procedures#8.3.1 Recursively Calculating a Sum|Chapter 8 — 8.3.1 Recursively Calculating a Sum]] (book page 21)
- [[Chapter 8 - Advanced Procedures#8.3.2 Calculating a Factorial|Chapter 8 — 8.3.2 Calculating a Factorial]] (book page 22)

## Cross-Language Examples


### C++
```cpp
int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
```

### Python
```python
def fact(n):
    return 1 if n <= 1 else n * fact(n - 1)
```

### Go
```go
func fact(n int) int {
    if n <= 1 { return 1 }
    return n * fact(n-1)
}
```

### Java
```java
static int fact(int n) {
    return n <= 1 ? 1 : n * fact(n - 1);
}
```

### PostgreSQL
```sql
WITH RECURSIVE nums(n) AS (
  SELECT 1
  UNION ALL
  SELECT n + 1 FROM nums WHERE n < 5
)
SELECT * FROM nums;
```


## Database Connections

- [[SQL Recursive CTEs]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Recursion** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
