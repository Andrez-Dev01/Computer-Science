# Chapter 5 — Procedures

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]

---

## 5.1 Stack Operations

> **Book page:** 1

**Study focus:** A CPU-managed memory area for return addresses, procedure data, parameters, locals, and saved values.

**Concepts to connect:**
- [[Runtime Stack#^what-is-it|Runtime Stack]]
- [[LIFO#^what-is-it|LIFO]]
- [[ESP#^what-is-it|ESP]]

**My notes:**

- 

### 5.1.1 Runtime Stack (32-Bit Mode)

> **Book page:** 2

**Study focus:** A CPU-managed memory area for return addresses, procedure data, parameters, locals, and saved values.

**Concepts to connect:**
- [[Runtime Stack#^what-is-it|Runtime Stack]]
- [[LIFO#^what-is-it|LIFO]]
- [[ESP#^what-is-it|ESP]]

**My notes:**

- 

#### Push Operation

> **Book page:** 3

**Study focus:** An instruction that places a value on the runtime stack and moves the stack pointer.

**Concepts to connect:**
- [[PUSH#^what-is-it|PUSH]]
- [[ESP#^what-is-it|ESP]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

#### Pop Operation

> **Book page:** 4

**Study focus:** An instruction that removes the top stack value into a destination and moves the stack pointer.

**Concepts to connect:**
- [[POP#^what-is-it|POP]]
- [[ESP#^what-is-it|ESP]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

#### Stack Applications

> **Book page:** 4

**Study focus:** A CPU-managed memory area for return addresses, procedure data, parameters, locals, and saved values.

**Concepts to connect:**
- [[Runtime Stack#^what-is-it|Runtime Stack]]
- [[LIFO#^what-is-it|LIFO]]
- [[ESP#^what-is-it|ESP]]

**My notes:**

- 

#### Using PUSH and POP Instructions to Reverse a String

> **Book page:** 5

**Study focus:** An instruction that removes the top stack value into a destination and moves the stack pointer.

**Concepts to connect:**
- [[POP#^what-is-it|POP]]
- [[ESP#^what-is-it|ESP]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

#### PUSH Instruction

> **Book page:** 5

**Study focus:** An instruction that places a value on the runtime stack and moves the stack pointer.

**Concepts to connect:**
- [[PUSH#^what-is-it|PUSH]]
- [[ESP#^what-is-it|ESP]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

#### POP Instruction

> **Book page:** 6

**Study focus:** An instruction that removes the top stack value into a destination and moves the stack pointer.

**Concepts to connect:**
- [[POP#^what-is-it|POP]]
- [[ESP#^what-is-it|ESP]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

#### PUSHFD and POPFD Instructions

> **Book page:** 7

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[PUSHFD and POPFD#^what-is-it|PUSHFD and POPFD]]
- [[EFLAGS#^what-is-it|EFLAGS]]

**My notes:**

- 

#### PUSHAD, PUSHA, POPAD, and POPA

> **Book page:** 7

**Study focus:** 32-bit instructions that save or restore the general-purpose register set on the stack.

**Concepts to connect:**
- [[PUSHAD and POPAD#^what-is-it|PUSHAD and POPAD]]
- [[Registers#^what-is-it|Registers]]

**My notes:**

- 

#### Example: Reversing a String

> **Book page:** 8

**Study focus:** An instruction that places a value on the runtime stack and moves the stack pointer.

**Concepts to connect:**
- [[PUSH#^what-is-it|PUSH]]
- [[POP#^what-is-it|POP]]
- [[String Literals#^what-is-it|String Literals]]

**Database / project connection:**
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[String Literals]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

## 5.2 Defining and Using Procedures

> **Book page:** 8

**Study focus:** Named blocks of code that perform a task and can be called from elsewhere.

**Concepts to connect:**
- [[Procedures#^what-is-it|Procedures]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Procedures]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Defining a Procedure

> **Book page:** 9

**Study focus:** Named blocks of code that perform a task and can be called from elsewhere.

**Concepts to connect:**
- [[Procedures#^what-is-it|Procedures]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Procedures]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Labels in Procedures

> **Book page:** 9

**Study focus:** Names attached to code or data locations so instructions and directives can refer to them.

**Concepts to connect:**
- [[Labels#^what-is-it|Labels]]
- [[Procedures#^what-is-it|Procedures]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Procedures]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Example: SumOf Three Integers

> **Book page:** 10

**Study focus:** Named blocks of code that perform a task and can be called from elsewhere.

**Concepts to connect:**
- [[Procedures#^what-is-it|Procedures]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Procedures]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Documenting Procedures

> **Book page:** 10

**Study focus:** Named blocks of code that perform a task and can be called from elsewhere.

**Concepts to connect:**
- [[Procedures#^what-is-it|Procedures]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

> [!example] Examples
> Open [[Procedures]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 5.2.2 CALL and RET Instructions

> **Book page:** 11

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[CALL#^what-is-it|CALL]]
- [[RET#^what-is-it|RET]]
- [[Return Address#^what-is-it|Return Address]]

**My notes:**

- 

#### Call and Return Example

> **Book page:** 12

**Study focus:** An instruction that transfers control to a procedure while saving a return address.

**Concepts to connect:**
- [[CALL#^what-is-it|CALL]]
- [[RET#^what-is-it|RET]]
- [[Return Address#^what-is-it|Return Address]]

**My notes:**

- 

### 5.2.3 Nested Procedure Calls

> **Book page:** 12

**Study focus:** One procedure calling another before the first returns.

**Concepts to connect:**
- [[Nested Procedure Calls#^what-is-it|Nested Procedure Calls]]
- [[Runtime Stack#^what-is-it|Runtime Stack]]

**My notes:**

- 

### 5.2.4 Passing Register Arguments to Procedures

> **Book page:** 13

**Study focus:** Procedure arguments passed in registers instead of memory or stack slots.

**Concepts to connect:**
- [[Register Parameters#^what-is-it|Register Parameters]]
- [[Procedure Parameters#^what-is-it|Procedure Parameters]]
- [[Registers#^what-is-it|Registers]]

**Database / project connection:**
- [[SQL Functions and Procedures]]

**My notes:**

- 

#### Testing the ArraySum Procedure

> **Book page:** 14

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]
- [[TEST#^what-is-it|TEST]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 5.2.6 Saving and Restoring Registers

> **Book page:** 15

**Study focus:** A PROC option telling MASM which registers a procedure should save and restore.

**Concepts to connect:**
- [[USES#^what-is-it|USES]]
- [[PUSH#^what-is-it|PUSH]]
- [[POP#^what-is-it|POP]]
- [[Registers#^what-is-it|Registers]]

**My notes:**

- 

#### USES Operator

> **Book page:** 15

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
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Debugging Tip

> **Book page:** 16

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Exception

> **Book page:** 16

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 5.3 Linking to an External Library

> **Book page:** 17

**Study focus:** Collections of precompiled routines that a linker can connect to your program.

**Concepts to connect:**
- [[Link Libraries#^what-is-it|Link Libraries]]
- [[Linker#^what-is-it|Linker]]
- [[Multimodule Programs#^what-is-it|Multimodule Programs]]
- [[External Procedures#^what-is-it|External Procedures]]
- [[Module Visibility#^what-is-it|Module Visibility]]

**My notes:**

- 

### 5.3.1 Background Information

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Linker Command Options

> **Book page:** 18

**Study focus:** Collections of precompiled routines that a linker can connect to your program.

**Concepts to connect:**
- [[Link Libraries#^what-is-it|Link Libraries]]
- [[Linker#^what-is-it|Linker]]

**My notes:**

- 

#### Linking 32-Bit Programs

> **Book page:** 19

**Study focus:** Collections of precompiled routines that a linker can connect to your program.

**Concepts to connect:**
- [[Link Libraries#^what-is-it|Link Libraries]]
- [[Linker#^what-is-it|Linker]]

**My notes:**

- 

## 5.4 The Irvine32 Library

> **Book page:** 19

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

### 5.4.2 The Win32 Console Window

> **Book page:** 21

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### properties.

> **Book page:** 22

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### CloseFile

> **Book page:** 22

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Clrscr

> **Book page:** 23

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### CreateOutputFile

> **Book page:** 23

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Crlf

> **Book page:** 24

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Delay

> **Book page:** 24

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### DumpMem

> **Book page:** 24

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### DumpRegs

> **Book page:** 25

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### GetCommandTail

> **Book page:** 25

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### GetMaxXY

> **Book page:** 26

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### GetMseconds

> **Book page:** 27

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### GetTextColor

> **Book page:** 27

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### GotoXY

> **Book page:** 28

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### IsDigit

> **Book page:** 28

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### MsgBox

> **Book page:** 29

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### MsgBoxAsk

> **Book page:** 29

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### OpenInputFile

> **Book page:** 29

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ParseDecimal32

> **Book page:** 30

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

#### ParseInteger32

> **Book page:** 30

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Random32

> **Book page:** 31

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Randomize

> **Book page:** 31

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### RandomRange

> **Book page:** 32

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ReadChar

> **Book page:** 32

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]
- [[ADC#^what-is-it|ADC]]
- [[Extended Precision Arithmetic#^what-is-it|Extended Precision Arithmetic]]

**My notes:**

- 

#### ReadDec

> **Book page:** 33

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

#### ReadFromFile

> **Book page:** 33

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ReadHex

> **Book page:** 34

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ReadInt

> **Book page:** 34

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ReadKey

> **Book page:** 35

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### ReadString

> **Book page:** 35

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### SetTextColor

> **Book page:** 36

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**Database / project connection:**
- [[SQL Boolean Logic]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Str_length

> **Book page:** 37

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WaitMsg

> **Book page:** 37

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteBin

> **Book page:** 38

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteBinB

> **Book page:** 38

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteChar

> **Book page:** 38

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteDec

> **Book page:** 39

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

#### WriteHex

> **Book page:** 39

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteHexB

> **Book page:** 39

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteInt

> **Book page:** 40

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteString

> **Book page:** 40

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### WriteToFile

> **Book page:** 41

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### WriteWindowsMsg

> **Book page:** 41

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]

**My notes:**

- 

#### Tutorial: Library Test #1

> **Book page:** 41

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### Library Test #2: Random Integers

> **Book page:** 42

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### Library Test #3: Performance Timing

> **Book page:** 43

**Study focus:** A teaching library for 32-bit MASM programs that provides convenient I/O and utility procedures.

**Concepts to connect:**
- [[Irvine32 Library#^what-is-it|Irvine32 Library]]
- [[TEST#^what-is-it|TEST]]

**My notes:**

- 

#### Detailed Analysis of the Program

> **Book page:** 44

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 5.5 64-Bit Assembly Programming

> **Book page:** 45

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 5.5.2 Calling 64-Bit Subroutines

> **Book page:** 46

**Study focus:** The Windows x64 convention using register parameters, stack shadow space, and alignment rules.

**Concepts to connect:**
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]

**My notes:**

- 

### 5.5.3 The x64 Calling Convention

> **Book page:** 46

**Study focus:** The Windows x64 convention using register parameters, stack shadow space, and alignment rules.

**Concepts to connect:**
- [[Microsoft x64 Calling Convention#^what-is-it|Microsoft x64 Calling Convention]]
- [[Calling Conventions#^what-is-it|Calling Conventions]]

**My notes:**

- 

### 5.5.4 Sample Program that Calls a Procedure

> **Book page:** 47

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### program.

> **Book page:** 49

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 5.6 Chapter Summary

> **Book page:** 50

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 5.7 Key Terms

> **Book page:** 51

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
