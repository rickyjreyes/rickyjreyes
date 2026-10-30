<div align="center">

# Richard J. Reyes

### Controls Engineer · Independent Researcher · Software Developer

**Lean 4 formal mathematics · Nonlinear wave dynamics · Industrial controls · Scientific computing**

[![Research Website](https://img.shields.io/badge/Research-Website-67D4FF)](https://rickyjreyes.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-rickyjreyes-181717?logo=github)](https://github.com/rickyjreyes)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rickyjreyes-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rickyjreyes/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--5975--8718-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0005-5975-8718)
[![Email](https://img.shields.io/badge/Email-reyes.ricky30%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:reyes.ricky30@gmail.com)

</div>

> **Richard J. Reyes** is a controls engineer and independent researcher working on **nonlinear partial differential equations, Lean 4 formal verification, wave dynamics, scientific computing, and industrial automation.** His mathematical work investigates precise existence, stability, spectral and geometric questions through proofs, counterexamples, and reproducible formalization. In parallel, he develops **Wave Confinement Theory (WCT)** as a proposed physical framework for confined oscillatory fields, with separate experimental and computational tests.

- **[Research website](https://rickyjreyes.github.io/):** accessible summaries, publication discovery, research-status labels, and the complete searchable archive.
- **[Formal mathematics and manuscripts](https://github.com/rickyjreyes/math):** theorem statements, compiled papers, Lean 4 proofs, and counterexamples.
- **[Technical WCT research hub](https://github.com/rickyjreyes/geometry_of_resonance):** manuscripts, equations, simulations, experiments, code, and reading maps.
- **[Reyes Problem Repository](https://github.com/rickyjreyes/math/tree/main/reyes-problem-repository):** a 300-entry research agenda with explicit issue, proof, and review workflows.
- **[Zenodo releases](https://rickyjreyes.github.io/publications/):** permanent DOI records and downloadable publications.

---

## Research highlights (October 2026)

The current research portfolio has two complementary tracks: **scope-precise mathematics with reproducible proofs** and **WCT-inspired physical and computational hypotheses tested against data and experiments**. Start with the checked mathematical statements rather than treating a numerical experiment or a broader physical proposal as the same kind of evidence.

| Research area | Current result or scope | Check the evidence |
|---|---|---|
| **Lean 4 mathematics** | **14/14 original mathematical manuscripts** marked complete at the repository's defined manuscript scope. The latest manifest reports **136 project modules** and **2,522 theorem/lemma source declarations**, including supporting and private lemmas. These are verification inventory counts, not 2,522 independent discoveries. | [Mathematics hub](https://github.com/rickyjreyes/math) · [Formalization manifest](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml) · [Certification review](https://github.com/rickyjreyes/math/blob/main/docs/ANALYTIC_CERTIFICATION_2026-10-30.md) |
| **Fourth-order nonlinear PDEs** | For an explicitly defined cubic–quintic Hamiltonian on H²(ℝ²; ℂ): strict binding, existence and compactness of constrained minimizers, global H² evolution, and orbital stability under stated coefficient and mass hypotheses. These mathematical results do not automatically establish the wider WCT physical model. | [Papers and formal proofs](https://github.com/rickyjreyes/math#selected-mathematical-results) |
| **Frozen D4 binding** | The actual prescribed 2D whole-space mass admits strict binding at **every** nontrivial split, with the exact analytic bound **I₂(μ) + I₂(m − μ) − I₂(m) > min(μ, m − μ)/400000**. The quantitative certificate uses rational arithmetic; this particular certificate is not a separate Lean formalization. | [Merged proof review, PR #51](https://github.com/rickyjreyes/geometry_of_resonance/pull/51) · [Full derivation](https://github.com/rickyjreyes/geometry_of_resonance/blob/main/docs/d4_frozen_review/PROOF.md) |
| **Geometric and inverse-problem obstructions** | Results include a rank-at-most-two obstruction for a specified scalar-gradient Gram tensor and a local non-identifiability result for a 31-parameter spectral observation model. Conclusions retain their exact hypotheses and are not universal no-go statements. | [F08 and F09 in the mathematics catalogue](https://github.com/rickyjreyes/math/blob/main/CONTENTS.md) |
| **Reyes Problem Repository** | **300 proposed research entries:** 65 formally stated questions and 235 early-stage research sketches. Each can progress through issue → proof or counterexample → review → Lean and/or paper. The list is a research agenda, not 300 independently established unsolved problems. | [Browse the problem repository](https://github.com/rickyjreyes/math/tree/main/reyes-problem-repository) |
| **WaveLock / CurvaChain** | Experimental cryptographic and ledger implementations, with attack audits and explicit remaining proof obligations. No general cryptographic security or hardness theorem is claimed. | [WaveLock research code and security status](https://github.com/rickyjreyes/Wavelock) |

**How to read these claims:** Lean checks the exact encoded propositions and assumptions; an analytic proof or exact-rational certificate is a different kind of evidence; simulations and physical interpretations need their own validation. The linked source repositories provide the claim-level boundaries.

---

## Reproduce WCT-2026.2

The maintained WCT research stack has a frozen, CI-verified release that pins the exact canonical-equation, SymPy, Lean, simulation, and published-registry source commits.

[![Run guide](https://img.shields.io/badge/Run-WCT--2026.2-67D4FF?style=for-the-badge)](https://rickyjreyes.github.io/reproduce/)
[![Frozen manifest](https://img.shields.io/badge/Manifest-JSON-64E19D?style=for-the-badge)](https://rickyjreyes.github.io/release/WCT-2026.2/release-manifest.json)
[![Release CI](https://img.shields.io/badge/CI-Lean%20%7C%20SymPy%20%7C%20Docker%20%7C%20Nix-9B8CFF?style=for-the-badge)](https://github.com/rickyjreyes/rickyjreyes.github.io/actions/workflows/frozen-release.yml)

```bash
git clone https://github.com/rickyjreyes/rickyjreyes.github.io.git
cd rickyjreyes.github.io
make reproduce
```

This rebuilds and verifies the 142-object registry, full SymPy audit, Lean formal layer, deterministic finite-band simulation, regenerated figure, source hashes, expected artifact hashes, Docker environment, and Nix environment. A successful run verifies reproducibility across the declared source, formal, simulation, and artifact layers.

---

## Contents

- [Research highlights (October 2026)](#research-highlights-october-2026)
- [Reproduce WCT-2026.2](#reproduce-wct-20262)
- [About](#about)
- [The research idea](#the-research-idea)
- [Start here — reading paths](#start-here--reading-paths)
- [Main research branches](#main-research-branches)
- [Engineering and software](#engineering-and-software)
- [Publications and Zenodo releases](#publications-and-zenodo-releases)
- [How to cite](#how-to-cite)
- [Background and contact](#background-and-contact)

---

## About

Richard J. Reyes is a controls engineer and independent researcher working across **industrial automation, nonlinear wave dynamics, scientific computing, and experimental analysis**.

He holds a **B.S. in Computer Science from San José State University** and works in industrial refrigeration and process automation, including PLC logic, instrumentation, alarms, sequencing, networked HMIs, commissioning, and control-system troubleshooting.

His research includes **independent mathematical analysis and Lean 4 formal verification** of nonlinear PDE, spectral, variational, and geometric questions. A separate, related program develops **Wave Confinement Theory (WCT)** and examines its physical hypotheses using symbolic calculations, simulations, open data, and experiments.

- **Research website:** [rickyjreyes.github.io](https://rickyjreyes.github.io/)
- **ORCID:** [0009-0005-5975-8718](https://orcid.org/0009-0005-5975-8718)
- **Mathematics and formal proofs:** [math](https://github.com/rickyjreyes/math)
- **WCT research hub:** [geometry_of_resonance](https://github.com/rickyjreyes/geometry_of_resonance)
- **Zenodo DOI collection:** [28 DOI records below](#publications-and-zenodo-releases); check the [live publication archive](https://rickyjreyes.github.io/publications/) for the broader catalogue.

## The research idea

**Wave Confinement Theory** is a proposed geometric wave framework in which persistent physical structure emerges from confined oscillatory fields.

```text
wave transport
    → finite-band mode selection
    → resonant confinement
    → phase and curvature locking
    → localized persistent structure
```

The central question is whether quantities usually treated as primitive—such as **mass, force, spectra, and effective geometry**—can instead arise from sustained resonance, curvature feedback, topology, and entropy-regulated coherence.

The public WCT corpus organizes definitions, derivations, simulations, experiments, phenomenology, and research extensions so each claim is connected to its corresponding evidence, code, data, and source record.

## Start here — reading paths

For **formal mathematics**, begin with the **[mathematics repository](https://github.com/rickyjreyes/math)** and its [Lean manuscript manifest](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml). For the **proposed physical program**, begin with the **[Geometry of Resonance / WCT Research Hub](https://github.com/rickyjreyes/geometry_of_resonance)**, which collects papers, equations, simulations, experiments, reading maps, and open-data tests.

**If you are new to the program, read in this order:**

1. **[The Geometry of Resonance](https://zenodo.org/records/15644222)** — core overview of WCT and its proposed emergence of mass, force, and effective spacetime geometry.
2. **[Phase–Flux Field](https://zenodo.org/records/17578766)** — observable substrate, conservation laws, finite-wavenumber selection, and shell formation.
3. **[Rest Energy from Density-Weighted Loop Curvature](https://zenodo.org/records/20533537)** — the cleanest statement of the curvature-locking mass proposal.
4. **[Hard Upper Bound on Spatial Dimensionality](https://zenodo.org/records/17081283)** — the mathematical argument for stable confinement being restricted to at most three spatial dimensions.

**Choose a path by your background:**

| If you are a… | Start with |
|---|---|
| **Mathematician / formal methods** | [Mathematical manuscripts](https://github.com/rickyjreyes/math) → [Lean manifest](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml) → [Reyes Problem Repository](https://github.com/rickyjreyes/math/tree/main/reyes-problem-repository) |
| **WCT physicist** | [Phase–Flux Field](https://zenodo.org/records/17578766) → [Rest Energy from Loop Curvature](https://zenodo.org/records/20533537) → [Koide Mass Relation](https://zenodo.org/records/17887562) → [Lepton Mass Spectrum](https://zenodo.org/records/18936949) |
| **Computer scientist / complexity** | [Discrete Wave-Constrained Computation](https://zenodo.org/records/17732642) → [P vs NP in Curvature-Bounded Computation](https://zenodo.org/records/17743607) → [Resonance-Confinement Architecture for Safe AI](https://zenodo.org/records/17732661) |
| **Experimentalist** | [Photon Resonance Confinement in Water Cavities](https://zenodo.org/records/17206381) → [Photodiode Protocol Ledger](https://zenodo.org/records/17957713) → [photodiode repo](https://github.com/rickyjreyes/photodiode) |
| **Open-data / phenomenology** | [NIST Atomic Line List](https://zenodo.org/records/20435463) → [LHCb B⁰→K\*⁰μ⁺μ⁻ spectra](https://zenodo.org/records/20164333) → [Log-Periodic Deformation of C9(q²)](https://zenodo.org/records/19705254) |

## Main research branches

| Branch | Entry point |
|---|---|
| **Mathematical papers and Lean 4 proofs** | [math](https://github.com/rickyjreyes/math) |
| **300-entry problem research agenda** | [Reyes Problem Repository](https://github.com/rickyjreyes/math/tree/main/reyes-problem-repository) |
| **Core WCT theory** | [geometry_of_resonance](https://github.com/rickyjreyes/geometry_of_resonance) |
| **Executable symbolic audit** | [wct-sympy](https://github.com/rickyjreyes/wct-sympy) |
| **Lean formalization** | [wct-lean](https://github.com/rickyjreyes/wct-lean) |
| **Photodiode experiment and signal analysis** | [photodiode](https://github.com/rickyjreyes/photodiode) |
| **Atomic spectra / Fe II log-cosine scan** | [NIST](https://github.com/rickyjreyes/NIST) |
| **LHCb open-data spectral analysis** | [LHC](https://github.com/rickyjreyes/LHC) |
| **WaveLock and CurvaChain research** | [Wavelock](https://github.com/rickyjreyes/Wavelock) |

The maintained software, symbolic-audit, and formalization repositories use GitHub Actions, with Docker-based reproduction paths where appropriate, so core checks can be rerun in isolated environments.

The NIST project uses public NIST Atomic Spectra Database exports and reports a bin-stable Fe II log-cosine line-density mode across 120, 160, and 200 bins.

WaveLock and CurvaChain are research implementations evaluated through adversarial testing, documented proof obligations, implementation audits, and reproducible software artifacts.

## Engineering and software

- Industrial automation, PLC control logic, instrumentation, sequencing, alarming, HMIs, commissioning, and troubleshooting
- Industrial refrigeration and process-control systems
- Scientific computing, numerical simulation, signal analysis, and reproducible data workflows
- Lean 4 / Mathlib formal verification, theorem correspondence audits, and mathematical manuscript tooling
- Python, R, C/C++, JavaScript, React, Docker, GitHub Actions, and Git

## Publications and Zenodo releases

**28 DOI-indexed publications (2025–2026)**, matching the [live publication archive](https://rickyjreyes.github.io/publications/) and its [machine-readable registry](https://rickyjreyes.github.io/publications.json) as of October 29, 2026. Author: Richard J. Reyes ([ORCID 0009-0005-5975-8718](https://orcid.org/0009-0005-5975-8718)).

The titles, original release dates, and DOI links below are taken from the public registry. Month-only entries retain their published month precision. Separate mathematical manuscripts and Lean proof artifacts can be found in the [mathematics repository](https://github.com/rickyjreyes/math).

<details>
<summary><strong>Open the complete 28-record DOI list</strong></summary>

### Primary WCT foundations

1. [**The Geometry of Resonance: Wave Confinement Theory and the Emergence of Mass, Force, and Spacetime**](https://zenodo.org/records/15644222) — Apr. 22, 2025. DOI: [`10.5281/zenodo.15644222`](https://doi.org/10.5281/zenodo.15644222)
2. [**Structure and Derivation of Physical Constants through Wave Confinement**](https://zenodo.org/records/15596159) — Apr. 26, 2025. DOI: [`10.5281/zenodo.15596159`](https://doi.org/10.5281/zenodo.15596159)
3. [**Phase-Flux Field (PFF): Axiomatic Substrate for Wave Confinement Theory — Zero-Wave Invariance, Finite-k Lyapunov Band-Pass, Shell Quantization, and D4 to Continuum**](https://zenodo.org/records/17578766) — Sep. 8, 2025. DOI: [`10.5281/zenodo.17578766`](https://doi.org/10.5281/zenodo.17578766)
4. [**Exact Scale-Winding Bijection Between Discrete Scale Invariance and WCT Active-Domain Phase Closure**](https://zenodo.org/records/22665914) — Sep. 8, 2026. DOI: [`10.5281/zenodo.22665914`](https://doi.org/10.5281/zenodo.22665914)

### Mass, geometry, dimensionality, and spectral dynamics

5. [**Hard Upper Bound on Spatial Dimensionality in Wave Confinement Theory**](https://zenodo.org/records/17081283) — Aug. 13, 2025. DOI: [`10.5281/zenodo.17081283`](https://doi.org/10.5281/zenodo.17081283)
6. [**Self-Emergent Fourier Cymatics: Entropic Eigenmodes out of Chaos**](https://zenodo.org/records/17732648) — Sep. 16, 2025. DOI: [`10.5281/zenodo.17732648`](https://doi.org/10.5281/zenodo.17732648)
7. [**Emergence of Effective Mass: Solenoidal Topology of Vibrational Energy**](https://zenodo.org/records/17459463) — Oct. 27, 2025. DOI: [`10.5281/zenodo.17459463`](https://doi.org/10.5281/zenodo.17459463)
8. [**Rest Energy from Density-Weighted Loop Curvature: A Covariant Locking Principle**](https://zenodo.org/records/20533537) — Nov. 11, 2025. DOI: [`10.5281/zenodo.20533537`](https://doi.org/10.5281/zenodo.20533537)
9. [**Wave Confinement Theory Predicts the Koide Mass Relation: A Curvature–Harmonic Origin of Fermion Mass Triplets**](https://zenodo.org/records/17887562) — Dec. 10, 2025. DOI: [`10.5281/zenodo.17887562`](https://doi.org/10.5281/zenodo.17887562)
10. [**Logarithmic Curvature Flow, Filament Localization, and the Geometric Origin of the Lepton Mass Spectrum**](https://zenodo.org/records/18936949) — Mar. 10, 2026. DOI: [`10.5281/zenodo.18936949`](https://doi.org/10.5281/zenodo.18936949)
11. [**Filament Reduction and Phase Quantization of Curvature-Locked Modes**](https://zenodo.org/records/22666758) — Sep. 8, 2026. DOI: [`10.5281/zenodo.22666758`](https://doi.org/10.5281/zenodo.22666758)
12. [**Geometric Turbulence in Wave Confinement Theory: Phase-Locked Curvature Filaments and the Soliton-Gas Regime**](https://zenodo.org/records/22666935) — Sep. 8, 2026. DOI: [`10.5281/zenodo.22666935`](https://doi.org/10.5281/zenodo.22666935)

### Computation, complexity, AI, and cryptography

13. [**Part I — P vs NP in Curvature-Bounded Wave Computation: A Model-Relative Pᴡᴄᴄ ≠ NPᴡᴄᴄ Separation**](https://zenodo.org/records/17743607) — May 7, 2025. DOI: [`10.5281/zenodo.17743607`](https://doi.org/10.5281/zenodo.17743607)
14. [**Resonance-Confinement Architecture: A Physically Bounded Substrate for Safe Superintelligence**](https://zenodo.org/records/17732661) — Jun. 11, 2025. DOI: [`10.5281/zenodo.17732661`](https://doi.org/10.5281/zenodo.17732661)
15. [**Part II — Discrete Wave-Constrained Computation and Classical Complexity: Turing Equivalence for P and NP**](https://zenodo.org/records/17732642) — Nov. 26, 2025. DOI: [`10.5281/zenodo.17732642`](https://doi.org/10.5281/zenodo.17732642)
16. [**Part III — The Classical P vs NP Problem Is Mathematically and Physically Ill-Posed**](https://zenodo.org/records/17783074) — Dec. 1, 2025. DOI: [`10.5281/zenodo.17783074`](https://doi.org/10.5281/zenodo.17783074)
17. [**WaveLock: A Curvature-Locked One-Way Function Based on Nonlinear PDE Evolution**](https://zenodo.org/records/19122146) — Dec. 1, 2025. DOI: [`10.5281/zenodo.19122146`](https://doi.org/10.5281/zenodo.19122146)
18. [**Recursive AI Drift: A 2025 Prediction Timeline External Validation Audit and Technical Note**](https://zenodo.org/records/20142976) — May 2026. DOI: [`10.5281/zenodo.20142976`](https://doi.org/10.5281/zenodo.20142976)
19. [**From Wave Confinement to Recursive AI Instability: A Propagation-Correction Criticality Law and Successful Prospective Prediction**](https://zenodo.org/records/22757003) — Sep. 14, 2026. DOI: [`10.5281/zenodo.22757003`](https://doi.org/10.5281/zenodo.22757003)

### Experiment, protocol, and physical systems

20. [**Observation of Long-Lived Photon Resonance Confinement in Water Cavities**](https://zenodo.org/records/17206381) — May 17, 2025. DOI: [`10.5281/zenodo.17206381`](https://doi.org/10.5281/zenodo.17206381)
21. [**JUNO Energy Resolution and Detectability of WCT Ghost-Mode Neutrinos**](https://zenodo.org/records/17715872) — Nov. 20, 2025. DOI: [`10.5281/zenodo.17715872`](https://doi.org/10.5281/zenodo.17715872)
22. [**Prediction & Protocol Ledger: Long-Lived Harmonic State Induction in Photodiodes**](https://zenodo.org/records/17957713) — Dec. 2025. DOI: [`10.5281/zenodo.17957713`](https://doi.org/10.5281/zenodo.17957713)
23. [**Nuclear Fusion Tokamak with Self Sustaining Resonance**](https://zenodo.org/records/19578185) — Apr. 14, 2026. DOI: [`10.5281/zenodo.19578185`](https://doi.org/10.5281/zenodo.19578185)

### Collider, gravitational-wave, atomic-line, and open-data phenomenology

24. [**A Curvature-Induced Log-Periodic Deformation of C9(q²): Wave Confinement Theory and the LHCb B⁰ → K\*⁰ μ⁺μ⁻ Anomaly**](https://zenodo.org/records/19705254) — Apr. 23, 2026. DOI: [`10.5281/zenodo.19705254`](https://doi.org/10.5281/zenodo.19705254)
25. [**Log-Spectral Structure and Koide-Like Winding Geometry in Open-Data B⁰ → K\*⁰ μ⁺μ⁻ Candidate Spectra**](https://zenodo.org/records/20164333) — May 9, 2026. DOI: [`10.5281/zenodo.20164333`](https://doi.org/10.5281/zenodo.20164333)
26. [**Bin-Stable Log-Periodic Structure in Public NIST Atomic Line List**](https://zenodo.org/records/20435463) — May 28, 2026. DOI: [`10.5281/zenodo.20435463`](https://doi.org/10.5281/zenodo.20435463)
27. [**Log-Periodic Structure in the GWTC Chirp-Mass Distribution: Frozen Holdout Evidence and a Prospective Prediction**](https://zenodo.org/records/22256802) — Aug. 26, 2026. DOI: [`10.5281/zenodo.22256802`](https://doi.org/10.5281/zenodo.22256802)
28. [**Log-Periodic Dimuon Residual in CMS Open Data: Cross-Period Replication and a Prospective Phase-Locked Holdout**](https://zenodo.org/records/22257067) — Aug. 31, 2026. DOI: [`10.5281/zenodo.22257067`](https://doi.org/10.5281/zenodo.22257067)

</details>

## How to cite

Please cite the specific publication you used by its Zenodo DOI. All 28 DOI records listed here are indexed in [`CITATION.cff`](CITATION.cff), which GitHub uses for repository citation information. For mathematical results without a corresponding Zenodo release, cite the specific manuscript, its hypotheses, and the relevant Git revision.

```bibtex
@misc{reyes_geometry_of_resonance_2025,
  author       = {Reyes, Richard J.},
  title        = {The Geometry of Resonance: Wave Confinement Theory and the
                  Emergence of Mass, Force, and Spacetime},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.15644222},
  url          = {https://doi.org/10.5281/zenodo.15644222}
}
```

Technical criticism, mathematical audit, reproducibility review, and independent replication are welcome; open an issue in the relevant repository or contact me directly.

## Background and contact

- **Education:** B.S. Computer Science, San José State University
- **Profession:** Controls Engineer, industrial refrigeration and process automation
- **Research:** Independent mathematical physics and scientific computation
- **Website:** [rickyjreyes.github.io](https://rickyjreyes.github.io/)
- **LinkedIn:** [linkedin.com/in/rickyjreyes](https://www.linkedin.com/in/rickyjreyes/)
- **ORCID:** [0009-0005-5975-8718](https://orcid.org/0009-0005-5975-8718)
- **Email:** [reyes.ricky30@gmail.com](mailto:reyes.ricky30@gmail.com)

> For new readers, begin with the **[research website](https://rickyjreyes.github.io/)** for accessible summaries, then continue to the **[geometry_of_resonance](https://github.com/rickyjreyes/geometry_of_resonance)** repository for the technical archive.