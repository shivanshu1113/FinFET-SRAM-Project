# CMOS Technology Analysis (NMOS Characterization)

## 📌 Overview

This project explores NMOS transistor behavior across three technology nodes: **90nm, 45nm, and 22nm** using Cadence Virtuoso. The aim is to understand how technology scaling affects device performance.

## 🎯 Objective

* Analyze **Id–VGS characteristics**
* Extract key parameters:

  * Threshold Voltage (**Vth**)
  * Maximum Drain Current (**Idmax**)
  * Transconductance (**gm**)

## ⚙️ Methodology

DC simulations were performed by sweeping gate voltage.

* **Vth** → Constant current method *(Id = 1µA × W/L)*
* **Idmax** → Maximum current at highest VGS
* **gm** → Slope (dId/dVGS) or OP analysis

## 📊 Insight

As technology scales from 90nm → 22nm:

* **gm increases** (better performance)
* **Id characteristics improve**
* **Vth remains nearly constant**

## 🛠️ Tools Used

* Cadence Virtuoso
* Spectre Simulator
* GPDK / PTM Models

---

This project provides practical understanding of MOSFET scaling and parameter extraction using industry-standard tools.
