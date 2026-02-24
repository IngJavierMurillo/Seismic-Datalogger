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

---

## STM32 Firmware

- Bare-metal (CMSIS-based)
- Modular drivers (GPIO, SPI, UART, DMA, Timers, etc.)
- External ADC interface (e.g., ADS1256 if applicable)
- Deterministic acquisition loop
- Robust time-stamping strategy

---

## Raspberry Pi 5 Software

- Data reception and buffering
- Time synchronization handling
- Conversion/export to miniSEED
- Service management (systemd if applicable)

---

## Key Design Objectives

- Continuous seismic data recording
- Robust and precise time-stamping
- Modular and scalable architecture
- Low-cost alternative to commercial seismic recorders
- Easy data extraction and standard-compliant output

---

## Thesis Context

Design, implementation, and experimental validation of a seismic (accelerographic) data acquisition system based on STM32 and Raspberry Pi platforms.
