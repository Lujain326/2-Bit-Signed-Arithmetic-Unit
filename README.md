# 2-Bit Signed Arithmetic Unit

A **2-bit signed arithmetic unit** designed and fully implemented in **Logisim Evolution**. The circuit performs arithmetic operations on two 2-bit signed numbers using **2's complement representation** and selectable control inputs.

This project was developed as part of a **Digital Logic Design** project to practice designing and connecting digital logic components into a functional arithmetic circuit.

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

## 🔢 Operation Selection

The arithmetic operation is selected using the control inputs.

**Important:** `Cin2` must always be set to **`1`** for the circuit to perform the intended operations. Setting `Cin2` to `0` prevents the circuit from producing the expected results.

| Control Input | `Cin2` | Operation |
|:---:|:---:|---|
| `01` | `1` | Addition |
| `10` | `1` | Subtraction |
| `11` | `1` | Multiplication |

---

## 🔢 Signed Number Representation

The circuit uses **2's complement representation** for signed 2-bit numbers.

Using 2's complement allows the arithmetic unit to represent both positive and negative values within the available 2-bit range.

---

## ⚙️ How It Works

The arithmetic unit receives two **2-bit signed inputs**.

The control inputs determine which arithmetic operation is selected. The circuit then uses combinational logic to perform the selected operation and produce the corresponding output.

The design combines several digital logic components, including **full adders, multiplexers, and logic gates**, to implement the required arithmetic operations.

The resulting output is displayed through the circuit's output components in **Logisim Evolution**.

---

## 🔧 Main Components

- Full Adders
- Multiplexers
- Logic Gates
- Input Switches
- Output Indicators
- Seven-Segment Display Components

---

## 🖥️ Logisim Circuit

The complete arithmetic unit was designed and implemented in **Logisim Evolution**.

### Circuit Screenshot

![2-Bit Signed Arithmetic Unit - Logisim Circuit](https://1drv.ms/i/c/210e17635efde1f9/IQA0hcOCGOn7T7mGRQN5RXfbAdDG6iT-LmL7PgshFcZPNJc?e=QtCoP4)

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
- Digital Circuit Integration
- Circuit Simulation and Verification

---

## 🛠️ Tool Used

- **Logisim Evolution**
- **Digital design**

---

## 📁 Project Structure

```text
2-Bit-Signed-Arithmetic-Unit/
├── README.md
└── arithmetic_unit.circ

---

##👩‍💻 Author

Lujain Ayman
Computer Engineering Student
