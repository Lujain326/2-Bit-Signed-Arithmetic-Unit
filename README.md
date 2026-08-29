# 2-Bit Signed Arithmetic Unit

A **2-bit signed arithmetic unit** designed and fully implemented in **Logisim Evolution**. The circuit performs arithmetic operations on two 2-bit signed numbers using **2's complement representation** and selectable control inputs.

This project was developed as part of a **Digital Logic Design** project to practice building and connecting digital logic components into a functional arithmetic circuit.

---

## ✨ Features

- 2-bit signed arithmetic
- Addition
- Subtraction
- Multiplication
- Operation selection using control inputs
- Signed number representation using **2's complement**
- Combinational digital logic design
- Fully designed and simulated in **Logisim Evolution**

---

## 🔢 Supported Operations

The arithmetic operation is selected using a 2-bit control input:

| Selector | Operation |
|:---:|---|
| `00` | Not used |
| `01` | Addition |
| `10` | Subtraction |
| `11` | Multiplication |

---

## 🔢 Signed Number Representation

The circuit uses **2's complement representation** for signed 2-bit numbers.

This allows the arithmetic unit to represent both positive and negative values within the available 2-bit range.

---

## ⚙️ How It Works

The arithmetic unit receives two 2-bit signed inputs.

The control input determines which arithmetic operation is selected. The circuit then routes the appropriate operation to the output using combinational logic.

The design combines multiple digital components, including **full adders, multiplexers, and logic gates**, to implement the required arithmetic operations.

The resulting output is displayed through the circuit's output components in Logisim Evolution.

---

## 🔧 Main Components

- Full Adders
- Multiplexers
- Logic Gates
- Input Switches
- Output Indicators
- Seven-Segment Display Components

---

## 👩‍💻 My Contribution

I **personally implemented the complete arithmetic unit circuit in Logisim Evolution**, including the digital logic components, their connections, and the overall circuit design.

I also used Logisim Evolution to simulate and verify the circuit's behavior.

---

## 🧠 Concepts Demonstrated

- Digital Logic Design
- 2's Complement Representation
- Signed Binary Arithmetic
- Combinational Circuit Design
- Arithmetic Operation Selection
- Multiplexers
- Full Adders
- Logic Gates
- Connecting Digital Logic Components
- Circuit Simulation

---

## 🛠️ Tool Used

- **Logisim Evolution**

---

## 📁 Project Structure

```text
2-Bit-Signed-Arithmetic-Unit/
├── README.md
└── arithmetic_unit.circ
