# Passing by Value

## What is it?

> [!abstract] Quick meaning
> Passing a copy of an argument's value to a procedure.
^what-is-it

## Why it matters

This is reusable knowledge. When another chapter teaches you more about **Passing by Value**, update this same page instead of making a duplicate.

## Connected Concepts

- [[Procedure Parameters]]
- [[Passing by Reference]]
- [[Stack Frame]]

## Chapter Sections That Use This

- [[Chapter 8 - Advanced Procedures#Passing by Value|Chapter 8 — Passing by Value]] (book page 4)

## Cross-Language Examples


### C++
```cpp
void f(int x) { x++; }  // caller's int is unchanged
```

### Go
```go
func f(x int) { x++ }   // caller's int is unchanged
```

### Python
Python passes object references by assignment; this is not the same model as a C++ value parameter.

### Java
Java is pass-by-value, including when the value is an object reference.


## Database Connections

- No direct database connection added yet.

## My Own Example

_Write an example from class, homework, or a project._

## Self-Test

- Can I explain **Passing by Value** without looking?
- Can I show one example?
- Can I explain one connection to another concept?
