# 52.2 kWp Grid-Connected Solar PV System – Venkatesh Dream Hub

## Project Overview

This project presents the **design and simulation of a 52.2 kWp grid-connected solar PV system** for Venkatesh Dream Hub, Dhule, India.

The system was modelled and analyzed using **PVsyst**, while the electrical **Single-Line Diagram (SLD)** was developed using **AutoCAD Electrical**.

The project focuses on PV array and inverter configuration, energy-yield estimation, system performance, loss analysis, module ageing, and electrical system representation.

---

## Software Used

- **PVsyst 8.1.6** – PV system simulation and performance analysis
- **AutoCAD Electrical** – Electrical Single-Line Diagram (SLD) design

---

## System Specifications

| Parameter            |                        Value |
| -------------------- | ---------------------------: |
| PV System Capacity   |                 **52.2 kWp** |
| PV Modules           |              **90 × 580 Wp** |
| Array Configuration  |            **2 × 26.10 kWp** |
| String Configuration | **3 × 15 modules per array** |
| Inverter Capacity    |                 **50 kW AC** |
| DC/AC Ratio          |                     **1.04** |
| System Type          |               Grid-Connected |
| Tilt / Azimuth       |                 **12° / 0°** |

---

## PVsyst Simulation

The PVsyst model includes geographical and meteorological data, system orientation, PV array configuration, inverter sizing, system losses, and energy-yield simulation.

### Project Setup

The project setup includes:

- Geographical coordinates
- Monthly weather data
- Sun path analysis
- PV array orientation

These files are available under [`01.1_Project_Setup`](01_PVsyst_Simulation/01.1_Project_Setup/).

### PV Array & Inverter Configuration

The system consists of **90 × 580 Wp PV modules**, divided into two **26.10 kWp arrays**, with a total installed capacity of **52.2 kWp**.

The PV array is connected to a **50 kW AC inverter**, resulting in a **DC/AC ratio of 1.04**.

**[View PVsyst System Summary](01_PVsyst_Simulation/01.2_System_Design/System_Summary.pdf)**

---

## Key Simulation Results

| Parameter                |                 Result |
| ------------------------ | ---------------------: |
| Annual Energy Production |    **83,078 kWh/year** |
| Specific Production      | **1,592 kWh/kWp/year** |
| Performance Ratio (PR)   |             **81.68%** |
| P50 Energy Production    |     **83.08 MWh/year** |
| P90 Energy Production    |     **79.90 MWh/year** |

### Simulation Graphs

The simulation results include graphical analysis of:

- Performance Ratio (PR)
- Array Temperature vs. Effective Irradiance
- Daily Input/Output Diagram
- System Output Power Distribution

---

## Performance & Loss Analysis

Additional PVsyst analysis was performed to study important factors affecting system performance:

- **IAM (Incidence Angle Modifier) losses**
- **Ohmic loss graph**
- **Ohmic loss parameters**
- **PV module ageing and degradation**

The PVsyst loss diagram indicates that **PV temperature loss is the largest individual simulated loss at approximately 6.91%**.

The detailed performance-analysis files are:

- [`IAM_Losses.png`](01_PVsyst_Simulation/01.4_Performance_Analysis/IAM_Losses.png)
- [`Ohmic_Losses_Graph.png`](01_PVsyst_Simulation/01.4_Performance_Analysis/Ohmic_Losses_Graph.png)
- [`Ohmic_Losses_Parameters.png`](01_PVsyst_Simulation/01.4_Performance_Analysis/Ohmic_Losses_Parameters.png)
- [`PV_Module_Ageing.png`](01_PVsyst_Simulation/01.4_Performance_Analysis/PV_Module_Ageing.png)

---

## PVsyst Simulation Report

The original PVsyst-generated report contains the complete simulation results, including:

- Normalized energy production
- Performance Ratio
- System loss diagram
- Daily Input/Output diagram
- System Output Power Distribution
- P50–P90 evaluation
- CO₂ emission balance

**[View Complete PVsyst Simulation Report](01_PVsyst_Simulation/01.5_PVsyst_Report/PVsyst_Generated_Report.pdf)**

---

## Electrical Single-Line Diagram

The electrical **Single-Line Diagram (SLD)** was developed using **AutoCAD Electrical** to represent the PV arrays, inverter, AC-side protection, bidirectional energy metering, and grid connection.

Both the editable AutoCAD drawing and PDF version are included.

- **[View SLD – PDF](02_Electrical_SLD/Venkatesh_Dream_Hub_SLD.pdf)**
- **[AutoCAD Electrical Drawing – DWG](02_Electrical_SLD/Venkatesh_Dream_Hub_SLD.dwg)**

---

## Repository Structure

```text
52.2-kWp-Solar-PV-Venkatesh-Dream-Hub/
│
├── README.md
│
├── 01_PVsyst_Simulation/
│   │
│   ├── 01.1_Project_Setup/
│   │   ├── Geographical_Coordinates.png
│   │   ├── Monthly_Weather_Data.png
│   │   ├── Sun_Path_Plot.png
│   │   └── Orientation_Management.png
│   │
│   ├── 01.2_System_Design/
│   │   ├── System_Summary.pdf
│   │   └── Grid_System_Definition_PV_Array_and_Inverter.png
│   │
│   ├── 01.3_Simulation_Results/
│   │   └── Simulation_Parameters_Graphs.png
│   │
│   ├── 01.4_Performance_Analysis/
│   │   ├── IAM_Losses.png
│   │   ├── Ohmic_Losses_Graph.png
│   │   ├── Ohmic_Losses_Parameters.png
│   │   └── PV_Module_Ageing.png
│   │
│   └── 01.5_PVsyst_Report/
│       └── PVsyst_Generated_Report.pdf
│
└── 02_Electrical_SLD/
    ├── Venkatesh_Dream_Hub_SLD.dwg
    └── Venkatesh_Dream_Hub_SLD.pdf
```

---

## Key Learnings

- Grid-connected solar PV system modelling using **PVsyst**
- PV module, string, array, and inverter configuration
- Energy-yield and Performance Ratio analysis
- PV system loss analysis
- IAM and ohmic-loss assessment
- P50–P90 energy-production evaluation
- PV module ageing analysis
- Electrical SLD development using **AutoCAD Electrical**

---

> **Note:** The simulation was performed using PVsyst 8.1.6 Trial. Results are based on the meteorological data, system configuration, and loss assumptions defined in the PVsyst model.

---

## Contact

**Shweta Baviskar**

([https://www.linkedin.com/in/shweta-m-baviskar/](https://www.linkedin.com/in/shweta-m-baviskar/))
