# 📝 Cheat Sheet: Instruction Set Architecture & Arithmetic/Logic Instructions

## Instruction Set Architecture (ISA)

-   **Defines** processor operation through machine instructions.
-   **Machine Instruction Elements**: Opcode, Source Operand, Result
    Operand, Next Instruction Reference.
-   **Categories**:
    -   Data Processing (Arithmetic/Logic)\
    -   Data Storage (Registers/Memory)\
    -   Data Movement (I/O)\
    -   Control (Branch/Test)

## Data Transfer

-   **Specs**: Source, Destination, Length, Addressing mode.\
-   **x86**: `MOV`, `XCHG`, `PUSH`, `POP`\
-   **IBM ESA/390**: `L`, `LH`, `LD`, `ST`, `STH`

## Data Manipulation

-   Conversion instructions (e.g., `TR` -- Translate code sets).

## Input/Output (I/O)

-   **Methods**:
    1.  Programmed I/O (CPU controls)\
    2.  Interrupt-Driven I/O (CPU works until interrupt)\
    3.  DMA (Direct Memory ↔ Device)\
-   **x86**: `IN`, `INS`, `OUT`, `OUTS`

## Control Operations

-   **Privileged**: System control (registers, protection keys).\
-   **Transfer of Control**: `CALL`, `RET`, `JMP`, `Jcc`, `NOP`, `HLT`,
    `WAIT`, `INT`

## Intel x86 ISA

-   **Procedural**: `CALL`, `ENTER`, `LEAVE`, `RET`\
-   **Memory Management**: Segmentation (OS only).\
-   **Flags/Conditions**: Used in branches.

## ARM ISA

-   **Load/Store**: Only memory ops.\
-   **Branch**: Conditional + subroutine.\
-   **Data Processing**: `AND`, `OR`, `XOR`, Add/Sub, Compare.\
-   **Multiply**: Word/Halfword.\
-   **Parallel Ops**: Image processing.\
-   **Extended**: Data unpack/extend.\
-   **Status Register Access**.

## Arithmetic Instructions

-   **Basic**: `ADD`, `SUB`, `MUL`, `IMUL`, `DIV`, `IDIV`.\
-   **Single Operand**: `ABS`, `NEG`, `INC`, `DEC`.\
-   **Comparison**: `CMP` (sets flags).

## Logic & Shift Instructions

-   **Logic**: `NOT`, `AND`, `OR`, `XOR`, `TEST`.\
-   **Shift/Rotate**:
    -   Logical: Insert 0s\
    -   Arithmetic: Preserve sign\
    -   Rotate: Wraparound\
-   **x86 Examples**: `SAL`, `SAR`, `SHR`, `ROL`, `ROR`, `RCL`, `RCR`

------------------------------------------------------------------------

📚 **References**\
- Stallings, W. (2019). *Computer Organization and Architecture*\
- Ledin, J. (2020). *Modern Computer Architecture and Organization*
