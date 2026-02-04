# 4-Bit Arithmetic Logic Unit (ALU)

## 📌 Overview
This project presents the design and implementation of a **4-bit Arithmetic Logic Unit (ALU)** using basic digital logic components.  
The ALU performs both **arithmetic** and **logical** operations and is implemented using **TTL ICs**, simulated in **Logisim**, and physically built on a **breadboard**.

The project was developed as part of a Digital Logic course under the supervision of **Prof. Ahmed Shalaby**.

---

## 🎯 Project Objectives
- Understand the internal structure of an ALU
- Implement arithmetic and logic operations using logic gate ICs
- Design and simulate circuits using Logisim and Proteus
- Build and test the complete ALU on a breadboard
- Bridge theoretical digital logic concepts with real hardware implementation

---

## ⚙️ Supported Operations

### 🔢 Arithmetic Operations
- Addition (A + B)
- Subtraction (A − B) using 2’s complement
- Increment / Decrement
- Multiplication using partial products and full adders

### 🔍 Logical Operations
- AND
- OR
- NOT
- NAND
- NOR
- XOR
- XNOR
- Bitwise complement
- Data transfer

---

## 🧠 Control Mechanism
A **Demultiplexer (DMUX)** is used to select the desired operation based on control signals (S0–S3).  
Only one operation is enabled at a time, ensuring efficient hardware utilization.

---

## 🧩 Main Components Used

### Logic ICs
- 7408 – AND
- 7432 – OR
- 7400 – NAND
- 7402 – NOR
- 4070 – XOR
- 74266 – XNOR

### Arithmetic & Storage
- 74LS83 – Full Adder
- 74LS195 – 5-Bit Register
- CD74HC154 – Demultiplexer
- Hexadecimal 7-Segment Display

---

## 🛠 Tools & Technologies
- **Logisim** – Circuit simulation
- **Proteus** – Pre-hardware verification
- **Breadboard** – Physical implementation
- **TTL Logic ICs**
- **LEDs & 7-Segment Displays**

---

## 🖼 Project Implementation

### 🔹 Simulation
- Full adder and 4-bit adder circuits
- Logic unit simulation
- Complete ALU simulation with DMUX control

### 🔹 Hardware
- Breadboard implementation of:
  - Arithmetic unit
  - Logic unit
  - Multiplication circuit
  - ALU main circuit

Photos of the breadboard and circuit layouts are included in the `/images` folder.

---

## 📄 Project Report
The full technical report with:
- Theory
- Truth tables
- Circuit diagrams
- Design explanation
- Results and conclusion


