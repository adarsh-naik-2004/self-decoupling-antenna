# Self-Decoupling Tri-Port Antenna for 5G Smartphone MIMO Systems

A compact self-decoupling tri-port antenna design for 5G smartphone applications, enabling high-performance MIMO systems with minimal mutual coupling. This project includes simulation files, results, and documentation for a 12×12 MIMO antenna array.

---

## 📑 Project Description
This work proposes a **self-decoupling tri-port antenna** that utilizes **mode cancellation** and **active reflection coefficient theory** to achieve high isolation between ports without additional decoupling structures. The antenna operates in the 3.4–3.6 GHz band, targeting 5G smartphone applications. Key achievements include:
- **High isolation (>11 dB)** between ports.
- **Low envelope correlation coefficient (ECC < 0.14)**.
- **Total efficiency** ranging from **59.6% to 88.6%**.
- Compact 12×12 MIMO system integration.

The design is validated through CST Microwave Studio simulations and experimental measurements.

---

## 🚀 Features
- **Tri-port antenna** with shared radiator.
- **Self-decoupling mechanism** using symmetrical U-shaped structures.
- **Multi-band functionality** and broad impedance bandwidth.
- **12×12 MIMO system** for enhanced channel capacity.
- Detailed performance analysis of S/Y/Z parameters, VSWR, and surface currents.

---


## 🔧 Installation & Usage
### Prerequisites
- **CST Microwave Studio** (for simulating `.cst` files).
- Microsoft Excel or equivalent (to view `.xlsx` results).

### Steps to Reproduce
1. **Simulations**:
   - Open `Decouple.cst` in CST Microwave Studio.
   - Run simulations to analyze S/Y/Z parameters, surface currents, and efficiency.
2. **Results**:
   - View pre-computed results in the `Results/` folder.
   - Compare simulated and measured data (e.g., reflection coefficients in `Reflection Coefficients.xlsx`).

---

## 📊 Key Results
1. **S-Parameters**:
   - Port 1: 10 dB impedance bandwidth exceeding 3.4–3.6 GHz.
   - Ports 2 & 3: ~270–280 MHz bandwidth.
   - Isolation >11 dB across all ports.
2. **Diversity Performance**:
   - ECC < 0.14 (excellent diversity).
3. **Total Efficiency**: 59.6–88.6%.
4. **12×12 MIMO System**:
   - High isolation and low correlation confirmed through measurements.

---

## 📚 References
1. Yang et al., "Tri-Port Antenna With Shared Radiator and Self-Decoupling Characteristic for 5G Smartphone Application," *IEEE Transactions on Antennas and Propagation*, 2022.
2. Ngo et al., "Energy and Spectral Efficiency of Very Large Multiuser MIMO Systems," *IEEE Trans. Commun.*, 2013.

---
