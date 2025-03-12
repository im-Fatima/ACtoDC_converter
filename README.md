# AC to DC Converter PCB

## Overview
This project features a **compact AC to DC converter PCB** designed for converting AC voltage into DC with **rectification, filtering, and indication** mechanisms. The circuit efficiently transforms an **AC input** from a transformer into a **steady DC output** using a **bridge rectifier, capacitor filter, and LED indicator**.

## Circuit Working Principle
1. **AC Input:** The **AC voltage** is supplied via **Terminal Block 1**, sourced from a transformer.
2. **Rectification:** Four **1N4007 diodes** form a **bridge rectifier**, converting the **AC voltage into pulsating DC**.
3. **Filtering:** A **parallel capacitor** smooths the pulsating DC into a **stable DC voltage**.
4. **Discharge Mechanism:** A **parallel resistor** discharges the capacitor to prevent unwanted voltage retention.
5. **Indication:** An **LED with a resistor** acts as a **status indicator**, confirming the circuit's operation.
6. **DC Output:** The filtered **DC voltage is available** at **Terminal Block 2** for use in external circuits.

## Features
- **Compact PCB design** for easy integration.
- **Bridge rectifier using 1N4007 diodes** for efficient AC to DC conversion.
- **Capacitor filtering** for a **smooth and stable** DC output.
- **LED indicator** for circuit status monitoring.
- **Parallel discharge resistor** to ensure proper capacitor operation.
- **Reliable terminal blocks** for AC input and DC output connections.

## Components Used
| Component       | Specification   | Function |
|----------------|----------------|----------|
| **Diodes**     | 1N4007 (x4)     | Bridge rectifier |
| **Capacitor**  | Electrolytic    | DC filtering |
| **Resistor**   | Various values  | Capacitor discharge & LED current limiting |
| **LED**        | Standard        | Power indication |
| **Terminal Blocks** | 2-pin       | AC input & DC output connections |

## Applications
- **Power supply modules** for embedded systems.
- **DC-powered circuits requiring AC transformation.**
- **DIY electronics and prototyping.**

## How to Use
1. **Connect the AC input** (e.g., from a transformer) to **Terminal Block 1**.
2. **Check LED status** to confirm proper operation.
3. **Use the DC output** from **Terminal Block 2** to power your circuit.

## Schematic Diagram
_([https://github.com/im-Fatima/ACtoDC_converter/blob/main/ACtoDC_converter_schematic.png])_



---
Feel free to contribute, suggest improvements, or modify the design based on your requirements!

📌 **Author:** _Otakutronics_

