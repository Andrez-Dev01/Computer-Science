# Chapter 3 — Assembly Language Fundamentals

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]

---

## 3.1 Basic Language Elements

> **Book page:** 2

**Study focus:** The statement and naming rules used by Microsoft Macro Assembler.

**Concepts to connect:**
- [[MASM Syntax#^what-is-it|MASM Syntax]]
- [[Instructions#^what-is-it|Instructions]]
- [[Directives#^what-is-it|Directives]]

**My notes:**

- 

#### Adding a Variable

> **Book page:** 2

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.1.2 Integer Literals

> **Book page:** 3

**Study focus:** Integer constants written directly in source code, possibly with radix suffixes.

**Concepts to connect:**
- [[Integer Literals#^what-is-it|Integer Literals]]

**My notes:**

- 

### 3.1.3 Constant Integer Expressions

> **Book page:** 4

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[Operator Precedence#^what-is-it|Operator Precedence]]

**My notes:**

- 

### 3.1.4 Real Number Literals

> **Book page:** 5

**Study focus:** Processor hardware specialized for floating-point arithmetic.

**Concepts to connect:**
- [[Floating-Point Unit#^what-is-it|Floating-Point Unit]]
- [[Constants#^what-is-it|Constants]]

**My notes:**

- 

### 3.1.5 Character Literals

> **Book page:** 5

**Study focus:** Single characters written as literal values in source code.

**Concepts to connect:**
- [[Character Literals#^what-is-it|Character Literals]]
- [[ASCII#^what-is-it|ASCII]]

**Database / project connection:**
- [[SQL Text and Encoding]]

**My notes:**

- 

### 3.1.6 String Literals

> **Book page:** 6

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

### 3.1.7 Reserved Words

> **Book page:** 6

**Study focus:** Words with special meaning to MASM that cannot be freely reused as identifiers.

**Concepts to connect:**
- [[Reserved Words#^what-is-it|Reserved Words]]
- [[Identifiers#^what-is-it|Identifiers]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.1.8 Identifiers

> **Book page:** 7

**Study focus:** Programmer-chosen names for variables, labels, procedures, and constants.

**Concepts to connect:**
- [[Identifiers#^what-is-it|Identifiers]]

**My notes:**

- 

### 3.1.9 Directives

> **Book page:** 8

**Study focus:** Commands interpreted by the assembler rather than executed directly by the CPU.

**Concepts to connect:**
- [[Directives#^what-is-it|Directives]]

**My notes:**

- 

#### Defining Program Segments

> **Book page:** 9

**Study focus:** Logical program areas for code, data, and stack storage.

**Concepts to connect:**
- [[Program Segments#^what-is-it|Program Segments]]
- [[Code Segment#^what-is-it|Code Segment]]
- [[Data Segment#^what-is-it|Data Segment]]
- [[Stack Segment#^what-is-it|Stack Segment]]

**My notes:**

- 

### 3.1.10 Instructions

> **Book page:** 9

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]

**My notes:**

- 

#### Label

> **Book page:** 10

**Study focus:** Names attached to code or data locations so instructions and directives can refer to them.

**Concepts to connect:**
- [[Labels#^what-is-it|Labels]]

**My notes:**

- 

#### Instruction Mnemonic

> **Book page:** 10

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]

**My notes:**

- 

#### Operands

> **Book page:** 11

**Study focus:** The values or locations an instruction works with: immediate, register, or memory.

**Concepts to connect:**
- [[Operands#^what-is-it|Operands]]

**My notes:**

- 

#### Comments

> **Book page:** 12

**Study focus:** Human-readable notes in source code that the assembler ignores.

**Concepts to connect:**
- [[Comments#^what-is-it|Comments]]

**My notes:**

- 

#### The NOP (No Operation) Instruction

> **Book page:** 12

**Study focus:** A no-operation instruction that intentionally performs no meaningful computation.

**Concepts to connect:**
- [[NOP#^what-is-it|NOP]]

**My notes:**

- 

## 3.2 Example: Adding and Subtracting Integers

> **Book page:** 13

**Study focus:** An instruction that adds a source value to a destination value.

**Concepts to connect:**
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### A Review of Assembler Directives

> **Book page:** 14

**Study focus:** Commands interpreted by the assembler rather than executed directly by the CPU.

**Concepts to connect:**
- [[Directives#^what-is-it|Directives]]

**My notes:**

- 

#### Visual Studio project.

> **Book page:** 15

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Debugging Demonstration

> **Book page:** 15

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Customizing the Debugging Interface

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Registers window.

> **Book page:** 17

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.2.3 Program Template

> **Book page:** 18

**Study focus:** The statement and naming rules used by Microsoft Macro Assembler.

**Concepts to connect:**
- [[MASM Syntax#^what-is-it|MASM Syntax]]
- [[Program Segments#^what-is-it|Program Segments]]

**My notes:**

- 

#### Use Comments

> **Book page:** 18

**Study focus:** Human-readable notes in source code that the assembler ignores.

**Concepts to connect:**
- [[Comments#^what-is-it|Comments]]

**My notes:**

- 

## 3.3 Assembling, Linking, and Running Programs

> **Book page:** 19

**Study focus:** A tool that translates Assembly source code into machine-code object files.

**Concepts to connect:**
- [[Assembler#^what-is-it|Assembler]]
- [[Linker#^what-is-it|Linker]]
- [[Object File#^what-is-it|Object File]]
- [[Source File#^what-is-it|Source File]]

**My notes:**

- 

### 3.3.1 The Assemble-Link-Execute Cycle

> **Book page:** 19

**Study focus:** A tool that translates Assembly source code into machine-code object files.

**Concepts to connect:**
- [[Assembler#^what-is-it|Assembler]]
- [[Linker#^what-is-it|Linker]]
- [[Object File#^what-is-it|Object File]]
- [[Source File#^what-is-it|Source File]]

**My notes:**

- 

### 3.3.2 Listing File

> **Book page:** 20

**Study focus:** An assembler-generated report that can show source lines, addresses, machine code, and symbols.

**Concepts to connect:**
- [[Listing File#^what-is-it|Listing File]]

**My notes:**

- 

## 3.4 Defining Data

> **Book page:** 21

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.2 Data Definition Statement

> **Book page:** 22

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Name

> **Book page:** 23

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Directive

> **Book page:** 23

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Initializer

> **Book page:** 24

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.4.3 Adding a Variable to the AddTwo Program

> **Book page:** 25

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.4 Defining BYTE and SBYTE Data

> **Book page:** 25

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Multiple Initializers

> **Book page:** 26

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

#### Defining Strings

> **Book page:** 27

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

#### DUP Operator

> **Book page:** 27

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[DUP#^what-is-it|DUP]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.5 Defining WORD and SWORD Data

> **Book page:** 28

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Array of 16-Bit Words

> **Book page:** 28

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

### 3.4.6 Defining DWORD and SDWORD Data

> **Book page:** 29

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Array of 32-Bt Doublewords

> **Book page:** 29

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Arrays#^what-is-it|Arrays]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]

**Database / project connection:**
- [[SQL Data Types]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.7 Defining QWORD Data

> **Book page:** 30

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.8 Defining Packed BCD (TBYTE) Data

> **Book page:** 30

**Study focus:** Binary-Coded Decimal stores each decimal digit using binary patterns.

**Concepts to connect:**
- [[BCD#^what-is-it|BCD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]
- [[Packed Decimal Arithmetic#^what-is-it|Packed Decimal Arithmetic]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.9 Defining Floating-Point Types

> **Book page:** 31

**Study focus:** Processor hardware specialized for floating-point arithmetic.

**Concepts to connect:**
- [[Floating-Point Unit#^what-is-it|Floating-Point Unit]]
- [[Constants#^what-is-it|Constants]]

**My notes:**

- 

### 3.4.10 A Program That Adds Variables

> **Book page:** 33

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]

**Database / project connection:**
- [[SQL Data Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.4.11 Little-Endian Order

> **Book page:** 33

**Study focus:** A byte order where the least-significant byte is stored at the lowest address.

**Concepts to connect:**
- [[Little Endian#^what-is-it|Little Endian]]

**My notes:**

- 

#### 12345678h.

> **Book page:** 34

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.4.12 Declaring Uninitialized Data

> **Book page:** 34

**Study focus:** Named storage locations reserved in memory.

**Concepts to connect:**
- [[Variables#^what-is-it|Variables]]
- [[Memory#^what-is-it|Memory]]
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]
- [[INC#^what-is-it|INC]]

**Database / project connection:**
- [[SQL Data Types]]
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Mixing Code and Data

> **Book page:** 35

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 3.5 Symbolic Constants

> **Book page:** 35

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]

**My notes:**

- 

### 3.5.1 Equal-Sign Directive

> **Book page:** 36

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]

**My notes:**

- 

#### Why Use Symbols?

> **Book page:** 36

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Current Location Counter

> **Book page:** 37

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Keyboard Definitions

> **Book page:** 37

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Using the DUP Operator

> **Book page:** 38

**Study focus:** Logic built from true/false or 1/0 values using AND, OR, XOR, and NOT.

**Concepts to connect:**
- [[Boolean Logic#^what-is-it|Boolean Logic]]
- [[DUP#^what-is-it|DUP]]
- [[Arrays#^what-is-it|Arrays]]

**Database / project connection:**
- [[SQL Boolean Logic]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Boolean Logic]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Redefinitions

> **Book page:** 38

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.5.2 Calculating the Sizes of Arrays and Strings

> **Book page:** 38

**Study focus:** Contiguous sequences of elements stored in memory.

**Concepts to connect:**
- [[Arrays#^what-is-it|Arrays]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]
- [[LOOP#^what-is-it|LOOP]]

**Database / project connection:**
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Arrays]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Arrays of Words and DoubleWords

> **Book page:** 39

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Arrays#^what-is-it|Arrays]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Indexed Addressing#^what-is-it|Indexed Addressing]]

**Database / project connection:**
- [[SQL Data Types]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 3.5.3 EQU Directive

> **Book page:** 39

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]

**My notes:**

- 

#### No Redefinition

> **Book page:** 41

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.5.4 TEXTEQU Directive

> **Book page:** 41

**Study focus:** Fixed values or symbolic names that do not represent writable program storage.

**Concepts to connect:**
- [[Constants#^what-is-it|Constants]]
- [[EQU#^what-is-it|EQU]]
- [[TEXTEQU#^what-is-it|TEXTEQU]]

**My notes:**

- 

## 3.6 Introducing 64-Bit Programming

> **Book page:** 42

**Study focus:** Processor modes that change important register, operand, and address sizes.

**Concepts to connect:**
- [[32-bit and 64-bit Modes#^what-is-it|32-bit and 64-bit Modes]]
- [[x86 Architecture#^what-is-it|x86 Architecture]]

**My notes:**

- 

#### Using 64-Bit Registers

> **Book page:** 43

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 3.7 Chapter Summary

> **Book page:** 43

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 3.8 Key Terms

> **Book page:** 45

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 3.8.2 Instructions, Operators, and Directives

> **Book page:** 48

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
