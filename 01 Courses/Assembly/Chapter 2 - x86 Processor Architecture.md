# Chapter 2 — x86 Processor Architecture

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]

---

## 2.1 General Concepts

> **Book page:** 1

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 2.1.1 Basic Microcomputer Design

> **Book page:** 2

**Study focus:** The processor that fetches, decodes, and executes machine instructions.

**Concepts to connect:**
- [[CPU#^what-is-it|CPU]]
- [[ALU#^what-is-it|ALU]]
- [[Control Unit#^what-is-it|Control Unit]]
- [[Registers#^what-is-it|Registers]]

**My notes:**

- 

#### Clock

> **Book page:** 3

**Study focus:** The timing signal that synchronizes processor operations.

**Concepts to connect:**
- [[CPU Clock#^what-is-it|CPU Clock]]

**My notes:**

- 

### 2.1.2 Instruction Execution Cycle

> **Book page:** 4

**Study focus:** The repeated fetch, decode, and execute process.

**Concepts to connect:**
- [[Instruction Execution Cycle#^what-is-it|Instruction Execution Cycle]]
- [[Instruction Pointer#^what-is-it|Instruction Pointer]]

**My notes:**

- 

### 2.1.3 Reading from Memory

> **Book page:** 5

**Study focus:** Storage that holds program instructions and data while a program runs.

**Concepts to connect:**
- [[Memory#^what-is-it|Memory]]
- [[Cache#^what-is-it|Cache]]
- [[Address Bus#^what-is-it|Address Bus]]
- [[Data Bus#^what-is-it|Data Bus]]

**My notes:**

- 

### 2.1.4 Loading and Executing a Program

> **Book page:** 6

**Study focus:** The operating-system component that places an executable into memory and prepares it to run.

**Concepts to connect:**
- [[Program Loader#^what-is-it|Program Loader]]
- [[Process#^what-is-it|Process]]
- [[Operating System#^what-is-it|Operating System]]

**My notes:**

- 

## 2.2 32-Bit x86 Processors

> **Book page:** 7

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

### 2.2.1 Modes of Operation

> **Book page:** 7

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Protected Mode

> **Book page:** 8

**Study focus:** An x86 operating mode that supports memory protection, multitasking, and protected address spaces.

**Concepts to connect:**
- [[Protected Mode#^what-is-it|Protected Mode]]

**My notes:**

- 

#### Virtual-8086 Mode

> **Book page:** 8

**Study focus:** A protected-mode environment that emulates real-mode behavior for legacy 8086-style software.

**Concepts to connect:**
- [[Virtual-8086 Mode#^what-is-it|Virtual-8086 Mode]]

**My notes:**

- 

#### Real-Address Mode

> **Book page:** 9

**Study focus:** An x86 mode modeled after the original 8086 environment with direct, limited memory addressing and little protection.

**Concepts to connect:**
- [[Real-Address Mode#^what-is-it|Real-Address Mode]]
- [[ADDR#^what-is-it|ADDR]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### System Management Mode

> **Book page:** 9

**Study focus:** A special x86 mode used for low-level firmware and system-management tasks.

**Concepts to connect:**
- [[System Management Mode#^what-is-it|System Management Mode]]

**My notes:**

- 

#### Address Space

> **Book page:** 9

**Study focus:** Storage that holds program instructions and data while a program runs.

**Concepts to connect:**
- [[Memory#^what-is-it|Memory]]
- [[Memory Addressing#^what-is-it|Memory Addressing]]
- [[ADDR#^what-is-it|ADDR]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Basic Program Execution Registers

> **Book page:** 10

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[General Purpose Registers#^what-is-it|General Purpose Registers]]

**My notes:**

- 

#### General-Purpose Registers

> **Book page:** 10

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[General Purpose Registers#^what-is-it|General Purpose Registers]]

**My notes:**

- 

#### Specialized Uses

> **Book page:** 11

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[General Purpose Registers#^what-is-it|General Purpose Registers]]
- [[USES#^what-is-it|USES]]
- [[PUSH#^what-is-it|PUSH]]
- [[POP#^what-is-it|POP]]

**My notes:**

- 

#### Segment Registers

> **Book page:** 12

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[Program Segments#^what-is-it|Program Segments]]

**My notes:**

- 

#### Instruction Pointer

> **Book page:** 12

**Study focus:** The register identifying the next instruction to execute; EIP in 32-bit x86.

**Concepts to connect:**
- [[Instruction Pointer#^what-is-it|Instruction Pointer]]

**My notes:**

- 

#### EFLAGS Register

> **Book page:** 12

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**My notes:**

- 

#### Control Flags

> **Book page:** 13

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**My notes:**

- 

#### Status Flags

> **Book page:** 13

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**My notes:**

- 

#### MMX Registers

> **Book page:** 14

**Study focus:** Special processor registers used by multimedia, SIMD, and floating-point/vector instructions.

**Concepts to connect:**
- [[MMX and XMM Registers#^what-is-it|MMX and XMM Registers]]

**My notes:**

- 

#### XMM Registers

> **Book page:** 14

**Study focus:** Special processor registers used by multimedia, SIMD, and floating-point/vector instructions.

**Concepts to connect:**
- [[MMX and XMM Registers#^what-is-it|MMX and XMM Registers]]

**My notes:**

- 

#### Floating-Point Unit

> **Book page:** 15

**Study focus:** Processor hardware specialized for floating-point arithmetic.

**Concepts to connect:**
- [[Floating-Point Unit#^what-is-it|Floating-Point Unit]]

**My notes:**

- 

### 2.2.3 x86 Memory Management

> **Book page:** 15

**Study focus:** Storage that holds program instructions and data while a program runs.

**Concepts to connect:**
- [[Memory#^what-is-it|Memory]]
- [[Memory Addressing#^what-is-it|Memory Addressing]]

**My notes:**

- 

## 2.3 64-Bit x86-64 Processors

> **Book page:** 16

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

### 2.3.1 64-Bit Operation Modes

> **Book page:** 17

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

#### Compatibility Mode

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### 64-Bit Mode

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 2.3.2 Basic 64-Bit Execution Environment

> **Book page:** 18

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

#### General-Purpose Registers

> **Book page:** 18

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[General Purpose Registers#^what-is-it|General Purpose Registers]]

**My notes:**

- 

#### REX Is Enabled.

> **Book page:** 19

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 2.4 Components of a Typical x86 Computer

> **Book page:** 19

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 2.4.1 Motherboard

> **Book page:** 20

**Study focus:** The main circuit board connecting the CPU, memory, buses, controllers, and peripheral interfaces.

**Concepts to connect:**
- [[Motherboard#^what-is-it|Motherboard]]
- [[System Bus#^what-is-it|System Bus]]

**My notes:**

- 

#### PCI and PCI Express Bus Architectures

> **Book page:** 21

**Study focus:** The main circuit board connecting the CPU, memory, buses, controllers, and peripheral interfaces.

**Concepts to connect:**
- [[Motherboard#^what-is-it|Motherboard]]
- [[System Bus#^what-is-it|System Bus]]

**My notes:**

- 

#### Motherboard Chipset

> **Book page:** 21

**Study focus:** The main circuit board connecting the CPU, memory, buses, controllers, and peripheral interfaces.

**Concepts to connect:**
- [[Motherboard#^what-is-it|Motherboard]]
- [[System Bus#^what-is-it|System Bus]]

**My notes:**

- 

### 2.4.2 Memory

> **Book page:** 22

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 2.5 Input–Output System

> **Book page:** 23

**Study focus:** The layers and mechanisms a program uses to communicate with input/output devices.

**Concepts to connect:**
- [[I-O System#^what-is-it|I-O System]]
- [[Device Drivers#^what-is-it|Device Drivers]]
- [[Operating System#^what-is-it|Operating System]]

**My notes:**

- 

### 2.5.1 Levels of I/O Access

> **Book page:** 23

**Study focus:** The layers and mechanisms a program uses to communicate with input/output devices.

**Concepts to connect:**
- [[I-O System#^what-is-it|I-O System]]
- [[Device Drivers#^what-is-it|Device Drivers]]
- [[Operating System#^what-is-it|Operating System]]

**My notes:**

- 

#### Device Drivers

> **Book page:** 24

**Study focus:** The layers and mechanisms a program uses to communicate with input/output devices.

**Concepts to connect:**
- [[I-O System#^what-is-it|I-O System]]
- [[Device Drivers#^what-is-it|Device Drivers]]
- [[Operating System#^what-is-it|Operating System]]

**My notes:**

- 

#### Programming at Multiple Levels

> **Book page:** 24

**Study focus:** The layers and mechanisms a program uses to communicate with input/output devices.

**Concepts to connect:**
- [[I-O System#^what-is-it|I-O System]]
- [[Device Drivers#^what-is-it|Device Drivers]]
- [[Operating System#^what-is-it|Operating System]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

## 2.6 Chapter Summary

> **Book page:** 26

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 2.7 Key Terms

> **Book page:** 27

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

---

## End-of-Chapter Review

- [ ] I can explain the main ideas without copying the book.
- [ ] I followed every section in order.
- [ ] I updated concept pages instead of duplicating concepts.
- [ ] I added at least one example in my own words.
- [ ] I connected useful ideas to C++, Python, Go, Java/JVM, or PostgreSQL where it makes sense.
