# Local Variables

## What is it?

> [!abstract] Quick meaning
> Variables whose lifetime and visibility belong to a single procedure call, commonly stored in its stack frame.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Local Variables**, update this same page instead of making a duplicate.

## Connected Concepts

- [[Stack Frame]]
- [[LOCAL]]
- [[EBP]]

## Chapter Sections That Use This

- [[Chapter 8 - Advanced Procedures#8.2.5 Local Variables|Chapter 8 — 8.2.5 Local Variables]] (book page 11)
- [[Chapter 8 - Advanced Procedures#8.2.9 LOCAL Directive|Chapter 8 — 8.2.9 LOCAL Directive]] (book page 17)
- [[Chapter 8 - Advanced Procedures#8.6.4 Non-Doubleword Local Variables|Chapter 8 — 8.6.4 Non-Doubleword Local Variables]] (book page 56)

## Cross-Language Examples


### C++
```cpp
void f() { int x = 10; }
```

### Python
```python
def f():
    x = 10
```

### Go
```go
func f() { x := 10; _ = x }
```

### Java
```java
static void f() { int x = 10; }
```

### PostgreSQL / PLpgSQL
```sql
DO $$
DECLARE x integer := 10;
BEGIN
  RAISE NOTICE '%', x;
END $$;
```


## Database Connections

- [[SQL Functions and Procedures]]

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Local Variables** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
