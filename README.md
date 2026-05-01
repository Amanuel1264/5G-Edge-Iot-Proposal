# �� 5G-Edge-IoT Performance Evaluation

## �� Project Title

A Study on the Performance of 5G and Edge Computing Integration in Real-Time IoT Applications

---

## �� Overview

This project investigates how integrating 5G networks with Multi-access Edge Computing (MEC) improves the performance of real-time Internet of Things (IoT) applications.

Traditional cloud-based systems introduce high latency and inefficiencies. This research evaluates whether moving computation closer to devices (edge computing) significantly enhances system performance.

---

## �� Objectives

### General Objective

To evaluate the performance of 5G + Edge Computing for real-time IoT systems.

### Specific Objectives

* Measure latency reduction using edge computing
* Evaluate throughput and Packet Delivery Ratio (PDR)
* Analyze energy consumption in IoT devices
* Study performance under different radio conditions (LOS/NLOS)

---

## �� Simulation Scenarios

The study compares three architectures:

1. 4G + Cloud (Baseline)
2. 5G + Cloud
3. 5G + Edge Computing (MEC)

---

## ⚙️ Tools & Technologies

* ns-3 Simulator (with 5G-LENA module)
* Python

* Pandas (data processing)
* Matplotlib / Seaborn (visualization)
* LaTeX (Overleaf) for documentation
* Git & GitHub for version control
* IEEE DataPort for datasets

---

## �� Evaluation Metrics

The system is evaluated using:

* End-to-End Latency
* Throughput
* Packet Delivery Ratio (PDR)
* Energy Consumption
* Jitter
* Reliability

---

## �� Project Structure

```
5G-Edge-IoT-Proposal/
│
├── docs/                 # LaTeX source files
├── data/                 # Datasets and traces
├── scripts/              # Python analysis scripts
├── results/              # Output graphs and tables
├── figures/              # Images (architecture diagrams)
├── references.bib        # Bibliography file
└── README.md             # Project documentation
```

---

## �� How to Reproduce Results

### 1. Clone Repository

```bash
git clone https://github.com/Amanuel1264/5G-Edge-Iot-Proposal.git
cd 5G-Edge-Iot-Proposal
```

### 2. Setup ns-3 with 5G-LENA

Follow official ns-3 installation steps and ensure:

* 5G-LENA module is installed
* Required dependencies are configured

### 3. Run Simulations

Execute simulation scripts (example):

```bash
./waf --run scratch/your_simulation_file
```

### 4. Analyze Results

Run Python scripts:

```bash
python analysis.py
```

---

## �� Expected Contributions

* Clear comparison of cloud vs edge performance
* Quantified improvements in latency and energy efficiency
* Reproducible simulation framework for future research
* Insights applicable to developing regions like Ethiopia

---

## ⚖️ Ethics & Reproducibility

* No personal data used
* Public datasets only
* All code and configurations are shared
* Simulations include realistic and challenging conditions

---

## �� Project Timeline

| Phase             | Weeks |
| ----------------- | ----- |
| Literature Review | 1–3   |
| Setup & Data Prep | 3–6   |
| Simulation        | 6–11  |
| Analysis          | 10–13 |
| Writing           | 13–15 |

---

## ��‍�� Author

Amanuel Seifu
Computer Science Student
Hawassa University Institute of Technology

---

## �� License

This project is licensed under the **MIT License**.

---

## �� Repository Link

�� https://github.com/Amanuel1264/5G-Edge-Iot-Proposal

---
