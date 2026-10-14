# Python Assembly Connections

Python hides most CPU details, so use this page to connect **concepts**, not to assume a Python line maps directly to one x86 instruction.

## Functions
- Python function → conceptually [[Procedures]]
- function call → lower execution layers eventually need call/return behavior
- recursion → [[Recursion]]

## Decisions
- `if` / `elif` / `else` → [[Conditional Processing]]
- comparisons → conceptually connect to [[CMP]]
- Boolean logic → [[Boolean Logic]]

## Data
Python integers are higher-level objects, not simply one x86 register integer.

Useful machine-level ideas:
- [[Binary Numbers]]
- [[Signed Integers]]
- [[Bit Shifting]]
- [[AND]]
- [[OR]]
- [[XOR]]
