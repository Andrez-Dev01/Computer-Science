# Chapter 4 — Data Transfers Addressing and Arithmetic

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]

---

## 4.1 Data Transfer Instructions

> **Book page:** 2

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[MOV#^what-is-it|MOV]]
- [[Operands#^what-is-it|Operands]]

**My notes:**

- 

### 4.1.2 Operand Types

> **Book page:** 3

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Immediate Operand#^what-is-it|Immediate Operand]]
- [[Register Operand#^what-is-it|Register Operand]]
- [[Memory Operand#^what-is-it|Memory Operand]]

**My notes:**

- 

### 4.1.3 Direct Memory Operands

> **Book page:** 4

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Direct Memory Operand#^what-is-it|Direct Memory Operand]]
- [[Memory Addressing#^what-is-it|Memory Addressing]]

**My notes:**

- 

### 4.1.4 MOV Instruction

> **Book page:** 4

**Study focus:** The x86 instruction used to copy data from a source operand to a destination.

**Concepts to connect:**
- [[MOV#^what-is-it|MOV]]

**My notes:**

- 

#### Memory to Memory

> **Book page:** 5

**Study focus:** The x86 instruction used to copy data from a source operand to a destination.

**Concepts to connect:**
- [[MOV#^what-is-it|MOV]]
- [[Memory Operand#^what-is-it|Memory Operand]]

**My notes:**

- 

#### Overlapping Values

> **Book page:** 5

**Study focus:** Very small, very fast storage locations inside the CPU.

**Concepts to connect:**
- [[Registers#^what-is-it|Registers]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

**My notes:**

- 

#### Copying Smaller Values to Larger Ones

> **Book page:** 6

**Study focus:** Increasing an unsigned value's size by filling new high bits with zero.

**Concepts to connect:**
- [[Zero Extension#^what-is-it|Zero Extension]]
- [[Sign Extension#^what-is-it|Sign Extension]]
- [[MOVZX#^what-is-it|MOVZX]]
- [[MOVSX#^what-is-it|MOVSX]]

**My notes:**

- 

#### MOVZX Instruction

> **Book page:** 7

**Study focus:** Increasing an unsigned value's size by filling new high bits with zero.

**Concepts to connect:**
- [[Zero Extension#^what-is-it|Zero Extension]]
- [[Sign Extension#^what-is-it|Sign Extension]]
- [[MOVZX#^what-is-it|MOVZX]]
- [[MOVSX#^what-is-it|MOVSX]]

**My notes:**

- 

#### 16-bit destination.

> **Book page:** 8

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### MOVSX Instruction

> **Book page:** 8

**Study focus:** Increasing an unsigned value's size by filling new high bits with zero.

**Concepts to connect:**
- [[Zero Extension#^what-is-it|Zero Extension]]
- [[Sign Extension#^what-is-it|Sign Extension]]
- [[MOVZX#^what-is-it|MOVZX]]
- [[MOVSX#^what-is-it|MOVSX]]

**My notes:**

- 

#### 16-bit destination.

> **Book page:** 9

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.1.6 LAHF and SAHF Instructions

> **Book page:** 9

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[LAHF and SAHF#^what-is-it|LAHF and SAHF]]
- [[EFLAGS#^what-is-it|EFLAGS]]

**My notes:**

- 

### 4.1.7 XCHG Instruction

> **Book page:** 10

**Study focus:** An instruction that exchanges the values of two operands.

**Concepts to connect:**
- [[XCHG#^what-is-it|XCHG]]

**My notes:**

- 

### 4.1.8 Direct-Offset Operands

> **Book page:** 10

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Direct-Offset Operands#^what-is-it|Direct-Offset Operands]]
- [[Arrays#^what-is-it|Arrays]]
- [[OFFSET#^what-is-it|OFFSET]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Word and Doubleword Arrays

> **Book page:** 11

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[SQL Data Types]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.1.9 Examples of Moving Data

> **Book page:** 11

**Study focus:** The x86 instruction used to copy data from a source operand to a destination.

**Concepts to connect:**
- [[MOV#^what-is-it|MOV]]
- [[Operands#^what-is-it|Operands]]

**My notes:**

- 

#### Displaying CPU Flags in the Visual Studio Debugger

> **Book page:** 12

**Study focus:** The processor that fetches, decodes, and executes machine instructions.

**Concepts to connect:**
- [[CPU#^what-is-it|CPU]]
- [[ALU#^what-is-it|ALU]]
- [[Control Unit#^what-is-it|Control Unit]]
- [[Registers#^what-is-it|Registers]]
- [[EFLAGS#^what-is-it|EFLAGS]]

**My notes:**

- 

## 4.2 Addition and Subtraction

> **Book page:** 13

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.1 INC and DEC Instructions

> **Book page:** 13

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.2 ADD Instruction

> **Book page:** 14

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.3 SUB Instruction

> **Book page:** 15

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.4 NEG Instruction

> **Book page:** 15

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.6 Flags Affected by Addition and Subtraction

> **Book page:** 16

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Unsigned Operations: Zero, Carry, and Auxiliary Carry

> **Book page:** 17

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Addition and the Carry Flag

> **Book page:** 18

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Subtraction and the Carry Flag

> **Book page:** 18

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Auxiliary Carry

> **Book page:** 19

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Parity

> **Book page:** 20

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Sign Flag

> **Book page:** 20

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### Overflow Flag

> **Book page:** 21

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### The Addition Test

> **Book page:** 21

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### How the Hardware Detects Overflow

> **Book page:** 21

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

#### NEG Instruction

> **Book page:** 22

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.2.7 Example Program (AddSubTest)

> **Book page:** 22

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

## 4.3 Data-Related Operators and Directives

> **Book page:** 23

**Study focus:** Commands interpreted by the assembler rather than executed directly by the CPU.

**Concepts to connect:**
- [[Directives#^what-is-it|Directives]]

**My notes:**

- 

### 4.3.1 OFFSET Operator

> **Book page:** 24

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[OFFSET#^what-is-it|OFFSET]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### OFFSET Examples

> **Book page:** 24

**Study focus:** A MASM operator that obtains the address/offset of a data item known at assembly time.

**Concepts to connect:**
- [[OFFSET#^what-is-it|OFFSET]]
- [[Pointers#^what-is-it|Pointers]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.3.2 ALIGN Directive

> **Book page:** 25

**Study focus:** A directive that moves the next item to a requested alignment boundary.

**Concepts to connect:**
- [[ALIGN#^what-is-it|ALIGN]]

**My notes:**

- 

### 4.3.3 PTR Operator

> **Book page:** 26

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[PTR#^what-is-it|PTR]]
- [[Memory Operand#^what-is-it|Memory Operand]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Moving Smaller Values into Larger Destinations

> **Book page:** 27

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.3.4 TYPE Operator

> **Book page:** 28

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.3.5 LENGTHOF Operator

> **Book page:** 28

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.3.6 SIZEOF Operator

> **Book page:** 29

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.3.7 LABEL Directive

> **Book page:** 30

**Study focus:** Names attached to code or data locations so instructions and directives can refer to them.

**Concepts to connect:**
- [[Labels#^what-is-it|Labels]]
- [[LABEL Directive#^what-is-it|LABEL Directive]]

**My notes:**

- 

## 4.4 Indirect Addressing

> **Book page:** 31

**Study focus:** Accessing memory through a register that contains an address.

**Concepts to connect:**
- [[Indirect Addressing#^what-is-it|Indirect Addressing]]
- [[Pointers#^what-is-it|Pointers]]
- [[ADDR#^what-is-it|ADDR]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Protected Mode

> **Book page:** 31

**Study focus:** An x86 operating mode that supports memory protection, multitasking, and protected address spaces.

**Concepts to connect:**
- [[Protected Mode#^what-is-it|Protected Mode]]

**My notes:**

- 

#### Using PTR with Indirect Operands

> **Book page:** 32

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[PTR#^what-is-it|PTR]]
- [[Memory Operand#^what-is-it|Memory Operand]]

**My notes:**

- 

### 4.4.2 Arrays

> **Book page:** 32

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Example: Adding 32-Bit Integers

> **Book page:** 33

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.4.3 Indexed Operands

> **Book page:** 33

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[Database Index vs CPU Indexed Addressing]]
- [[PostgreSQL Arrays]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Adding Displacements

> **Book page:** 34

**Study focus:** Accessing memory by combining a base location with an index, often for arrays.

**Concepts to connect:**
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[Database Index vs CPU Indexed Addressing]]
- [[PostgreSQL Arrays]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Using 16-Bit Registers

> **Book page:** 34

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Scale Factors in Indexed Operands

> **Book page:** 35

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[Database Index vs CPU Indexed Addressing]]
- [[PostgreSQL Arrays]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.4.4 Pointers

> **Book page:** 35

**Study focus:** Values that hold memory addresses.

**Concepts to connect:**
- [[Pointers#^what-is-it|Pointers]]
- [[TYPEDEF#^what-is-it|TYPEDEF]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### TYPEDEF Operator

> **Book page:** 36

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[Pointers#^what-is-it|Pointers]]
- [[TYPEDEF#^what-is-it|TYPEDEF]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Example Program: Pointers

> **Book page:** 37

**Study focus:** Values that hold memory addresses.

**Concepts to connect:**
- [[Pointers#^what-is-it|Pointers]]
- [[TYPEDEF#^what-is-it|TYPEDEF]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 4.5 JMP and LOOP Instructions

> **Book page:** 37

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[JMP#^what-is-it|JMP]]
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.5.1 JMP Instruction

> **Book page:** 38

**Study focus:** An unconditional branch instruction that transfers execution to a target label.

**Concepts to connect:**
- [[JMP#^what-is-it|JMP]]

**My notes:**

- 

#### Creating a Loop

> **Book page:** 38

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.5.2 LOOP Instruction

> **Book page:** 39

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Nested Loops

> **Book page:** 40

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.5.3 Displaying an Array in the Visual Studio

> **Book page:** 40

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Debugger

> **Book page:** 40

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### to display an array.

> **Book page:** 41

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.5.4 Summing an Integer Array

> **Book page:** 41

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.5.5 Copying a String

> **Book page:** 42

**Study focus:** Sequences of characters written inside quotes in source code.

**Concepts to connect:**
- [[String Literals#^what-is-it|String Literals]]
- [[Character Representation#^what-is-it|Character Representation]]

**Database / project connection:**
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[String Literals]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

## 4.6 64-Bit Programming

> **Book page:** 43

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

### 4.6.2 64-Bit Version of SumArray

> **Book page:** 44

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 4.6.3 Addition and Subtraction

> **Book page:** 44

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]
- [[DEC#^what-is-it|DEC]]
- [[NEG#^what-is-it|NEG]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

## 4.7 Chapter Summary

> **Book page:** 45

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Operand Types

> **Book page:** 46

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]
- [[Immediate Operand#^what-is-it|Immediate Operand]]
- [[Register Operand#^what-is-it|Register Operand]]
- [[Memory Operand#^what-is-it|Memory Operand]]

**My notes:**

- 

#### Status Flags

> **Book page:** 47

**Study focus:** The x86 register containing individual control and status flag bits.

**Concepts to connect:**
- [[EFLAGS#^what-is-it|EFLAGS]]
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]

**My notes:**

- 

#### Operators

> **Book page:** 47

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Loops

> **Book page:** 48

**Study focus:** An x86 loop instruction that uses a counter register and repeats while the count has not reached zero.

**Concepts to connect:**
- [[LOOP#^what-is-it|LOOP]]

> [!example] Examples
> Open [[LOOP]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 4.8 Key Terms

> **Book page:** 48

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 4.8.2 Instructions, Operators, and Directives

> **Book page:** 49

**Study focus:** Commands interpreted by the assembler rather than executed directly by the CPU.

**Concepts to connect:**
- [[Directives#^what-is-it|Directives]]

**My notes:**

- 

---

## End-of-Chapter Review

- [ ] I can explain the main ideas without copying the book.
- [ ] I followed every section in order.
- [ ] I updated concept pages instead of duplicating concepts.
- [ ] I added at least one example in my own words.
- [ ] I connected useful ideas to C++, Python, Go, Java/JVM, or PostgreSQL where it makes sense.
