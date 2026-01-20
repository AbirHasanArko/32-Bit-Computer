# 🖥️ 32-bit Computer Architecture

---

A complete **32-bit computer system** designed and implemented using **Logisim**, developed as part of the **Computer Architecture Laboratory (CSE 2114)** course at **Khulna University of Engineering & Technology (KUET)**.

This project demonstrates a full datapath and control unit implementation, including a **32-bit ALU**, **Booth’s Multiplier**, **register set**, **RAM**, and a **hardwired control unit**.



---

## 🧠 System Overview

### Major Components
- 32-bit Arithmetic Logic Unit (ALU)
- 32-bit Booth’s Multiplier
- Register Set
- Control Unit
- 32-bit Word RAM
- Complete Instruction Datapath

---

## ⚙️ 32-bit ALU

### Supported Operations
- 32-bit Bitwise **AND**
- 32-bit Bitwise **OR**
- 32-bit **Addition & Subtraction**

### ALU Features
- Carry Lookahead Adder (CLA) architecture
- 2’s complement subtraction
- Status flags:
  - Carry
  - Overflow
  - Zero
  - Negative

---

## ✖️ 32-bit Booth’s Multiplier

- Implements **Booth’s Algorithm** for signed multiplication
- Includes:
  - Sequence Generator
  - Arithmetic shift logic
  - Booth encoding control
- Efficient for positive and negative operands

---

## 📦 Register Set

| Register | Size | Description |
|--------|------|------------|
| ACC | 32-bit | Accumulator |
| IR | 4-bit | Instruction Register |
| PC | 5-bit | Program Counter |
| MAR | 5-bit | Memory Address Register |
| MBR | 32-bit | Memory Buffer Register |

---

## 🧩 Control Unit

The control unit manages instruction fetch, decode, and execute cycles.

### Supported Instructions

| Opcode | Instruction | Description |
|------|------------|------------|
| 0 | AND | Bitwise AND |
| 1 | ADD | Addition |
| 2 | STO | Store to memory |
| 3 | ISZ | Increment & Skip if Zero |
| 4 | BSB | Branch and Save |
| 5 | BUN | Branch Unconditionally |
| 6 | LOD | Load |
| 7 | HLT | Halt |
| 8 | ROL | Rotate Left |
| 9 | DEC | Decrement |

---

## 🧠 Memory Unit

- Word size: **32-bit**
- Supports read and write operations
- Integrated with MAR and MBR
- Controlled by the control unit

---

## 🖼️ Project Diagrams

The project includes:
- 32-bit ALU schematic
- Booth’s Multiplier schematic
- Register block diagrams
- Control unit layout
- Complete 32-bit computer top view

> Open `.circ` files using **Logisim Evolution** for proper visualization.

---

## 🛠️ Tools & Technologies

- Logisim / Logisim Evolution
- Digital Logic Design
- Computer Architecture Concepts

---

## 🚀 How to Run

1. Install **Logisim Evolution**
2. Open the main `.circ` file
3. Load memory with instructions (if required)
4. Start simulation
5. Observe register values and outputs

---

## 📜 License

This project is for **academic and educational purposes**.  
You may use, modify, and extend it with proper credit.

---

## 👨‍💻 Author
- **Name:** Abir Hasan Arko  
- **Roll:** 2207053
- Department of Computer Science and Engineering
- Khulna University of Engineering & Technoloy, Khulna, BD

---
