<div align="center">

# Richard J. Reyes

### Controls Engineer · Independent Researcher · Software Developer

**Industrial automation, nonlinear wave dynamics, scientific computing, and experimental research**

[![GitHub](https://img.shields.io/badge/GitHub-rickyjreyes-181717?logo=github)](https://github.com/rickyjreyes)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--5975--8718-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0005-5975-8718)
[![Email](https://img.shields.io/badge/Email-reyes.ricky30%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:reyes.ricky30@gmail.com)

</div>

---

## About

I design and implement industrial control systems while developing an open, audit-oriented research program at the intersection of **nonlinear PDEs, wave confinement, spectral dynamics, computation, and experimental physics**.

My main independent research program is **Wave Confinement Theory (WCT)**: a proposed geometric wave framework in which persistent structures are modeled through curvature feedback, phase locking, finite-wavenumber selection, topology, and Lyapunov-regulated dynamics.

```text
wave transport
    → finite-band mode selection
    → resonant confinement
    → curvature and phase locking
    → localized effective structure
```

The recurring WCT objects include the regularized curvature operator

$$
\Theta[\psi]
=-\frac{\nabla^2\psi}
{\psi+\varepsilon e^{-\alpha|\psi|^2}},
$$

and the loop-curvature rest-energy ansatz

$$
E_{\mathrm{rest}}=mc^2=\hbar c\,k_{\mathrm{eff}},
\qquad
m=\frac{\hbar}{c}\left\langle\sqrt{\kappa^2+\tau^2}\right\rangle_w.
$$

WCT is an evolving independent research framework, not an established physical theory. My repositories are organized to separate **derivations, simulations, measured data, phenomenological tests, and speculative extensions** so each layer can be audited independently.

## Current work

- **Industrial controls:** PLC logic, instrumentation, alarms, process sequencing, networked HMIs, commissioning, and control-system troubleshooting.
- **Mathematical physics:** curvature-regulated wave equations, finite-band instability, soliton localization, spectral entropy, loop geometry, and dimensional stability.
- **Experimental analysis:** optical and photodiode measurements with raw oscilloscope data, FFT pipelines, controls, null tests, and reproducible output artifacts.
- **Open-data tests:** atomic spectra, collider candidate spectra, log-periodic structure, harmonic geometry, and statistical falsification.
- **Computational architecture:** GPU scientific computing, symbolic derivation, nonlinear-PDE commitments, and coherence-bounded AI concepts.
- **Fusion control:** diagnostics-driven transport estimation, actuator allocation, safety margins, and self-biasing tokamak-control simulations.

## Featured repositories

| Repository | Purpose |
|---|---|
| **[geometry_of_resonance](https://github.com/rickyjreyes/geometry_of_resonance)** | Main WCT research archive: equations, papers, simulations, experiments, spectral tests, and reading paths. |
| **[photodiode](https://github.com/rickyjreyes/photodiode)** | Reproducible silicon-photodiode artifact package with raw waveform data, FFT analysis, prediction records, controls, and shuffle-null tests. |
| **[LHC](https://github.com/rickyjreyes/LHC)** | Open-data analysis of structured residuals and log-spectral geometry in $B^0\rightarrow K^{*0}\mu^+\mu^-$ candidate spectra. |
| **[NIST](https://github.com/rickyjreyes/NIST)** | Reproducible log-cosine line-density scan of public NIST Atomic Spectra Database transition-metal line lists. The canonical Fe II mode has $k_{\mathrm{best}}=31.3265$ across 120, 160, and 200 bins, with active-domain winding $n\approx10.7$ and 0/5000 Poisson-bootstrap exceedances per setting. NIST is the data provider only; no endorsement or validation is claimed. |
| **[Wavelock](https://github.com/rickyjreyes/Wavelock)** | Experimental path-dependent commitments, one-time signatures, adversarial audits, and a prototype curvature-locked ledger. Not production cryptography. |

## Research method

```text
Define the object
    ↓
Derive the governing equation
    ↓
State assumptions and failure conditions
    ↓
Implement a reproducible numerical or experimental test
    ↓
Run controls, null models, ablations, and adversarial checks
    ↓
Publish code, data, outputs, and unresolved problems
```

I prioritize:

- explicit equations and dependency chains;
- complete code and data artifacts;
- prediction ledgers and chronological records;
- effect sizes and global null tests rather than isolated $p$-values;
- clear separation of observation, inference, and physical interpretation;
- documented negative results, failure modes, and open proof obligations.

## Engineering and research tools

`Python` · `NumPy` · `SciPy` · `CuPy` · `R` · `C/C++` · `JavaScript` · `React` · `Docker` · `Git` · `LaTeX` · `B&R Automation Studio` · `Industrial PLC/HMI systems`

## Background

- **B.S. Computer Science**, San José State University
- **Controls Engineer**, industrial refrigeration and process automation
- **Independent researcher**, mathematical physics and scientific computation

## Contact and review

Technical criticism, independent replication, mathematical audits, and experimental controls are welcome.

- **Email:** [reyes.ricky30@gmail.com](mailto:reyes.ricky30@gmail.com)
- **ORCID:** [0009-0005-5975-8718](https://orcid.org/0009-0005-5975-8718)
- **Research code:** [github.com/rickyjreyes](https://github.com/rickyjreyes)

> The fastest entry into the research program is the README and recommended reading order in **[geometry_of_resonance](https://github.com/rickyjreyes/geometry_of_resonance)**.
