# Geophysical Earth Resistivity Meter - KiCad Project

This repository contains the initial KiCad project scaffolding and BOM for the Geophysical Earth Resistivity Meter design (ESP32 + ADS1115 front-end) targeted to 0-200 V DC HV with CC, and 4 SPST HV relays for probes C1,C2,P1,P2.

Branch: feature/kicad-georesistivity

Structure:
- README.md (this file)
- LICENSE (MIT)
- .gitignore
- BOM.csv (final BOM ready for import)
- kicad_project/
  - project.pro (placeholder)
  - power_board.sch
  - hv_relay_board.sch
  - sensor_control_board.sch
  - power_board.kicad_pcb (placeholder)
  - hv_relay_board.kicad_pcb (placeholder)
  - sensor_control_board.kicad_pcb (placeholder)
- libs/
  - README.md (notes about custom symbols and footprints)

Notes:
- These are initial placeholder KiCad files and the BOM. Schematic capture and PCB layout files are placeholders to be edited in KiCad v6. Custom symbols/footprints will be added in subsequent commits.
- Safety: HV areas require creepage/clearance rules and appropriate handling. Follow README instructions before assembly.
