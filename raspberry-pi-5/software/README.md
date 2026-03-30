# Raspberry Pi 5 Software

Host-side software for data handling, processing, and export of seismic recordings (e.g., miniSEED).

## Responsibilities
- Data reception / ingestion (from STM32 or local ADC pipeline)
- Buffer management and storage
- Time synchronization handling (if applicable)
- Conversion/export to standard seismology formats (miniSEED-oriented)
- Service management (systemd) for unattended operation

## Suggested Structure
- `python/`    Parsers, converters, tools
- `services/`  systemd units, watchdog configuration
- `scripts/`   Setup/deploy scripts

## Setup / Run
Document dependencies and execution steps here.
