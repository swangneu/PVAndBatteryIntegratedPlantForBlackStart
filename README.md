# PVAndBatteryIntegratedPlantForBlackStart

**Version 2.0**

## Overview

This repository contains a MATLAB/Simulink simulation model for a PV and battery integrated inverter plant designed to study black start and grid-forming operation in inverter-based power systems.

The model demonstrates how grid-forming control strategies autonomously establish and regulate voltage and frequency during black start operation, under both islanded conditions and grid-connected scenarios, while ensuring coordinated power sharing between photovoltaic generation and battery energy storage systems.

The simulation is intended for research and educational purposes, particularly in the context of:

- Grid-forming inverters

- Black start capability of inverter-based resources

- Renewable and storage hybrid plants

- Microgrid operation

## Version History

### Version 2.0 (current)

The model has been rebuilt using **native Simscape Electrical** components. This is the active, maintained version located in the repository root: `PVAndBatteryIntegratedPlantForBlackStart.slx`.

### Version 1.0 (legacy)

The original model was built using **Specialized Power Systems (SPS)**. It has been preserved for reference under `legacy/PVAndBatteryIntegratedPlantForBlackStart_SPS.slx` and is no longer actively maintained.

## Requirements

- MATLAB R2024b or later

- Simulink

- Simscape Electrical

## Disclaimer

This model is intended for research and academic use only.
It is not a validated utility-grade design and should not be used directly for hardware implementation without further verification.

## Citation

If you use this model in academic work, please cite appropriately or acknowledge the repository.
