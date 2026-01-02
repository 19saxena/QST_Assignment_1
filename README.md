# Quantum State Tomography — Week 1 (ML-Ready Foundations)

## Summary
Implemented a reproducible tomography data generation workflow using the PennyLane simulator.

## Measurements
- Pauli projective measurements (X, Y, Z) with basis alignment via circuit rotations.
- POVM methods like SIC-POVM were reviewed theoretically for comparison but not implemented in simulation due to hardware and classical post-processing overhead trade-offs.

## Quantum States
|0⟩, |1⟩, |+⟩, |−⟩, and a phase-offset state (|0⟩ + i|1⟩)/√2.

## Validation Metrics
Reconstruction fidelity evaluated under shot noise and small noise perturbations.

## Files included
- Measurement datasets (.npy)
- Density matrices (.npy)
- Fidelity benchmarking tables (.csv)
- Circuit designs and visualization outputs (screenshots + Plotly)

## Reproducibility
Artifacts authored and executed by me in Google Colab using PennyLane.

## Reflection
- Dataset size scales exponentially with qubits.
- Pauli measurements are hardware-native but require multi-basis coverage.
- Future work (Week 2): ML-assisted fast state reconstruction.

