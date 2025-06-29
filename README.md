# MCOTM-N: Newton-Enhanced Mobility-Aware Computation Offloading and Task Migration for IIoT

This repository presents **MCOTM-N**, an enhanced version of the original MCOTM framework, integrating **Newton’s Interpolation** for improved trajectory prediction in **Industrial Internet of Things (IIoT)** environments. This adaptation offers better **numerical stability** and **computational efficiency**, crucial for real-time mobile edge computing (MEC).

---

## Overview

The original MCOTM relied on Lagrange interpolation for trajectory prediction. This version replaces it with **Newton's Forward Difference Method**, which provides:

- Reduced computational cost
- Enhanced numerical stability for longer prediction windows
- Better adaptability to dynamic IIoT environments

---

## Key Contributions

- **Trajectory Prediction** using Newton’s interpolation instead of Lagrange’s
- **Resource Forecasting** via LSTM for edge server load prediction
- **Decision Making** using Deep Deterministic Policy Gradient (DDPG)
- Full simulation environment for mobile devices and edge nodes

---

## Performance Improvements

According to experimental evaluation:

- **7.76% reduction** in mean task turnaround time
- **6.96% decrease** in energy consumption
- **4.55% drop** in migration rate

---

## Requirements

Install required dependencies:

```bash
pip install tensorflow>=2.0
pip install numpy
pip install pandas
pip install scipy
pip install scikit-learn
pip install matplotlib
