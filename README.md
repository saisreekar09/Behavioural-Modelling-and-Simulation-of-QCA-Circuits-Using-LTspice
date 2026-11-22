# Behavioural-Modelling-and-Simulation-of-QCA-Circuits-Using-LTspice
Behavioural modelling and simulation of Quantum-Dot Cellular Automata (QCA) combinational logic circuits using LTspice. Implements Half Subtractor, 3-Input XOR Gate, Full Adder, and 2:1 Multiplexer using behavioural voltage sources and capacitors, with transient waveform analysis to verify logical functionality.
# Behavioural Modelling and Simulation of QCA Circuits Using LTspice

## Overview

This project focuses on the behavioural modelling and simulation of **Quantum-Dot Cellular Automata (QCA)** combinational logic circuits using LTspice.

QCA is an emerging nanoscale computing technology in which binary information is represented through the polarization of electrons inside quantum-dot cells. Unlike conventional CMOS technology, QCA uses electrostatic interactions between neighbouring cells to transfer information.

In this project, an electrical behavioural equivalent model is developed using LTspice. Behavioural voltage sources and capacitors are used to represent logical operations, signal propagation, and transient characteristics.

## Circuits Implemented

The following four combinational circuits are modelled and simulated:

| S.No | Circuit | Function |
|---|---|---|
| 1 | Half Subtractor | Performs single-bit subtraction |
| 2 | Three-Input XOR Gate | Produces 1 for an odd number of HIGH inputs |
| 3 | Full Adder | Performs addition of three single-bit inputs |
| 4 | 2:1 Multiplexer | Selects one of two inputs based on a select signal |

## Modelling Approach

The QCA circuits are represented using an electrical behavioural equivalent model.

- **Behavioural Voltage Sources:** Implement mathematical expressions and logical operations.
- **Capacitors:** Provide electrical charge storage and influence transient response.
- **Voltage Representation:** Positive voltage represents logic 1, while negative voltage represents logic 0.

The transient analysis in LTspice is used to observe the input and output waveforms and verify the logical functionality of each circuit.

## Software Used

- LTspice
- Behavioural Voltage Sources
- Capacitive Elements
- Transient Simulation

## Simulation Results

The simulation waveforms are analysed to verify the expected input-output relationships.

- **Half Subtractor:** Verifies Difference and Borrow outputs.
- **Three-Input XOR:** Verifies odd-parity functionality.
- **Full Adder:** Verifies Sum and Carry-out outputs.
- **2:1 Multiplexer:** Verifies input selection based on the select signal.

The simulated outputs are compared with the corresponding truth tables to confirm correct logical operation.

## Project Structure

```text
QCA-LTspice-Behavioural-Modelling/
│
├── Half_Subtractor/
│   ├── Circuit schematic
│   └── Simulation results
│
├── Three_Input_XOR/
│   ├── Circuit schematic
│   └── Simulation results
│
├── Full_Adder/
│   ├── Circuit schematic
│   └── Simulation results
│
├── 2_to_1_Multiplexer/
│   ├── Circuit schematic
│   └── Simulation results
│
└── README.md
```

## Important Note

This project uses an electrical behavioural equivalent model of QCA. It does not directly simulate the quantum-mechanical movement of electrons inside physical QCA cells. The voltage waveforms represent the logical state relationships and transient behaviour of the model.

## Conclusion

This project demonstrates the behavioural implementation and simulation of four QCA-based combinational circuits using LTspice. The transient simulation results verify the expected logical functionality and demonstrate the applicability of electrical behavioural modelling for studying QCA circuit designs.

**Developed by:** Suru SaiSreekar  
**Department:** Electronics and Communication Engineering  
**Institution:** Indian Institute of Information Technology Sri City
