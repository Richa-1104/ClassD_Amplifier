# ClassD_Amplifier

A simple **Class-D audio amplifier** built with **555 timer, LM358 op-amp, MOSFET, and LC filter**, designed on PCB with minimal components.

---

## Overview
Class-D amplifiers use **PWM (Pulse Width Modulation)** to amplify audio with very high efficiency (>90%).  
This project demonstrates how to build a basic Class-D amplifier without using any dedicated IC.


## 🔧 Components
| Component   | Value/Part No. | Quantity |
|-------------|----------------|----------|
| NE555       | Timer IC       | 1 |
| LM358       | Dual Op-Amp    | 1 |
| MOSFET      | IRF540N        | 1 |
| Inductor    | 100 µH, 3 A    | 1 |
| Capacitors  | 1 µF, 470 nF, 470 µF | several |
| Resistors   | 100k, 10k, etc | several |

---

## How to Use
1. Connect audio input from phone/laptop (3.5 mm jack).  
2. Power with **12 V DC, 2 A**.  
3. Connect 8Ω speaker (up to 10 W).  
4. Play audio → amplified output!  

---

## Repository Contents
- `/schematic` → circuit diagrams   
- `/images` → project photos  
- `/docs` → datasheets  

---

## Results
- Clear audio with good loudness  
- Very low heat due to high efficiency  
- Simple design → great for beginners  

---

## 🔮 Future Improvements
- Use a faster comparator (LM311)  
- Add heatsink for high power  
- Use ferrite core inductor for better sound quality  
