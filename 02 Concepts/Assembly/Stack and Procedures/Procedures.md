# Procedures

## What is it?

> [!abstract] Quick meaning
> Named blocks of code that perform a task and can be called from elsewhere.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Procedures**, update this same page instead of making a duplicate.

## Connected Concepts

- [[CALL]]
- [[RET]]
- [[Procedure Parameters]]
- [[Stack Frame]]

## Chapter Sections That Use This

- [[Chapter 5 - Procedures#5.2 Defining and Using Procedures|Chapter 5 — 5.2 Defining and Using Procedures]] (book page 8)
- [[Chapter 5 - Procedures#Defining a Procedure|Chapter 5 — Defining a Procedure]] (book page 9)
- [[Chapter 5 - Procedures#Labels in Procedures|Chapter 5 — Labels in Procedures]] (book page 9)
- [[Chapter 5 - Procedures#Example: SumOf Three Integers|Chapter 5 — Example: SumOf Three Integers]] (book page 10)
- [[Chapter 5 - Procedures#Documenting Procedures|Chapter 5 — Documenting Procedures]] (book page 10)

## Cross-Language Examples


### MASM
```asm
MyProc PROC
    ; work
    ret
MyProc ENDP
```

### C++
```cpp
int add(int a, int b) { return a + b; }
```

### Python
```python
def add(a, b):
    return a + b
```

### Go
```go
func add(a, b int) int { return a + b }
```

### Java
```java
static int add(int a, int b) { return a + b; }
```

### PostgreSQL
```sql
CREATE FUNCTION add_two(a int, b int)
RETURNS int
LANGUAGE sql
AS $$ SELECT a + b $$;
```


## Database Connections

- [[SQL Functions and Procedures]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Procedures** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
