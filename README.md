HydroGuard - Demo(prototype)
----------
HydroGuard is a smart water filtration and water-quality monitoring prototype. It combines a physical filtration system with sensors, data logging, programming, and a live dashboard.



Goal: 

The goal is to track water-quality readings such as:

- Turbidity
- pH
- Temperature
- TDS
- Flow rate
- Filter performance

Current Version

This repo currently includes a demo dashboard using simulated sensor data. The demo shows how the final system will display readings, calculate filtration performance, and provide status labels such as "Good", "Warning", or "Critical".


Planned Final Version:

The final system will connect real sensor readings from an ESP32 to Python data logging and a live dashboard.

Sensors -> ESP32 -> Python Logger -> CSV Data -> Dashboard -> Recommendations 
