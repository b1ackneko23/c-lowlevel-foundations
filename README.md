# C Low-Level Foundations

A deliberate practice repository dedicated to mastering C systems programming, manual memory management, and hardware-adjacent software architecture[cite: 2, 4].

## Directory Overview
- `01-cli-calculator/`: Modular terminal calculator emphasizing pointer math and standard input parsing[cite: 2].
- `02-matrix-math/`: Dynamic multi-dimensional array operations foundational to physics and robot coordinate transforms[cite: 2, 4].
- `03-sensor-telemetry-sim/`: File I/O simulation modeling photovoltaic voltage, current, and $P = V \times I$ power telemetry[cite: 2].

## Build Workflow
Programs are compiled using GCC:
```bash
gcc -Wall -Wextra -std=c99 src/main.c -o bin/program
