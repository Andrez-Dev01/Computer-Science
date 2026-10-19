# EXAMPLE — Registers (Assembly)

**Class:** Assembly Language
**Book / lecture / source:** Demonstration note written for this vault; not a quoted textbook section.

---

## Topic: CPU Registers

### 1. What is it?
A register is a small storage location inside a CPU. Instructions can operate on the values in registers.

### 2. Words I need to know
- **Register:** Fast storage inside the processor.
- **EAX:** One of the x86 32-bit general-purpose registers.

### 3. How does it work / how do I use it?
- `mov` copies a value into a register.
- `add` adds its second operand to its first operand and stores the result in the first.
- These are x86 assembly instructions; the code depends on the assembler and execution environment.

### 4. Example from the book or lecture
```asm
mov eax, 10
mov ebx, 5
add eax, ebx    ; EAX becomes 15
```
**What happens?** First EAX is set to 10, then EBX to 5, then EBX is added to EAX.
**Source:** This example is original, for demonstration only.

### 5. My example / experiment
**What I tried in my code editor:** Change EBX to 9, run the program, and observe EAX.

**What happened when I ran it:** (fill in when you test it)

**Practice file or repository:** (your actual MASM file)

### 6. Mistakes and fixes
- **Error:** Expecting `add eax, ebx` to change EBX.
  **Why:** EAX is the destination operand.
  **Fix:** Trace the destination and source operands separately.

### 7. Practice / check my understanding
- [ ] Explain why EAX becomes 15.
- [ ] Make a program that adds three numbers.
- [ ] Test one incorrect assumption and document the fix.

**What I want to remember:** Assembly instructions directly name the registers holding their operands.
