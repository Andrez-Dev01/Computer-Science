# Chapter 8 — Advanced Procedures

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]
- [[Java and JVM]]
- [[PostgreSQL and Low-Level Concepts]]

---

## 8.1 Introduction

> **Book page:** 2

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.2.2 Disadvantages of Register Parameters

> **Book page:** 3

**Study focus:** Procedure arguments passed in registers instead of memory or stack slots.

**Concepts to connect:**
- [[Register Parameters#^what-is-it|Register Parameters]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Registers#^what-is-it|Registers]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### Passing by Value

> **Book page:** 4

**Study focus:** Passing a copy of an argument's value to a procedure.

**Concepts to connect:**
- [[Passing by Value#^what-is-it|Passing by Value]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Passing by Value]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Passing by Reference

> **Book page:** 5

**Study focus:** Passing an address so a procedure can access or modify the caller's original object.

**Concepts to connect:**
- [[Passing by Reference#^what-is-it|Passing by Reference]]
- [[Pointers#^what-is-it|Pointers]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Passing Arrays

> **Book page:** 5

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.2.3 Accessing Stack Parameters

> **Book page:** 6

**Study focus:** Procedure arguments passed through locations on the runtime stack.

**Concepts to connect:**
- [[Stack Parameters#^what-is-it|Stack Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]
- [[Stack Cleanup#^what-is-it|Stack Cleanup]]
- [[EBP#^what-is-it|EBP]]

**My notes:**

- 

#### AddTwo Example

> **Book page:** 6

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Base-Offset Addressing

> **Book page:** 7

**Study focus:** A MASM operator that obtains the address/offset of a data item known at assembly time.

**Concepts to connect:**
- [[OFFSET#^what-is-it|OFFSET]]
- [[Pointers#^what-is-it|Pointers]]
- [[Base-Offset Addressing#^what-is-it|Base-Offset Addressing]]
- [[EBP#^what-is-it|EBP]]
- [[ADDR#^what-is-it|ADDR]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Explicit Stack Parameters

> **Book page:** 7

**Study focus:** Procedure arguments passed through locations on the runtime stack.

**Concepts to connect:**
- [[Stack Parameters#^what-is-it|Stack Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]
- [[Stack Cleanup#^what-is-it|Stack Cleanup]]
- [[EBP#^what-is-it|EBP]]

**My notes:**

- 

#### Cleaning Up the Stack

> **Book page:** 8

**Study focus:** Procedure arguments passed through locations on the runtime stack.

**Concepts to connect:**
- [[Stack Parameters#^what-is-it|Stack Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]
- [[Stack Cleanup#^what-is-it|Stack Cleanup]]
- [[EBP#^what-is-it|EBP]]
- [[LEA#^what-is-it|LEA]]

**My notes:**

- 

### 8.2.4 32-Bit Calling Conventions

> **Book page:** 8

**Study focus:** Rules defining how functions pass parameters, return values, preserve registers, and clean up the stack.

**Concepts to connect:**
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[C Calling Convention#^what-is-it|C Calling Convention]]
- [[STDCALL#^what-is-it|STDCALL]]
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]

**My notes:**

- 

#### The C Calling Convention

> **Book page:** 9

**Study focus:** Rules defining how functions pass parameters, return values, preserve registers, and clean up the stack.

**Concepts to connect:**
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[C Calling Convention#^what-is-it|C Calling Convention]]
- [[STDCALL#^what-is-it|STDCALL]]
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]

**My notes:**

- 

#### STDCALL Calling Convention

> **Book page:** 9

**Study focus:** Rules defining how functions pass parameters, return values, preserve registers, and clean up the stack.

**Concepts to connect:**
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[C Calling Convention#^what-is-it|C Calling Convention]]
- [[STDCALL#^what-is-it|STDCALL]]
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]

**My notes:**

- 

#### Saving and Restoring Registers

> **Book page:** 10

**Study focus:** A PROC option telling MASM which registers a procedure should save and restore.

**Concepts to connect:**
- [[USES#^what-is-it|USES]]
- [[PUSH#^what-is-it|PUSH]]
- [[POP#^what-is-it|POP]]
- [[Registers#^what-is-it|Registers]]

**My notes:**

- 

### 8.2.5 Local Variables

> **Book page:** 11

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Local Variables#^what-is-it|Local Variables]]
- [[LOCAL#^what-is-it|LOCAL]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Data Types]]
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### variables.

> **Book page:** 12

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Local Variable Symbols

> **Book page:** 12

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.2.6 Reference Parameters

> **Book page:** 13

**Study focus:** Passing an address so a procedure can access or modify the caller's original object.

**Concepts to connect:**
- [[Passing by Reference#^what-is-it|Passing by Reference]]
- [[Pointers#^what-is-it|Pointers]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### ArrayFill Example

> **Book page:** 13

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.2.7 LEA Instruction

> **Book page:** 14

**Study focus:** Load Effective Address computes and loads an address rather than the value stored there.

**Concepts to connect:**
- [[LEA#^what-is-it|LEA]]
- [[Pointers#^what-is-it|Pointers]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.2.8 ENTER and LEAVE Instructions

> **Book page:** 15

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[LEA#^what-is-it|LEA]]
- [[Pointers#^what-is-it|Pointers]]
- [[ENTER#^what-is-it|ENTER]]
- [[LEAVE#^what-is-it|LEAVE]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### LEAVE Instruction

> **Book page:** 16

**Study focus:** Load Effective Address computes and loads an address rather than the value stored there.

**Concepts to connect:**
- [[LEA#^what-is-it|LEA]]
- [[Pointers#^what-is-it|Pointers]]
- [[ENTER#^what-is-it|ENTER]]
- [[LEAVE#^what-is-it|LEAVE]]
- [[Stack Frame#^what-is-it|Stack Frame]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.2.9 LOCAL Directive

> **Book page:** 17

**Study focus:** Variables whose lifetime and visibility belong to a single procedure call, commonly stored in its stack frame.

**Concepts to connect:**
- [[Local Variables#^what-is-it|Local Variables]]
- [[LOCAL#^what-is-it|LOCAL]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Local Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Examples

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### MASM Code Generation

> **Book page:** 18

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.2.10 The Microsoft x64 Calling Convention

> **Book page:** 19

**Study focus:** The Windows x64 convention using register parameters, stack shadow space, and alignment rules.

**Concepts to connect:**
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[C Calling Convention#^what-is-it|C Calling Convention]]
- [[STDCALL#^what-is-it|STDCALL]]

**My notes:**

- 

## 8.3 Recursion

> **Book page:** 20

**Study focus:** A procedure or function calling itself, with each active call keeping its own return information and state.

**Concepts to connect:**
- [[Recursion#^what-is-it|Recursion]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Recursive CTEs]]

> [!example] Examples
> Open [[Recursion]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Endless Recursion

> **Book page:** 20

**Study focus:** A procedure or function calling itself, with each active call keeping its own return information and state.

**Concepts to connect:**
- [[Recursion#^what-is-it|Recursion]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Recursive CTEs]]

> [!example] Examples
> Open [[Recursion]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.3.1 Recursively Calculating a Sum

> **Book page:** 21

**Study focus:** A procedure or function calling itself, with each active call keeping its own return information and state.

**Concepts to connect:**
- [[Recursion#^what-is-it|Recursion]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Recursive CTEs]]

> [!example] Examples
> Open [[Recursion]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.3.2 Calculating a Factorial

> **Book page:** 22

**Study focus:** A procedure or function calling itself, with each active call keeping its own return information and state.

**Concepts to connect:**
- [[Recursion#^what-is-it|Recursion]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Recursive CTEs]]

> [!example] Examples
> Open [[Recursion]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Example Program

> **Book page:** 22

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

## 8.4 INVOKE, ADDR, PROC, and PROTO

> **Book page:** 24

**Study focus:** A MASM directive that calls a procedure and arranges arguments using a calling convention.

**Concepts to connect:**
- [[INVOKE#^what-is-it|INVOKE]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[ADDR#^what-is-it|ADDR]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]
- [[PROTO#^what-is-it|PROTO]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.4.1 INVOKE Directive

> **Book page:** 25

**Study focus:** A MASM directive that calls a procedure and arranges arguments using a calling convention.

**Concepts to connect:**
- [[INVOKE#^what-is-it|INVOKE]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### EAX, EDX Overwritten

> **Book page:** 26

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.4.2 ADDR Operator

> **Book page:** 26

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[ADDR#^what-is-it|ADDR]]
- [[Passing by Reference#^what-is-it|Passing by Reference]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Syntax of the PROC Directive

> **Book page:** 27

**Study focus:** A MASM directive that declares a procedure, optionally with parameters and saved registers.

**Concepts to connect:**
- [[PROC Directive#^what-is-it|PROC Directive]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### Parameter Lists

> **Book page:** 28

**Study focus:** A MASM directive that declares a procedure, optionally with parameters and saved registers.

**Concepts to connect:**
- [[PROC Directive#^what-is-it|PROC Directive]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### RET Instruction Modified by PROC

> **Book page:** 31

**Study focus:** A MASM directive that declares a procedure, optionally with parameters and saved registers.

**Concepts to connect:**
- [[PROC Directive#^what-is-it|PROC Directive]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### Specifying the Parameter Passing Protocol

> **Book page:** 32

**Study focus:** A MASM directive that declares a procedure, optionally with parameters and saved registers.

**Concepts to connect:**
- [[PROC Directive#^what-is-it|PROC Directive]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[PROTO#^what-is-it|PROTO]]
- [[INVOKE#^what-is-it|INVOKE]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

### 8.4.4 PROTO Directive

> **Book page:** 32

**Study focus:** A MASM directive that declares a procedure prototype.

**Concepts to connect:**
- [[PROTO#^what-is-it|PROTO]]
- [[INVOKE#^what-is-it|INVOKE]]

**My notes:**

- 

#### Assembly Time Argument Checking

> **Book page:** 33

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Errors Detected by MASM

> **Book page:** 34

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]

**My notes:**

- 

#### Errors Not Detected by MASM

> **Book page:** 35

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]

**My notes:**

- 

#### ArraySum Example

> **Book page:** 35

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.4.5 Parameter Classifications

> **Book page:** 36

**Study focus:** Ways to describe procedure parameters as input, output, or input-output values.

**Concepts to connect:**
- [[Parameter Classifications#^what-is-it|Parameter Classifications]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

### 8.4.6 Example: Exchanging Two Integers

> **Book page:** 36

**Study focus:** Passing an address so a procedure can access or modify the caller's original object.

**Concepts to connect:**
- [[Passing by Reference#^what-is-it|Passing by Reference]]
- [[XCHG#^what-is-it|XCHG]]

> [!example] Examples
> Open [[Passing by Reference]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Argument Size Mismatch

> **Book page:** 37

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Passing the Wrong Type of Pointer

> **Book page:** 38

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Passing Immediate Values

> **Book page:** 38

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Pointers#^what-is-it|Pointers]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Pointers]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.4.8 WriteStackFrame Procedure

> **Book page:** 39

**Study focus:** An instruction that performs AND only to update flags, without storing the AND result.

**Concepts to connect:**
- [[TEST#^what-is-it|TEST]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**My notes:**

- 

## 8.5 Creating Multimodule Programs

> **Book page:** 39

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 8.5.1 Hiding and Exporting Procedure Names

> **Book page:** 40

**Study focus:** Programs split across separately assembled source modules later linked into one executable.

**Concepts to connect:**
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]
- [[EXTERN#^what-is-it|EXTERN]]

**My notes:**

- 

#### OPTION PROC:PRIVATE Directive

> **Book page:** 40

**Study focus:** Programs split across separately assembled source modules later linked into one executable.

**Concepts to connect:**
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]
- [[EXTERN#^what-is-it|EXTERN]]

**My notes:**

- 

### 8.5.2 Calling External Procedures

> **Book page:** 41

**Study focus:** Programs split across separately assembled source modules later linked into one executable.

**Concepts to connect:**
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]
- [[EXTERN#^what-is-it|EXTERN]]

**My notes:**

- 

#### Exporting Variables and Symbols

> **Book page:** 42

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Accessing External Variables and Symbols

> **Book page:** 42

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Using an INCLUDE File with EXTERNDEF

> **Book page:** 43

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
> Open [[ADD]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.5.4 Example: ArraySum Program

> **Book page:** 43

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.5.5 Creating the Modules Using Extern

> **Book page:** 44

**Study focus:** Programs split across separately assembled source modules later linked into one executable.

**Concepts to connect:**
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]
- [[EXTERN#^what-is-it|EXTERN]]

**My notes:**

- 

#### PromptForIntegers

> **Book page:** 44

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### ArraySum

> **Book page:** 45

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### DisplaySum

> **Book page:** 46

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Startup Module

> **Book page:** 46

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.5.6 Creating the Modules Using INVOKE and PROTO

> **Book page:** 47

**Study focus:** A MASM directive that calls a procedure and arranges arguments using a calling convention.

**Concepts to connect:**
- [[INVOKE#^what-is-it|INVOKE]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[PROTO#^what-is-it|PROTO]]
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### The sum.inc Include File

> **Book page:** 48

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
> Open [[ADD]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### The _prompt Module

> **Book page:** 49

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### The _arraysum Module

> **Book page:** 49

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### The _display Module

> **Book page:** 50

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### The Sum_main Module

> **Book page:** 51

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Summary

> **Book page:** 51

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

## 8.6 Advanced Use of Parameters (Optional Topic)

> **Book page:** 52

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

### 8.6.1 Stack Affected by the USES Operator

> **Book page:** 52

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[USES#^what-is-it|USES]]
- [[PUSH#^what-is-it|PUSH]]
- [[POP#^what-is-it|POP]]
- [[Registers#^what-is-it|Registers]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.6.2 Passing 8-Bit and 16-Bit Arguments on the Stack

> **Book page:** 53

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### 16-Bit Argument Example

> **Book page:** 54

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.6.3 Passing 64-Bit Arguments

> **Book page:** 55

**Study focus:** Input values or references supplied to a procedure.

**Concepts to connect:**
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

### 8.6.4 Non-Doubleword Local Variables

> **Book page:** 56

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Local Variables#^what-is-it|Local Variables]]
- [[LOCAL#^what-is-it|LOCAL]]
- [[Stack Frame#^what-is-it|Stack Frame]]

**Database / project connection:**
- [[SQL Data Types]]
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### (Example1 Procedure).

> **Book page:** 56

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### variables.

> **Book page:** 57

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

## 8.7 Java Bytecodes (Optional Topic)

> **Book page:** 58

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[JVM#^what-is-it|JVM]]
- [[JIT Compilation#^what-is-it|JIT Compilation]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Viewing Disassembled Bytecodes

> **Book page:** 59

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Primitive Data Types

> **Book page:** 59

**Study focus:** Java's built-in primitive value types such as int, long, float, double, char, and boolean.

**Concepts to connect:**
- [[Java Primitive Types#^what-is-it|Java Primitive Types]]

**My notes:**

- 

#### Comparison Instructions

> **Book page:** 60

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

#### Branching Instructions

> **Book page:** 61

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[Conditional Processing#^what-is-it|Conditional Processing]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Conditional Processing]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

### 8.7.3 Java Disassembly Examples

> **Book page:** 61

**Study focus:** The instruction format executed by the JVM rather than directly by the physical x86 CPU.

**Concepts to connect:**
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[JVM#^what-is-it|JVM]]
- [[JIT Compilation#^what-is-it|JIT Compilation]]

> [!example] Examples
> Open [[JVM]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Example: Adding Two Integers

> **Book page:** 61

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Example: Adding Two Doubles

> **Book page:** 62

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

### 8.7.4 Example: Conditional Branch

> **Book page:** 63

**Study focus:** The instruction format executed by the JVM rather than directly by the physical x86 CPU.

**Concepts to connect:**
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[JVM#^what-is-it|JVM]]
- [[JIT Compilation#^what-is-it|JIT Compilation]]

> [!example] Examples
> Open [[JVM]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Conclusion

> **Book page:** 64

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

## 8.8 Chapter Summary

> **Book page:** 65

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

#### Java Bytecodes

> **Book page:** 66

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Java Bytecode#^what-is-it|Java Bytecode]]
- [[JVM#^what-is-it|JVM]]
- [[JIT Compilation#^what-is-it|JIT Compilation]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go/Java / PostgreSQL examples.

**My notes:**

- 

## 8.9 Key Terms

> **Book page:** 66

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go/Java examples.

**My notes:**

- 

---

## End-of-Chapter Review

- [ ] I can explain the main ideas without copying the book.
- [ ] I followed every section in order.
- [ ] I updated concept pages instead of duplicating concepts.
- [ ] I added at least one example in my own words.
- [ ] I connected useful ideas to C++, Python, Go, Java/JVM, or PostgreSQL where it makes sense.
