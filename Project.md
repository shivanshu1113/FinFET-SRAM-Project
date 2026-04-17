# 🚀 FinFET-Based 6T SRAM Design and Analysis (22nm Technology)

## 📌 Overview

This project presents a detailed design and simulation-based analysis of a **6-Transistor (6T) SRAM cell** across three semiconductor technology nodes: **90nm, 45nm, and 22nm**.

The work focuses on understanding the impact of **technology scaling** and demonstrating how **FinFET architecture at 22nm** overcomes the limitations of traditional planar CMOS.

---

## 🎯 Objectives

* Characterize **NMOS and PMOS** devices across multiple technology nodes
* Design and analyze a **CMOS inverter** using VTC curves
* Implement a **6T SRAM cell** with proper transistor sizing
* Evaluate key performance metrics:

  * Static Noise Margin (SNM)
  * Power Consumption
  * Propagation Delay
* Compare **planar CMOS vs FinFET performance**

---

## 🧠 Key Concepts Covered

* FinFET vs Planar MOSFET
* Short Channel Effects (SCE) & DIBL
* SRAM Read/Write Stability
* Voltage Transfer Characteristics (VTC)
* Butterfly Curve for SNM

---

## ⚙️ Tools & Technologies

* **Cadence Virtuoso** – Schematic Design
* **Spectre Simulator** – DC & Transient Analysis
* **Predictive Technology Models (PTM)** – Device modeling

---

## 🏗️ Project Workflow

1. **MOSFET Characterization**

   * Id–Vgs and Id–Vds analysis
   * Threshold voltage and leakage behavior

2. **CMOS Inverter Design**

   * VTC extraction
   * Noise margin evaluation

3. **6T SRAM Cell Design**

   * Cross-coupled inverter structure
   * Access transistor integration

4. **Simulation Scenarios**

   * Hold Operation
   * Read Operation
   * Write Operation

5. **Performance Evaluation**

   * SNM using butterfly curves
   * Power and delay measurements

---

## 📊 Key Results

### 🔹 Static Noise Margin (SNM)

| Technology | Hold SNM | Read SNM | Write SNM |
| ---------- | -------- | -------- | --------- |
| 90 nm      | 332 mV   | 236 mV   | 452 mV    |
| 45 nm      | 277 mV   | 194 mV   | 392 mV    |
| 22 nm      | 202 mV   | 110 mV   | 354 mV    |

### 🔹 Power Consumption

| Technology | Static Power | Dynamic Power | Total Power |
| ---------- | ------------ | ------------- | ----------- |
| 90 nm      | 88.6 nW      | 10.4 µW       | 10.48 µW    |
| 45 nm      | 47.1 nW      | 13.3 µW       | 13.34 µW    |
| 22 nm      | 8.3 nW       | 11.8 µW       | 11.80 µW    |

### 🔹 Propagation Delay

| Technology | Read Delay | Write Delay | Access Time |
| ---------- | ---------- | ----------- | ----------- |
| 90 nm      | 166 ps     | 188 ps      | 175 ps      |
| 45 nm      | 103 ps     | 133 ps      | 142 ps      |
| 22 nm      | 68 ps      | 94 ps       | 81 ps       |

---

## 📈 Insights

* Scaling reduces **delay and dynamic power**, improving speed
* Planar CMOS suffers from **increased leakage at smaller nodes**
* **FinFET at 22nm significantly reduces leakage** and improves control
* Trade-off observed between **stability (SNM)** and **performance**

---

## 🔥 Why FinFET?

FinFET technology introduces a **3D gate structure** that provides:

* Better electrostatic control
* Lower leakage current
* Improved scalability below 45nm
* Enhanced performance-per-watt

---


## 🚧 Future Work

* Extend design to **8T SRAM** for better read stability
* Perform **layout design (DRC & LVS)**
* Conduct **Monte Carlo analysis** for process variations
* Explore **sub-10nm FinFET technologies (14nm, 7nm)**

---

## 👨‍💻 Authors

* Shivanshu Jha

---

## 📚 References

* IEEE Transactions on VLSI Systems
* IEEE Access
* Predictive Technology Models (ASU)

---

## ⭐ Final Note

This project demonstrates how **advanced device architectures like FinFET are essential for sustaining Moore’s Law** and enabling next-generation low-power, high-performance memory systems.

