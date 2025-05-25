# Low-Power-ALU-for-RISC-V-ISA
This repository contains Verilog HDL code, simulation files, and power analysis reports for three ALU architectures designed for low-power embedded applications

## 📌 Description

This repository explores three different ALU architectures:

| ALU Type           | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| 🔸 Normal ALU       | Basic architecture with no optimizations                                    |
| ♻️ Resource-Sharing ALU | Shared logic components to minimize redundancy                              |
| 🔐 Latch-Based ALU   | Most efficient design using controlled latches to reduce power consumption |

---

## 🎯 Objectives

- ✅ Design 4-bit ALU architectures in Verilog HDL
- ✅ Evaluate power efficiency of each design
- ✅ Compare dynamic and static power dissipation
- ✅ Integrate latch-based control techniques
- ✅ Simulate functionality using testbenches
- ✅ Analyze thermal and switching activity using Quartus II

---

## 🔧 Tools & Technologies

| Tool              | Purpose                    |
|------------------|----------------------------|
| Verilog           | ALU Design Implementation |
| Icarus Verilog    | Functional Simulation     |
| Quartus II        | Power Analysis            |
| VS Code           | HDL Development           |

---

## 🧪 Block Diagram

##Customised Full Adder
![image](https://github.com/user-attachments/assets/3bbcdde6-a3b8-4aab-b4c4-c97cbcd0db1e)
 ##Latch-Based Technique
![image](https://github.com/user-attachments/assets/9511ff5c-dc89-4462-8332-dc0aa00ab597)
 ##Resource-Sharing Technique
![image](https://github.com/user-attachments/assets/e0f94f42-8374-48dc-87bc-ea93f549c46e)
##Proposed Method
![image](https://github.com/user-attachments/assets/0c68d9b7-135c-4a0c-8fbc-914e2b0f40fe)


### 🔋 Power Consumption (Thermal)

| ALU Type           | Thermal Power (mW) | Power Reduction |
|--------------------|-------------------|-----------------|
| Normal ALU         | 104.53            | -               |
| Resource-Sharing   | 104.40            | ↓ 0.13 mW       |
| Latch-Based ALU    | 64.93             | ↓ 38.60 mW ✅    |

> Latch-based design shows the highest efficiency by controlling enable signals and reducing switching transitions.

## 🧪 Simulation Results

##Power Analysis
![image](https://github.com/user-attachments/assets/f741005d-3959-4628-b1b3-36b780833e61)
##Proposed ALU
![image](https://github.com/user-attachments/assets/174ed697-62eb-4250-a38e-435b825b6c97)


