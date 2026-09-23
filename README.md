# CERN Open Data: Dimuon Invariant Mass Analyses

This repository contains two independent Python analyses of dimuon invariant mass spectra using CERN Open Data.

---

## 1. Broad-Spectrum Dimuon Invariant Mass Analysis (Run2010B)

Reproduces J/ψ, Υ, and Z boson resonances across 2–110 GeV with KDE normalisation, log-scale visualisation, and automated sequential peak detection.

- **Dataset:** CERN Open Data Portal (Record 700)
- **Script:** `broad_spectrum/jpsi_z_reconstruction.py`

## 2. Reproduction of J/ψ Meson (Run2011A)

Reproduces the J/ψ and ψ(2S) resonances following Samuel Ting's 1976 Nobel Lecture workflow.

- **Dataset:** CERN Open Data Portal (Record 5203)
- **Script:** `jpsi_reproduction/jpsi_reconstruction_dimuon.py`

---

## Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scipy
```

---

## Repository Structure

```
├── 2010B_dimuon_event/
│   ├── MuRun2010B.csv
│   ├── Dimuon_event.py
│   └── dimuon_invariant_mass_spectrum.png
│   └── README.md
└── 2011A_J-psi_to_dimuon/
    ├── Jpsimumu.csv
    ├── jpsi_reconstruction_dimuon.py
    └── jpsi_mass_spectrum_dimuon.png
    └── README.md
```
