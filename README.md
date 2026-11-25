# Five-Stage Current-Starved VCO

> **Status:** Design documentation and permitted-result reconstruction in progress.

A full-custom CMOS design study of a five-stage current-starved voltage-controlled oscillator (VCO), developed in Cadence Virtuoso using a 180 nm technology flow. The project focuses on analog circuit design, oscillator behaviour, simulation, and physical-verification discipline.

## Confirmed work

- Five-stage current-starved ring-oscillator architecture
- Full-custom CMOS design flow
- Circuit simulation in Cadence Virtuoso
- Design-rule checking (DRC)
- Layout-versus-schematic (LVS) verification

## Repository plan

```text
├── docs/            # Architecture notes and permitted figures
├── simulations/     # Recreated test setup and exported results
├── results/         # Verified plots and observations
└── README.md
```

## Important note on reproducibility

Foundry PDK files, licensed Cadence libraries, and proprietary technology data will **not** be published. Frequency, power, tuning-range, and layout claims will be added only after their results are reproduced or independently verified.

## Reconstruction roadmap

- [ ] Document the current-starved delay-cell topology
- [ ] Recreate permitted schematics and test conditions
- [ ] Reproduce transient and control-voltage sweeps
- [ ] Add verified plots and design observations
- [ ] Add a concise DRC/LVS verification summary

## Author

**D. Giridhar**  
[LinkedIn](https://www.linkedin.com/in/duddekunta-giridhar-799b88302/) · [GitHub](https://github.com/DGiridhar2085)
