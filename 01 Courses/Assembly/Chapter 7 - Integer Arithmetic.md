# Chapter 7 — Integer Arithmetic

> [!important] How to read this note
> Read this page from top to bottom while you read the chapter. Each book section stays in the same order. Hover a concept link to preview its **What is it?** explanation. Click it when you want the full concept, examples, language connections, and database connections.

## Language Bridges for This Chapter

- [[C++ and Assembly]]
- [[Python and Assembly]]
- [[Go and Assembly]]
- [[PostgreSQL and Low-Level Concepts]]

---

## 7.1 Shift and Rotate Instructions

> **Book page:** 2

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[Bit Shifting#^what-is-it|Bit Shifting]]
- [[Logical vs Arithmetic Shifts#^what-is-it|Logical vs Arithmetic Shifts]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

> [!example] Examples
> Open [[Bit Shifting]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.1.1 Logical Shifts and Arithmetic Shifts

> **Book page:** 3

**Study focus:** Moving the bits of an operand left or right.

**Concepts to connect:**
- [[Bit Shifting#^what-is-it|Bit Shifting]]
- [[Logical vs Arithmetic Shifts#^what-is-it|Logical vs Arithmetic Shifts]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

> [!example] Examples
> Open [[Bit Shifting]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Bitwise Multiplication

> **Book page:** 5

**Study focus:** Using left shifts, sometimes with additions, to multiply by powers of two or sums of powers of two.

**Concepts to connect:**
- [[Bitwise Multiplication#^what-is-it|Bitwise Multiplication]]
- [[SHL#^what-is-it|SHL]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]
- [[SQL Integer Types]]

**My notes:**

- 

### 7.1.3 SHR Instruction

> **Book page:** 5

**Study focus:** Logical Shift Right moves bits right, inserts zero at the high end, and sends the outgoing low bit to Carry.

**Concepts to connect:**
- [[SHR#^what-is-it|SHR]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

**My notes:**

- 

#### Bitwise Division

> **Book page:** 6

**Study focus:** The x86 unsigned division instruction.

**Concepts to connect:**
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 7.1.4 SAL and SAR Instructions

> **Book page:** 6

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[SAL#^what-is-it|SAL]]
- [[SAR#^what-is-it|SAR]]

**My notes:**

- 

#### Signed Division

> **Book page:** 7

**Study focus:** The x86 signed division instruction.

**Concepts to connect:**
- [[IDIV#^what-is-it|IDIV]]
- [[Signed Integers#^what-is-it|Signed Integers]]
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Sign-Extend AX into EAX

> **Book page:** 7

**Study focus:** Increasing a signed value's size while preserving its sign.

**Concepts to connect:**
- [[Sign Extension#^what-is-it|Sign Extension]]
- [[CBW CWD CDQ#^what-is-it|CBW CWD CDQ]]

**My notes:**

- 

#### Multiple Rotations

> **Book page:** 8

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]
- [[MUL#^what-is-it|MUL]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

#### Exchanging Groups of Bits

> **Book page:** 8

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

### 7.1.6 ROR Instruction

> **Book page:** 9

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]

**My notes:**

- 

#### Multiple Rotations

> **Book page:** 9

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]
- [[MUL#^what-is-it|MUL]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 7.1.7 RCL and RCR Instructions

> **Book page:** 10

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]

**My notes:**

- 

#### Recover a Bit from the Carry Flag

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

#### RCR Instruction

> **Book page:** 11

**Study focus:** Rotate Left moves bits left and wraps the outgoing high bit back into the low end.

**Concepts to connect:**
- [[ROL#^what-is-it|ROL]]
- [[ROR#^what-is-it|ROR]]
- [[RCL#^what-is-it|RCL]]
- [[RCR#^what-is-it|RCR]]

**My notes:**

- 

### 7.1.8 Signed Overflow

> **Book page:** 11

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

### 7.1.9 SHLD/SHRD Instructions

> **Book page:** 12

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[SHR#^what-is-it|SHR]]
- [[SHLD#^what-is-it|SHLD]]
- [[SHRD#^what-is-it|SHRD]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

**My notes:**

- 

## 7.2 Shift and Rotate Applications

> **Book page:** 14

**Study focus:** Moving the bits of an operand left or right.

**Concepts to connect:**
- [[Bit Shifting#^what-is-it|Bit Shifting]]
- [[Logical vs Arithmetic Shifts#^what-is-it|Logical vs Arithmetic Shifts]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

> [!example] Examples
> Open [[Bit Shifting]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.2.1 Shifting Multiple Doublewords

> **Book page:** 14

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[Arrays#^what-is-it|Arrays]]
- [[TYPE LENGTHOF SIZEOF#^what-is-it|TYPE LENGTHOF SIZEOF]]
- [[Extended Precision Arithmetic#^what-is-it|Extended Precision Arithmetic]]

**Database / project connection:**
- [[SQL Data Types]]
- [[PostgreSQL Arrays]]
- [[Database Index vs CPU Indexed Addressing]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.2.2 Multiplication by Shifting Bits

> **Book page:** 15

**Study focus:** Using left shifts, sometimes with additions, to multiply by powers of two or sums of powers of two.

**Concepts to connect:**
- [[Bitwise Multiplication#^what-is-it|Bitwise Multiplication]]
- [[SHL#^what-is-it|SHL]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]
- [[SQL Integer Types]]

**My notes:**

- 

### 7.2.3 Displaying Binary Bits

> **Book page:** 16

**Study focus:** Numbers represented using only 0 and 1.

**Concepts to connect:**
- [[Binary Numbers#^what-is-it|Binary Numbers]]
- [[Bit Shifting#^what-is-it|Bit Shifting]]

**Database / project connection:**
- [[PostgreSQL Bitwise Operations]]

> [!example] Examples
> Open [[Binary Numbers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.2.4 Extracting File Date Fields

> **Book page:** 17

**Study focus:** Packed date/time fields stored inside selected groups of bits that can be isolated with shifts and masks.

**Concepts to connect:**
- [[File Date Bit Fields#^what-is-it|File Date Bit Fields]]
- [[Bit Masking#^what-is-it|Bit Masking]]

**My notes:**

- 

## 7.3 Multiplication and Division Instructions

> **Book page:** 18

**Study focus:** Statements describing operations the processor executes at run time.

**Concepts to connect:**
- [[Instructions#^what-is-it|Instructions]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[DIV#^what-is-it|DIV]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 7.3.1 Unsigned Integer Multiplication (MUL)

> **Book page:** 18

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IMUL#^what-is-it|IMUL]]
- [[Signed Integers#^what-is-it|Signed Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### MUL Examples

> **Book page:** 19

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

#### Using MUL in 64-Bit Mode

> **Book page:** 20

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 7.3.2 Signed Integer Multiplication (IMUL)

> **Book page:** 20

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IMUL#^what-is-it|IMUL]]
- [[Signed Integers#^what-is-it|Signed Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Single-Operand Formats

> **Book page:** 21

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Two-Operand Formats (32-Bit Mode)

> **Book page:** 21

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Three-Operand Formats

> **Book page:** 22

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

#### Using IMUL in 64-Bit Mode

> **Book page:** 23

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IMUL#^what-is-it|IMUL]]
- [[Signed Integers#^what-is-it|Signed Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Unsigned Multiplication

> **Book page:** 23

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

#### IMUL Examples

> **Book page:** 24

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IMUL#^what-is-it|IMUL]]
- [[Signed Integers#^what-is-it|Signed Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.3.3 Measuring Program Execution Times

> **Book page:** 25

**Study focus:** Measuring how long code takes to run so alternative implementations can be compared.

**Concepts to connect:**
- [[Execution Time Measurement#^what-is-it|Execution Time Measurement]]
- [[CPU Clock#^what-is-it|CPU Clock]]

**My notes:**

- 

#### Comparing MUL and IMUL to Bit Shifting

> **Book page:** 25

**Study focus:** The x86 unsigned multiplication instruction.

**Concepts to connect:**
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IMUL#^what-is-it|IMUL]]
- [[Signed Integers#^what-is-it|Signed Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.3.4 Unsigned Integer Division (DIV)

> **Book page:** 26

**Study focus:** The x86 unsigned division instruction.

**Concepts to connect:**
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IDIV#^what-is-it|IDIV]]
- [[Signed Integers#^what-is-it|Signed Integers]]
- [[CBW CWD CDQ#^what-is-it|CBW CWD CDQ]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### DIV Examples

> **Book page:** 26

**Study focus:** The x86 unsigned division instruction.

**Concepts to connect:**
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]

**Database / project connection:**
- [[SQL Integer Types]]

**My notes:**

- 

### 7.3.5 Signed Integer Division (IDIV)

> **Book page:** 28

**Study focus:** The x86 unsigned division instruction.

**Concepts to connect:**
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IDIV#^what-is-it|IDIV]]
- [[Signed Integers#^what-is-it|Signed Integers]]
- [[CBW CWD CDQ#^what-is-it|CBW CWD CDQ]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Sign Extension Instructions (CBW, CWD, CDQ)

> **Book page:** 29

**Study focus:** Increasing a signed value's size while preserving its sign.

**Concepts to connect:**
- [[Sign Extension#^what-is-it|Sign Extension]]
- [[CBW CWD CDQ#^what-is-it|CBW CWD CDQ]]

**My notes:**

- 

#### The IDIV Instruction

> **Book page:** 29

**Study focus:** The x86 unsigned division instruction.

**Concepts to connect:**
- [[DIV#^what-is-it|DIV]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[IDIV#^what-is-it|IDIV]]
- [[Signed Integers#^what-is-it|Signed Integers]]
- [[CBW CWD CDQ#^what-is-it|CBW CWD CDQ]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Signed Integers]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### Divide Overflow

> **Book page:** 31

**Study focus:** Flag bits that describe results of arithmetic and logical operations.

**Concepts to connect:**
- [[CPU Status Flags#^what-is-it|CPU Status Flags]]
- [[Carry Flag#^what-is-it|Carry Flag]]
- [[Overflow Flag#^what-is-it|Overflow Flag]]
- [[Parity Flag#^what-is-it|Parity Flag]]
- [[Sign Flag#^what-is-it|Sign Flag]]

**My notes:**

- 

### 7.3.6 Implementing Arithmetic Expressions

> **Book page:** 32

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

## 7.4 Extended Addition and Subtraction

> **Book page:** 35

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

### 7.4.1 ADC Instruction

> **Book page:** 36

**Study focus:** Add with Carry adds the source, destination, and current Carry flag.

**Concepts to connect:**
- [[ADC#^what-is-it|ADC]]
- [[Extended Precision Arithmetic#^what-is-it|Extended Precision Arithmetic]]

**My notes:**

- 

### 7.4.2 Extended Addition Example

> **Book page:** 36

**Study focus:** Add with Carry adds the source, destination, and current Carry flag.

**Concepts to connect:**
- [[ADC#^what-is-it|ADC]]
- [[Extended Precision Arithmetic#^what-is-it|Extended Precision Arithmetic]]

**My notes:**

- 

### 7.4.3 SBB Instruction

> **Book page:** 37

**Study focus:** Subtract with Borrow includes the Carry/borrow state in subtraction.

**Concepts to connect:**
- [[SBB#^what-is-it|SBB]]
- [[Extended Precision Arithmetic#^what-is-it|Extended Precision Arithmetic]]

**My notes:**

- 

## 7.5 ASCII and Unpacked Decimal Arithmetic

> **Book page:** 38

**Study focus:** The idea that characters are stored as numeric codes in memory.

**Concepts to connect:**
- [[Character Representation#^what-is-it|Character Representation]]
- [[ASCII#^what-is-it|ASCII]]
- [[Unicode#^what-is-it|Unicode]]
- [[BCD#^what-is-it|BCD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**Database / project connection:**
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Character Representation]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

#### ASCII Decimal and Unpacked Decimal

> **Book page:** 39

**Study focus:** The idea that characters are stored as numeric codes in memory.

**Concepts to connect:**
- [[Character Representation#^what-is-it|Character Representation]]
- [[ASCII#^what-is-it|ASCII]]
- [[Unicode#^what-is-it|Unicode]]
- [[BCD#^what-is-it|BCD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**Database / project connection:**
- [[SQL Text and Encoding]]

> [!example] Examples
> Open [[Character Representation]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.5.1 AAA Instruction

> **Book page:** 39

**Study focus:** Legacy 32-bit x86 adjust instructions used with ASCII or unpacked decimal arithmetic.

**Concepts to connect:**
- [[AAA AAS AAM AAD#^what-is-it|AAA AAS AAM AAD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**My notes:**

- 

#### Multibyte Addition Using AAA

> **Book page:** 40

**Study focus:** Common MASM size names for 8-, 16-, 32-, and 64-bit storage.

**Concepts to connect:**
- [[BYTE WORD DWORD QWORD#^what-is-it|BYTE WORD DWORD QWORD]]
- [[Variables#^what-is-it|Variables]]
- [[MUL#^what-is-it|MUL]]
- [[Unsigned Integers#^what-is-it|Unsigned Integers]]
- [[AAA AAS AAM AAD#^what-is-it|AAA AAS AAM AAD]]

**Database / project connection:**
- [[SQL Data Types]]
- [[SQL Integer Types]]

> [!example] Examples
> Open [[Variables]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.5.2 AAS Instruction

> **Book page:** 41

**Study focus:** Legacy 32-bit x86 adjust instructions used with ASCII or unpacked decimal arithmetic.

**Concepts to connect:**
- [[AAA AAS AAM AAD#^what-is-it|AAA AAS AAM AAD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**My notes:**

- 

### 7.5.3 AAM Instruction

> **Book page:** 42

**Study focus:** Legacy 32-bit x86 adjust instructions used with ASCII or unpacked decimal arithmetic.

**Concepts to connect:**
- [[AAA AAS AAM AAD#^what-is-it|AAA AAS AAM AAD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**My notes:**

- 

### 7.5.4 AAD Instruction

> **Book page:** 42

**Study focus:** Legacy 32-bit x86 adjust instructions used with ASCII or unpacked decimal arithmetic.

**Concepts to connect:**
- [[AAA AAS AAM AAD#^what-is-it|AAA AAS AAM AAD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]

**My notes:**

- 

## 7.6 Packed Decimal Arithmetic

> **Book page:** 43

**Study focus:** Binary-Coded Decimal stores each decimal digit using binary patterns.

**Concepts to connect:**
- [[BCD#^what-is-it|BCD]]
- [[ASCII Decimal Arithmetic#^what-is-it|ASCII Decimal Arithmetic]]
- [[Packed Decimal Arithmetic#^what-is-it|Packed Decimal Arithmetic]]
- [[ADD#^what-is-it|ADD]]
- [[SUB#^what-is-it|SUB]]

**Database / project connection:**
- [[SQL Integer Types]]

> [!example] Examples
> Open [[ADD]] for Assembly/C++/Python/Go / PostgreSQL examples.

**My notes:**

- 

### 7.6.1 DAA Instruction

> **Book page:** 43

**Study focus:** Legacy 32-bit x86 adjust instructions used after packed-decimal addition or subtraction.

**Concepts to connect:**
- [[DAA and DAS#^what-is-it|DAA and DAS]]
- [[Packed Decimal Arithmetic#^what-is-it|Packed Decimal Arithmetic]]

**My notes:**

- 

### 7.6.2 DAS Instruction

> **Book page:** 45

**Study focus:** Legacy 32-bit x86 adjust instructions used after packed-decimal addition or subtraction.

**Concepts to connect:**
- [[DAA and DAS#^what-is-it|DAA and DAS]]
- [[Packed Decimal Arithmetic#^what-is-it|Packed Decimal Arithmetic]]

**My notes:**

- 

## 7.7 Chapter Summary

> **Book page:** 45

**Study focus:** A low-level programming language that uses readable instruction names to work close to the processor and hardware.

**Concepts to connect:**
- [[Assembly Language#^what-is-it|Assembly Language]]

> [!example] Examples
> Open [[Assembly Language]] for Assembly/C++/Python/Go examples.

**My notes:**

- 

## 7.8 Key Terms

> **Book page:** 46

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
