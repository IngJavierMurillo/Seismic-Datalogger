# STM32F407 Firmware

Bare-metal (CMSIS-based) firmware for real-time seismic (accelerographic) data acquisition.

## Scope
- Deterministic sampling and buffering
- Low-level peripheral control (register-level)
- Time-stamping support (robust timing strategy)
- Interface to external ADC (e.g., ADS1256) if applicable

## Structure (expected)
- `drivers/`  Peripheral and device drivers (one `.c/.h` per module)
- `app/`      Acquisition logic, buffering, data framing
- `platform/` CMSIS device files, startup, system init
- `boards/`   Board-specific pinmap/clock/init

## Build / Flash
Add build and flash instructions here (CubeIDE / Makefile / OpenOCD / ST-LINK).

## Notes
Keep this firmware modular and reusable (driver-level separation from application logic).
