

```
# Computerized Management System for Hybrid-Electric Tugboats

## Project Overview

This project focuses on developing a **computerized management system** to improve the **efficiency, flexibility, and environmental sustainability** of **hybrid-electric propulsion (H-EP) tugboats**.

Unlike existing research that focuses on large vessels or simplified models, this work targets **real-life hybrid tugboats** with **complex dynamic constraints** such as variable loads, frequent maneuvers, and short operational cycles.

The final goal is to **simulate**, **analyze**, and **optimize** energy and operational performance through an **integrated hybrid-electric propulsion model** built and validated using **Python**.

---

## Objectives

### Main Objective
Increase the **flexibility and efficiency** of hybrid-electric tugboat operations while **reducing their environmental footprint** through a computerized management system.

### Specific Objectives
1. **Optimize operational efficiency** of connected vessels  
2. **Reduce environmental impact** of hybrid-electric propulsion  
3. **Improve planning and coordination** of maritime operations  

---

## Core Components

### 1. Data Collection & Processing
- Source files (`.xls`, `.xlsx`) contain second-by-second measurements from various onboard systems:
  - **Main Engines (PORT/STBD):** fuel flow, temperature, power
  - **Shafts:** RPM, torque, energy
  - **LC Sensors:** oxygen and lambda
  - **GPS & AIS:** position, speed, vessel info  
- Raw data located in: `data/raw/`  
- Processed outputs stored in: `data/processed/`

### 2. Modeling & Simulation
The hybrid-electric propulsion model integrates:
- **Technical variables:** SOC, instantaneous power  
- **Environmental variables:** weather, tide  
- **Operational variables:** mission type, towing duration  

Algorithms used for energy management:
- **Genetic Algorithm (GA)**
- **Adaptive Equivalent Consumption Minimization Strategy (A-ECMS)**  

---

## Evaluation Criteria (KPIs)

### 1. Energy Efficiency
- Average energy consumption per mission (kWh/h)  
- Overall energy efficiency (%)  
- Energy saved per mission (%)  
- Battery vs. diesel energy ratio  

### 2. Operational Optimization
- Average mission duration  
- Schedule compliance rate (%)  
- Energy productivity (kWh/ton-nm)  
- Tugboat utilization rate (%)  

### 3. Environmental Performance
- CO₂-equivalent emissions per mission (kgCO₂e)  
- GHG reduction rate (%)  
- Compliance with IMO standards  

### 4. Reliability & Maintenance
- Unplanned shutdowns (count)  
- Mean Time Between Failures (MTBF)  
- Maintenance cost per operating hour ($/h)  
- Preventive alert rate (%)  
- Average battery SOC degradation (%/month or %/year)  

---

## Tools and Technologies

| Domain | Tool | Purpose |
|--------|------|----------|
| Modeling & Optimization | **Python** | Primary analysis and modeling tool |
| Data Processing | **Pandas**, **NumPy** | Data extraction, cleaning, and transformation |
| Visualization | **Matplotlib**, **Altair**, **Plotly** | Graphs, maps, and dashboards |
| Simulation (future) | **Simulink**, **Typhoon HIL402** | Comparative real-time or offline validation |

---

## Project Structure
```

hybrid_tugboat/

analysis.ipynb **          **# Main analysis notebook**

**README.md**                **# Project documentation

data/**docs/

data/**raw/ **                **# Raw sensor data (ignored in Git)

data/processed/ **          **# Cleaned & formatted data outputs

.gitignore **              **# Git ignore file to exclude large raw data

```
---

## Implementation Steps

1. **Review documentation** (`data/docs/`)
2. **Explore and clean** all raw sensor files (`data/raw/`)
3. **Develop analytical models** in Python  
4. **Simulate energy management and mission performance**
5. **Visualize** KPIs through plots and maps
6. **Validate results** against conventional diesel benchmarks
7. **Compare alternative strategies:**
   - Electrification adoption
   - Biofuel integration

---

## Expected Outcomes

- Validated **hybrid-electric propulsion model** for tugboats  
- Comparative analysis of **conventional vs hybrid systems**  
- **KPI-based dashboard** for operational and environmental insights  
- Foundational framework for **fleet-level simulation** and optimization  

---

## Repository Notes

Raw data files (~50 MB each) are excluded from version control.

```gitignore
data/raw/
```
