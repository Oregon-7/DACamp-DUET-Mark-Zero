# DACamp-DUET-Mark-Zero
Design and Manufacturing Memorandum

## Repository Directory Structure

```
DACamp-DUET-Mark-Zero/
├── hardware/                  # PCB design source files
│   ├── schematics/            # Circuit schematic files (e.g. KiCad, Eagle)
│   ├── pcb/                   # PCB layout files
│   ├── gerbers/               # Intermediate Gerber output files
│   └── bom/                   # Bill of Materials
│
├── components/                # Component library assets
│   ├── symbols/               # Schematic symbols
│   ├── footprints/            # PCB land-pattern footprints
│   ├── 3d_models/             # 3D models for mechanical clearance checks
│   └── datasheets/            # Component datasheets
│       ├── analog/            # Analog components (op-amps, DACs, amplifiers, etc.)
│       ├── digital/           # Digital / IC chip components
│       └── passive/           # Passive components (resistors, capacitors, inductors, etc.)
│
├── simulation/                # Circuit simulation files
│   └── spice/                 # SPICE netlists and simulation setups
│
├── firmware/                  # Embedded software (if applicable)
│   ├── src/                   # Firmware source files
│   └── include/               # Header / interface files
│
├── docs/                      # Project documentation
│   ├── design/                # Design specifications and notes
│   ├── manufacturing/         # Manufacturing guidelines and constraints
│   └── assembly/              # Assembly instructions and procedures
│
└── manufacturing/             # Production-ready output files
    ├── gerbers/               # Final Gerber files for PCB fabrication
    ├── assembly/              # Pick-and-place and assembly data
    └── testing/               # Test procedures and acceptance criteria
```
