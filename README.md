# IEEE 14-Bus System Static & Dynamic Load Flow Analysis

An advanced, cloud-computed power systems engineering framework analyzing grid configurations without requiring local hardware resource provisioning. This repository executes static state verification using a **Newton-Raphson numerical solver** in Python (`PyPSA`) and validates system stability during short-circuit transients using **Simscape Electrical (MATLAB Online)**.

---

## 📁 Repository Configuration Tree
```text
ieee14-load-flow-analysis/
├── python-pypsa/
│   ├── IEEE14_Static_Analysis.ipynb    <-- Cloud-computed PyPSA Solver
│   └── requirements.txt                <-- Static environment dependencies
├── matlab-online/
│   ├── ieee14_dynamic_sim.slx          <-- Simscape transient model
│   └── run_dynamic_analysis.m          <-- Control & plotting script
├── .gitignore
├── LICENSE
└── README.md
