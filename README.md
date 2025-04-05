# Solar Model Experiments

This repository is dedicated to experimenting with the `pvlib` package for solar modeling. The goal is to explore and understand the capabilities of `pvlib` for simulating and analyzing solar energy systems.

## About `pvlib`
`pvlib` is a Python library that provides tools for simulating the performance of photovoltaic energy systems. It includes functions for modeling solar position, irradiance, and system performance.

## Objectives
- Learn the basics of `pvlib`.
- Experiment with different solar modeling techniques.
- Analyze and visualize solar energy data.

## Getting Started
To get started, ensure you have Python installed and install `pvlib` using pip:

```bash
pip install pvlib
```

Stay tuned for updates and experiments!


TimeShifts

TMY data CSV:
Row 10 = 22 >> Timestamp = 9am >> Shift Stated = +10min --> Implies 09:10 real timestamp

Hourly Data CSV:
Row 10 = 22 >> Timestamp = 09:10am >> Shift Stated = None --> Implies 09:10 real timestamp

TMY data EPW file:
Row 9 = 22 >> Timestamp = 09:00am >> Shift Stated = -50mins --> Implies 
Conclude PVGIS EPW data is incorrect.
