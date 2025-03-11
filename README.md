# 🎯 WHACK-A-MOLE --- DLD Project Report

**WHACK-A-MOLE - DLD** is an interactive game designed to enhance understanding of Digital Logic Design (DLD) principles through hands-on implementation. This report outlines the components used, the design process, and the overall functionality of the game.

---

## 📖 Table of Contents
- [🎮 Project Overview](#-project-overview)
- [🔧 Components Used](#-components-used)
- [📐 Circuit Design](#-circuit-design)
- [⚙️ Implementation Details](#-implementation-details)
- [🛠️ Testing and Debugging](#-testing-and-debugging)
- [🏆 Conclusion](#-conclusion)
- [📜 License](#-license)

---

## 🎮 Project Overview
The **Whack-a-Mole** game simulates a carnival-style game where players score points by hitting randomly flashing moles (represented by LEDs) using push buttons. The game includes:
- A **scoring system**
- A **timer**
- **Sound effects** to enhance user interaction

---

## 🔧 Components Used
The following components were used to build the circuit:

| Component                     | Quantity |
|--------------------------------|----------|
| **555 Timer IC**              | 2        |
| **Resistors** (10kΩ, 1kΩ, 100kΩ) | 6 total  |
| **Capacitors** (1nF, 100mF, 80mF) | 3 total  |
| **NAND-based D-Latch**        | 1        |
| **4013 D-Flip Flop**          | 2        |
| **Up/Down Counter IC (4510)** | 4        |
| **BCD to 7-Segment Display**  | 4        |
| **Decoder/Display Driver (7447)** | 1    |
| **Logic Gates (NOT, AND, NOR, OR, XNOR)** | Multiple |
| **Push Buttons**              | 12       |
| **LEDs**                      | 11       |
| **74LS112 JK-Flip Flop**      | 3        |
| **Decoder IC (74HC238)**      | 1        |
| **Battery (5V output)**       | 1        |
| **Buzzer**                    | 1        |
| **Breadboards**               | 5        |

---

## 📐 Circuit Design
The circuit design integrates various digital logic components to create the **core functionality** of the game.
- **LEDs represent the moles**
- **Push buttons allow scoring**
- **555 timer and flip-flops control mole activation and scoring logic**
- **A display driver shows the player's score**

> **Diagram**:
<div align=center width="100%">
   <img src="https://github.com/AbdulAHAD968/WHACK-A-MOLE---DLD/blob/main/assets/0.PNG"/>
   <img src="https://github.com/AbdulAHAD968/WHACK-A-MOLE---DLD/blob/main/assets/1.PNG"/>
   <img src="https://github.com/AbdulAHAD968/WHACK-A-MOLE---DLD/blob/main/assets/2.PNG"/>
   <img src="https://github.com/AbdulAHAD968/WHACK-A-MOLE---DLD/blob/main/assets/3.PNG"/>
</div>

---

## ⚙️ Implementation Details
The implementation follows these steps:
1. **Assembling** the circuit on a breadboard.
2. **Connecting** all components as per the schematic.
3. **Programming** the logic for:
   - **Mole activation** (random LED flashes)
   - **Scoring mechanism** (hit detection)
   - **Game timing** (30-second countdown)
   - **End-of-game buzzer activation**

---

## 🛠️ Testing and Debugging
Rigorous testing was conducted to ensure:
✅ LEDs flashed randomly as expected.  
✅ Scoring system correctly registered hits and misses.  
✅ Timer functioned properly, ending the game after **30 seconds**.  
✅ The buzzer activated at the **end of the game**.  

Debugging was performed iteratively during lab sessions to refine the circuit.

---

## 🏆 Conclusion
The **Whack-a-Mole** project successfully demonstrates **Digital Logic Design principles** through an engaging and interactive game. It provided an insightful learning experience in:
- **Circuit design**
- **Flip-flop operations**
- **Counter logic**
- **Real-world implementation of logic gates**

---

## 📜 License
This project report is licensed under the **MIT License**. See the LICENSE file for more information.

---

🚀 **Happy Learning & Keep Innovating!** 🛠️

