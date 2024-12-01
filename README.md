# WHACK-A-MOLE --- DLD Project Report  

**WHACK A MOLE - DLD** is an interactive game designed to enhance understanding of Digital Logic Design principles through hands-on implementation. This report outlines the components used, the design process, and the overall functionality of the game.  

## Table of Contents  
- [Project Overview](#project-overview)  
- [Components Used](#components-used)  
- [Circuit Design](#circuit-design)  
- [Implementation Details](#implementation-details)  
- [Testing and Debugging](#testing-and-debugging)  
- [Conclusion](#conclusion)  
- [License](#license)  

## Project Overview  
The Whack-a-Mole game simulates a carnival-style game where players score points by hitting randomly flashing moles (represented by LEDs) using push buttons. The game includes features such as a scoring system, a timer, and sound effects to enhance user interaction.  

## Components Used  
The following components were utilized in the project:  

1. **555 Timer IC** (2 units)  
2. **Resistors**:  
   - 10k ohm (3 units)  
   - 1k ohm (2 units)  
   - 100k ohm (1 unit)  
3. **Capacitors**:  
   - 1nF (1 unit)  
   - 100mF (1 unit)  
   - 80mF (1 unit)  
4. **NAND based D-Latch** (1 unit)  
5. **4013 D-Flip Flop** (2 units)  
6. **Up/Down Counter IC (4510)** (4 units)  
7. **BCD to 7-Segment Display** (4 units)  
8. **Decoder/Display Driver (7447)** (1 unit)  
9. **NOT Gates** (4 units)  
10. **Push Buttons** (12 units; logic toggle used in Proteus)  
11. **LEDs** (11 units)  
12. **74LS112 JK-Flip Flop** (3 units)  
13. **Decoder IC (74HC238)** (1 unit)  
14. **AND Gates** (3 units)  
15. **NOR Gates** (2 units)  
16. **XNOR Gate** (1 unit)  
17. **OR Gates** (4 units)  
18. **Battery** (5V output)  
19. **Buzzer**  
20. **Breadboard** (5 pcs)  

## Circuit Design  
The circuit design integrates various digital logic components to create the functionality of the game. The LEDs represent the moles, and the push buttons allow players to score points. The timer and scoring logic are managed using flip-flops and counters, while the display driver shows the score.  

## Implementation Details  
The implementation involves:  
- Assembling the circuit on a breadboard.  
- Connecting the components according to the designed schematic.  
- Programming the logic for mole activation, scoring, and timing using the 555 timer and flip-flops.  

## Testing and Debugging  
Testing was conducted to ensure that:  
- LEDs flashed randomly as intended.  
- The scoring system correctly registered hits and misses.  
- The timer functioned properly, ending the game after 30 seconds.  
- The buzzer activated at the end of the game.  

Debugging was performed during lab sessions, allowing for iterative improvements and adjustments to the circuit.  

## Conclusion  
The Whack-a-Mole project successfully demonstrates the principles of Digital Logic Design through an engaging and interactive game. The use of various digital components provided a comprehensive learning experience in circuit design and implementation.  

## License  
This project report is licensed under the MIT License. See the LICENSE file for more information.  

---  

This `README.md` serves as a comprehensive report for your project submission. Feel free to modify any sections to better fit your specific experiences or findings during the project. If you need further assistance or adjustments, just let me know!
