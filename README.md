# Numerical Circuit Simulation and Modified Nodal Analysis using LTspice ⚡

This project presents a comprehensive investigation of circuit behavior using LTspice simulation and analytical modeling techniques.

The work focuses on time-domain analysis of resonant circuits and numerical solution of linear networks using Modified Nodal Analysis (MNA). The project integrates theoretical derivation, circuit simulation, and numerical verification to demonstrate how modern circuit simulators compute electrical system states.

---

## 🖥️ Execution Environment

This project requires the following environment:

### Operating System

- Windows
- macOS
- Linux

### Simulation Software

- LTspice XVII or later

Download:

https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html

---

## ▶️ How to Run Simulation

### Step 1: Open Simulation File

Open LTspice.

Click:

File → Open

Select:

```
*.asc
```

---

### Step 2: Run Simulation

Click:

Run Button

The simulator will generate:

- Voltage waveform
- Current waveform
- Operating point analysis

---

### Step 3: View Results

Simulation results can be observed in:

```
*.log
```

---

## 🎯 Project Objectives

This project investigates two fundamental problems in circuit simulation:

### Parallel LC Resonant Circuit Analysis

The project simulates the dynamic response of an ideal LC resonant circuit and verifies its theoretical solution.

As shown in the experimental report, the voltage and current exhibit sinusoidal oscillations with a 90° phase difference and a period of approximately 0.99 seconds. :contentReference[oaicite:0]{index=0}

This confirms the analytical solution derived from the governing differential equation.

---

### Modified Nodal Analysis (MNA) Modeling

The project constructs the SPICE netlist of a linear circuit and derives its MNA matrix representation.

Simulation results demonstrate:

Node voltages:

- N001 = 2 V
- N002 = 7.78 V
- N003 = 31.11 V
- N004 = 7.78 V

Controlling current:

- 7.78 mA

These results match the analytical solution exactly. :contentReference[oaicite:1]{index=1}

This verifies the correctness of the SPICE numerical computation process.

---

## ✨ Project Highlights

### Physics-Based Circuit Modeling

The project derives circuit dynamic equations directly from physical laws:

- Kirchhoff’s Laws
- Capacitor constitutive relations
- Inductor constitutive relations

This establishes a direct mapping between physical system behavior and electrical signals.

---

### Numerical Simulation using Industry Tool

The project uses LTspice, an industry-standard circuit simulator.

This demonstrates:

- Time-domain transient simulation
- DC operating point analysis
- Numerical state solving

---

### SPICE Netlist Construction

The circuit is represented as a SPICE netlist, which is the internal representation used by simulators.

This allows the circuit to be solved using numerical linear algebra methods.

---

### Modified Nodal Analysis Verification

The project derives the MNA matrix analytically and compares it with simulator-generated results.

This validates:

- Mathematical model correctness
- Simulator computation accuracy

---

### Signal-to-State Mapping

The project demonstrates how internal circuit states such as:

- Node voltage
- Branch current

can be reconstructed from simulation.

This represents the fundamental principle of modern electronic sensing and circuit analysis.

---

## 📁 Repository Structure

```
LTspice-Circuit-Simulation-MNA
│
├── README.md
│
├── report
│   └── Report.pdf
│
├── simulation
│   ├── circuit.asc
│   ├── circuit.log
│
├── netlist
│   └── circuit.net
```

---

## 🚀 Summary

This project demonstrates a complete workflow for circuit analysis, including:

- Physical modeling
- Differential equation derivation
- Numerical simulation
- SPICE netlist construction
- Matrix-based state solving

The project illustrates how circuit simulators compute electrical system states from mathematical models.

This work reflects fundamental principles used in:

- Microelectronics
- Integrated circuit design
- Sensor systems
- Analog circuit modeling
- Hardware system analysis

---
