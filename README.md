# seismic-datalogger

Seismic (accelerographic) data acquisition system developed as part of my Mechatronics B.Sc. thesis.  
The project focuses on continuous, reliable recording with robust time-stamping, enabling reuse of existing accelerometric sensors and exporting data in standard seismology formats (e.g., miniSEED).

---

## System Overview

The system is composed of:

- **STM32F407** – Real-time data acquisition and low-level hardware control.
- **Raspberry Pi 5** – Data management, processing, and standard format generation.
- **Custom Hardware** – Signal conditioning, ADC interface, and integration with accelerometric sensors.

---

## Repository Structure
