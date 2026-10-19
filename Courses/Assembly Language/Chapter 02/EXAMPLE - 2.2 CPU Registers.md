# 2.2 — CPU Registers (demonstration)

> [!abstract] Overview
> A register is a small storage location inside the CPU. Assembly instructions can name registers directly when moving or calculating with data.

> [!note] About this demo
> The numbers **2.2, 2.2.1, 2.2.2, and 2.2.3 are examples of formatting**, not verified section titles from your textbook. Create your real notes using your book's actual headings.

## 2.2.1 — What are CPU registers?

A CPU register holds a small amount of data close to the circuitry that executes instructions. Registers provide fast access to values used during operations.

> [!info] Vocabulary
> **Register** — A small storage location inside the processor.  
> **Operand** — A value or location that an instruction acts on.  
> **Destination** — The place where an instruction writes its result.

Unlike a high-level language's local variable, a named register in x86 assembly refers to a particular CPU register.

## 2.2.2 — General-purpose registers

In **32-bit x86** assembly, examples include:

| Register | Width | Example use |
| --- | --- | --- |
| `EAX` | 32 bits | Arithmetic and general-purpose data |
| `EBX` | 32 bits | General-purpose data |
| `ECX` | 32 bits | Counters and general-purpose data |
| `EDX` | 32 bits | General-purpose data |

> [!tip] A useful detail
> The low 16 bits of `EAX` can be accessed as `AX`; its low and high bytes of `AX` can be accessed as `AL` and `AH`.

## 2.2.3 — Moving and adding values

### Code example (MASM, 32-bit x86)

```asm
mov eax, 10     ; put 10 in EAX
mov ebx, 20     ; put 20 in EBX
add eax, ebx   ; EAX = EAX + EBX = 30
```

**What happens?** `MOV` copies the source value into the destination. `ADD` adds `EBX` to `EAX` and stores the result in **`EAX`**. The value in `EBX` remains 20.

> [!example] Predict the result
> If you change `mov ebx, 20` to `mov ebx, 7`, what should `EAX` contain after `add eax, ebx`? **17**.

> [!warning] Easy mistake
> `add eax, ebx` does **not** update both registers. The destination (`EAX`) changes; the source (`EBX`) does not.

### My experiment

Try the three instructions in a test MASM program using your configured toolchain. Change the starting values, predict the result, and inspect the registers using a debugger or your course's tools.

> [!tip] What I tested
> **Prediction:** `EAX` becomes 17 if `EBX` is set to 7.  
> **Observed result:** _Fill this in only after running the code._  
> **Program location:** _Optional local path to your `.asm` experiment._

**Source:** This example was written for the template demonstration. It is not copied from a textbook.
