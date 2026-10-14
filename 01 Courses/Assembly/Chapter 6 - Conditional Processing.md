# Chapter 6 — Conditional Processing

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]
- [[PostgreSQL and Low-Level Concepts]]

---

## 6.1 Boolean and Comparison Instructions

> **Book page:** 1

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[Instructions#^what-is-it|Instructions]]
- [[LEA#^what-is-it|LEA]]
- [[Pointers#^what-is-it|Pointers]]
- [[Java Bytecode#^what-is-it|Java Bytecode]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.1.1 The CPU Status Flags

> **Book page:** 2

**Study focus:** The processor that fetches, decodes, and executes machine instructions.

**Concepts to connect:**
- [[CPU#^what-is-it|CPU]]
- [[ALU#^what-is-it|ALU]]
- [[Control Unit#^what-is-it|Control Unit]]
- [[Registers#^what-is-it|Registers]]
- [[EFLAGS#^what-is-it|EFLAGS]]

**My notes:**

- 

#### AND Instruction

> **Book page:** 3

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Converting Characters to Upper Case

> **Book page:** 4

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.1.3 OR Instruction

> **Book page:** 5

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.1.4 Bit-Mapped Sets

> **Book page:** 6

**Study focus:** Representing set membership with bits.

**Concepts to connect:**
- [[Bit-Mapped Sets#^what-is-it|Bit-Mapped Sets]]
- [[Set Operations with Bits#^what-is-it|Set Operations with Bits]]

**My notes:**

- 

#### Set Complement

> **Book page:** 7

**Study focus:** Representing set membership with bits.

**Concepts to connect:**
- [[Bit-Mapped Sets#^what-is-it|Bit-Mapped Sets]]
- [[Set Operations with Bits#^what-is-it|Set Operations with Bits]]

**My notes:**

- 

#### Set Intersection

> **Book page:** 7

**Study focus:** Representing set membership with bits.

**Concepts to connect:**
- [[Bit-Mapped Sets#^what-is-it|Bit-Mapped Sets]]
- [[Set Operations with Bits#^what-is-it|Set Operations with Bits]]

**My notes:**

- 

#### Set Union

> **Book page:** 8

**Study focus:** Representing set membership with bits.

**Concepts to connect:**
- [[Bit-Mapped Sets#^what-is-it|Bit-Mapped Sets]]
- [[Set Operations with Bits#^what-is-it|Set Operations with Bits]]

**My notes:**

- 

### 6.1.5 XOR Instruction

> **Book page:** 8

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Checking the Parity Flag

> **Book page:** 9

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### 16-Bit Parity

> **Book page:** 10

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### NOT Instruction

> **Book page:** 11

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.1.7 TEST Instruction

> **Book page:** 11

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### Testing Multiple Bits

> **Book page:** 11

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 6.1.8 CMP Instruction

> **Book page:** 12

**Study focus:** An instruction that updates flags as if a subtraction occurred but stores no subtraction result.

**Concepts to connect:**
- [[CMP#^what-is-it|CMP]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### CMP Flags and Comparisons

> **Book page:** 13

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[CMP#^what-is-it|CMP]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.1.9 Setting and Clearing Individual CPU Flags

> **Book page:** 14

**Study focus:** The processor that fetches, decodes, and executes machine instructions.

**Concepts to connect:**
- [[CPU#^what-is-it|CPU]]
- [[ALU#^what-is-it|ALU]]
- [[Control Unit#^what-is-it|Control Unit]]
- [[Registers#^what-is-it|Registers]]
- [[EFLAGS#^what-is-it|EFLAGS]]

**My notes:**

- 

### 6.1.10 Boolean Instructions in 64-Bit Mode

> **Book page:** 15

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[LEA#^what-is-it|LEA]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

## 6.2 Conditional Jumps

> **Book page:** 15

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.2.2 Jcond Instruction

> **Book page:** 16

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Using the CMP Instruction

> **Book page:** 17

**Study focus:** An instruction that updates flags as if a subtraction occurred but stores no subtraction result.

**Concepts to connect:**
- [[CMP#^what-is-it|CMP]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.2.3 Types of Conditional Jump Instructions

> **Book page:** 18

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]

**My notes:**

- 

#### Equality Comparisons

> **Book page:** 19

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Unsigned Comparisons

> **Book page:** 20

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Signed Comparisons

> **Book page:** 21

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Testing Status Bits

> **Book page:** 22

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Larger of Two Integers

> **Book page:** 23

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Smallest of Three Integers

> **Book page:** 24

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Loop until Key Pressed

> **Book page:** 24

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Sequential Search of an Array

> **Book page:** 25

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Simple String Encryption

> **Book page:** 26

**Study focus:** A simple reversible transformation that applies XOR to data using the same key for encryption and decryption.

**Concepts to connect:**
- [[String Encryption with XOR#^what-is-it|String Encryption with XOR]]
- [[XOR#^what-is-it|XOR]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

> [!example] Examples
> Open [[XOR]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Program Listing

> **Book page:** 27

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 6.3 Conditional Loop Instructions

> **Book page:** 27

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[LOOP#^what-is-it|LOOP]]
- [[Conditional Loop Instructions#^what-is-it|Conditional Loop Instructions]]
- [[LOOPZ and LOOPE#^what-is-it|LOOPZ and LOOPE]]
- [[LOOPNZ and LOOPNE#^what-is-it|LOOPNZ and LOOPNE]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### LOOPZ and LOOPE Instructions

> **Book page:** 28

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[LOOP#^what-is-it|LOOP]]
- [[LOOPZ and LOOPE#^what-is-it|LOOPZ and LOOPE]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.3.2 LOOPNZ and LOOPNE Instructions

> **Book page:** 28

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[LOOP#^what-is-it|LOOP]]
- [[LOOPNZ and LOOPNE#^what-is-it|LOOPNZ and LOOPNE]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 6.4 Conditional Structures

> **Book page:** 29

**Study focus:** MASM directives such as .IF, .ELSE, .WHILE, and .REPEAT that generate lower-level branch code.

**Concepts to connect:**
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Block-Structured IF Statements

> **Book page:** 30

**Study focus:** MASM directives such as .IF, .ELSE, .WHILE, and .REPEAT that generate lower-level branch code.

**Concepts to connect:**
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### White Box Testing

> **Book page:** 32

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]
- [[White Box Testing#^what-is-it|White Box Testing]]

**My notes:**

- 

#### Logical AND Operator

> **Book page:** 34

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Short-Circuit Evaluation

> **Book page:** 34

**Study focus:** MASM directives such as .IF, .ELSE, .WHILE, and .REPEAT that generate lower-level branch code.

**Concepts to connect:**
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.4.3 WHILE Loops

> **Book page:** 35

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### IF Statement Nested in a Loop

> **Book page:** 36

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Assembly Code

> **Book page:** 37

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.4.4 Table-Driven Selection

> **Book page:** 38

**Study focus:** Choosing different instruction paths using comparisons, flags, and jump conditions.

**Concepts to connect:**
- [[Conditional Processing#^what-is-it|Conditional Processing]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

## 6.5 Application: Finite-State Machines

> **Book page:** 39

**Study focus:** A model that moves between a fixed set of states according to input and transition rules.

**Concepts to connect:**
- [[Finite-State Machine#^what-is-it|Finite-State Machine]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.5.1 Validating an Input String

> **Book page:** 40

**Study focus:** A model that moves between a fixed set of states according to input and transition rules.

**Concepts to connect:**
- [[Finite-State Machine#^what-is-it|Finite-State Machine]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]
- [[String Literals#^what-is-it|String Literals]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Character String Example

> **Book page:** 40

**Study focus:** The idea that characters are stored as numeric codes in memory.

**Concepts to connect:**
- [[Character Representation#^what-is-it|Character Representation]]
- [[ASCII#^what-is-it|ASCII]]
- [[Unicode#^what-is-it|Unicode]]

**Database / project connection:**
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Character Representation]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.5.2 Validating a Signed Integer

> **Book page:** 41

**Study focus:** A model that moves between a fixed set of states according to input and transition rules.

**Concepts to connect:**
- [[Finite-State Machine#^what-is-it|Finite-State Machine]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]
- [[String Literals#^what-is-it|String Literals]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Complete Finite-State Machine Program

> **Book page:** 42

**Study focus:** A model that moves between a fixed set of states according to input and transition rules.

**Concepts to connect:**
- [[Finite-State Machine#^what-is-it|Finite-State Machine]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]
- [[String Literals#^what-is-it|String Literals]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### IsDigit Procedure

> **Book page:** 43

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

## 6.6 Conditional Control Flow Directives (Optional Topic)

> **Book page:** 44

**Study focus:** Commands interpreted by the assembler rather than executed directly by the CPU.

**Concepts to connect:**
- [[Directives#^what-is-it|Directives]]
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.6.1 Creating IF Statements

> **Book page:** 46

**Study focus:** MASM directives such as .IF, .ELSE, .WHILE, and .REPEAT that generate lower-level branch code.

**Concepts to connect:**
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 6.6.2 Signed and Unsigned Comparisons

> **Book page:** 48

**Study focus:** Jump instructions that transfer control only when specific flag conditions are true.

**Concepts to connect:**
- [[Conditional Jumps#^what-is-it|Conditional Jumps]]
- [[CMP#^what-is-it|CMP]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[CMP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Comparing Registers

> **Book page:** 49

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.6.3 Compound Expressions

> **Book page:** 49

**Study focus:** MASM directives such as .IF, .ELSE, .WHILE, and .REPEAT that generate lower-level branch code.

**Concepts to connect:**
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### SetCursorPosition Example

> **Book page:** 50

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 6.6.4 Creating Loops with .REPEAT and .WHILE

> **Book page:** 52

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]
- [[High-Level MASM Control Flow#^what-is-it|High-Level MASM Control Flow]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Loop Containing an IF Statement

> **Book page:** 53

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 6.7 Chapter Summary

> **Book page:** 53

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 6.8 Key Terms

> **Book page:** 54

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
