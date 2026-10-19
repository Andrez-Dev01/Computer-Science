---
type: college-section-example
subject: Computer Architecture & Assembly
course: Sample
aliases:
  - Registers example
---
# EXAMPLE — Assembly Registers (Section Note)

> [!important] Demonstration, not a textbook transcription
> This is an **original** sample of the format. The numbering and content are not presented as a section from your actual book. Replace with your textbook's real headings when studying.

**Goal:** Understand how x86 registers participate in arithmetic operations.

## Topic 1 — General-Purpose Registers

### What it is — in my own words
Registers are tiny, fast storage locations used directly by processor instructions. In 32-bit x86 code, `EAX` and `EBX` are general-purpose registers.

### Key vocabulary and facts
- **Register:** CPU storage named by the instruction set.
- **Operand:** Value or location an instruction reads or writes.
- **Destination operand:** The operand that receives a result for many two-operand arithmetic instructions.

### Syntax / steps / different methods
`mov destination, source` copies a value. `add destination, source` adds the source to the destination and stores the result in the destination.

### Source example — explained
**Source:** Original illustrative code; test in your course's MASM environment.

```asm
mov eax, 10      ; EAX = 10
mov ebx, 20      ; EBX = 20
add eax, ebx     ; EAX = 30, EBX stays 20
```

**Walkthrough:** The third instruction adds 20 to 10. The result is stored in `EAX`, not automatically in a high-level language variable.

### Mistakes, edge cases, and fixes
| Problem | Why | Fix |
| --- | --- | --- |
| Assuming `EBX` holds 30 after `add eax, ebx` | The destination is `EAX` | Check operand order and inspect registers |
| Confusing a 32-bit register with a memory address | Registers and memory locations are different kinds of storage | Identify what each operand refers to |

### My test and independent experiment
- **Change I tried:** Try `sub eax, ebx` after setting both registers, then inspect the result.
- **Prediction:** [Fill in before running]
- **Actual result:** [Fill in after running]
- **Tested personally?** Not yet — this is a template demonstration.
- **Working program:** [Record a public-safe program location after you run it]

### Where I can apply it
Implement and trace a two-number arithmetic routine. Later compare how compiler-generated assembly uses registers, without requiring a separate concept-note copy.

### Check my understanding
- [ ] Can I identify the destination operand?
- [ ] Can I write a small MASM program and explain every instruction?

## Section wrap-up
**Main takeaway:** Operand order matters for these instructions.

**Manual practice:** Write an example using `mov`, `add`, and `sub` without looking at these notes; then test it.
