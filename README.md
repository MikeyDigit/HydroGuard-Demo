# HydroGuard — Smart Water Filtration & Quality Monitoring System

HydroGuard is a bench-scale smart water filtration and monitoring prototype designed to evaluate filtration performance using sensor data, live visualization, and basic recommendation logic.

The system combines a physical multi-stage filtration setup with turbidity, pH, TDS, temperature, and flow-rate sensing. Sensor readings are collected through an ESP32 microcontroller, logged using Python, and displayed through a live dashboard.

> **Status:** In Progress  
> This project is a prototype for engineering learning and demonstration. It is not a certified drinking water treatment system.

---

## Project Purpose

This project explores practical water treatment, environmental monitoring, and sustainable infrastructure design.

The goal is to measure how well a small-scale filtration system improves water clarity and to use collected data to guide maintenance and design improvements.

HydroGuard demonstrates skills in:

- Water filtration and treatment fundamentals
- Environmental data collection
- Sensor integration
- Microcontroller programming
- Data logging and visualization
- Technical reporting
- Cost estimation
- Sustainable system design

---

## System Overview

HydroGuard uses a multi-stage filtration system made from:

- Gravel
- Coarse sand
- Fine sand
- Activated carbon
- Filter cloth or polishing layer

Water-quality readings are taken before and after filtration to evaluate performance.

The system measures:

- Raw water turbidity
- Filtered water turbidity
- pH
- TDS
- Temperature
- Flow rate

The dashboard displays:

- Live sensor readings
- Turbidity reduction percentage
- Flow-rate trends
- System status
- Maintenance warnings
- Filtration performance summaries

---

## Hardware

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller |
| Turbidity Sensor x2 | Measures water clarity before and after filtration |
| pH Sensor | Measures acidity/basicity |
| TDS Sensor | Measures dissolved solids |
| Temperature Sensor | Measures water temperature |
| Flow Sensor | Measures water flow rate |
| Gravel, Sand, Activated Carbon | Filtration media |
| Tubing and Containers | Water movement and storage |
| Breadboard and Jumper Wires | Circuit prototyping |

---

## Software

| Tool | Purpose |
|---|---|
| Arduino C++ | ESP32 sensor firmware |
| Python | Data logging and processing |
| CSV | Stores sensor readings |
| Streamlit | Local dashboard |
| Plotly | Data visualization |
| FastAPI | Optional backend |
| React | Optional web frontend |

---

## File Structure

```text
HydroGuard-Smart-Water-Monitoring/
├── esp32/
├── python/
├── backend/
├── frontend/
├── data/
├── docs/
└── images/
