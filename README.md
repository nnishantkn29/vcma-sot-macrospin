# Macrospin LLGS simulation of VCMA and SOT switching in p-MTJs

UROP project, Department of Electrical and Computer Engineering,
National University of Singapore, Summer 2026.

## Overview
A unified macrospin model of the Landau–Lifshitz–Gilbert–Slonczewski
(LLGS) equation implemented in COMSOL Multiphysics, with independently
switchable STT, SOT, and VCMA driving terms. The model is validated
against the FANTASI reference devices (Miriyala et al., 2018) and the
three-terminal β-W device of Grimaldi et al. (2020), with independent
cross-checks against MuMax3.

## Repository contents
- `colab/` — Python/Colab analysis scripts for VCMA V–T–t sweeps,
  SOT J–T–t sweeps, and MuMax3 comparison
- `mumax3/` — MuMax3 macrospin cross-check scripts (VCMA and SOT)
- `comsol/` — COMSOL model notes (`.mph` files available on request)
- `data/` — simulation outputs (available on request)

## Key results
- VCMA-only switching fails within the 3 V oxide-breakdown ceiling
  above T_x ≈ 413 K
- Robust VCMA switching favours low write voltage, not high voltage
- SOT deterministic critical current J_c ≈ 6.5 × 10¹² A/m² at 300 K,
  decreasing with temperature
- The low-current switching band (~2 × 10¹²) is non-monotone in drive
  and cannot be used as an operating point

## References
- Miriyala et al. (2018), SISPAD — FANTASI framework
- Grimaldi et al. (2020), Nature Nanotechnology

## Contact
nnishant@sas.upenn.edu
