<div align="center">

# Richard J. Reyes

### Mathematical Physics · Lean 4 Formal Verification · Field Computation

**Controls Engineer · Independent Researcher · Software Developer**

[![Research Website](https://img.shields.io/badge/Research-Website-67D4FF)](https://rickyjreyes.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-rickyjreyes-181717?logo=github)](https://github.com/rickyjreyes)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rickyjreyes-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rickyjreyes/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--5975--8718-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0005-5975-8718)
[![Email](https://img.shields.io/badge/Email-reyes.ricky30%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:reyes.ricky30@gmail.com)

</div>


I study **when nonlinear waves can form stable, localized structures**, and how waves might be used as a physical substrate for computation. My work connects mathematical proofs, Lean 4 formal verification, scientific software, and industrial control engineering.

The mathematical theorems below apply to explicitly defined models. Wave Confinement Theory (WCT), WaveLock, and photonic computing are separate research programs with additional physical and engineering questions.

**Explore:** [Flagship results](#featured-mathematical-results) · [What I'm building](#what-im-building) · [Proofs and CI](#verified-mathematics-and-reproduction) · [28 DOI publications](#publications-and-zenodo-releases)

---

## Featured mathematical results

### 1. Fourth-order nonlinear waves: existence and orbital stability

The **F01 theorem series** develops an entire chain for a focusing-cubic / defocusing-quintic fourth-order Hamiltonian on **H²(ℝ²; ℂ)**:

**Negative constrained energy → strict binding → existence and compactness of minimizers modulo translations → global H² evolution → orbital stability of the minimizing set.**

The results hold for the stated independent Hamiltonian, positive coefficients and explicit sufficient mass range. This is a mathematical existence and stability result, not a derivation of the WCT parent field theory.

**Read the work:** [Strict binding](https://github.com/rickyjreyes/math/blob/main/preprints/strict-subadditivity-fourth-order-cubic-quintic/paper.pdf) · [Minimizers](https://github.com/rickyjreyes/math/blob/main/preprints/whole-space-fourth-order-cubic-quintic-minimizers/paper.pdf) · [Orbital stability](https://github.com/rickyjreyes/math/blob/main/preprints/orbital-stability-fourth-order-cubic-quintic/paper.pdf) · [Lean proof inventory](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml)

### 2. Spectral inverse problems: a 20-dimensional local ambiguity

For the specified **31-parameter / 11-observable clipped v18 map**, the **F09 Lean formalization** establishes Jacobian rank **11**, nullity **20**, and a local C¹ chart with a **20-dimensional level-set fiber**. This is local nonlinear non-identifiability of that particular model, not a universal inverse-problem obstruction or a validation of its physical predictions.

**Read the work:** [Formalized completion, PR #51](https://github.com/rickyjreyes/math/pull/51) · [F09 manuscript](https://github.com/rickyjreyes/math/blob/main/preprints/sm-v18-local-identifiability-obstruction/paper.pdf) · [Source-pinned analytic certificate](https://github.com/rickyjreyes/math/blob/main/docs/SM_V18_ANALYTIC_RANK_CERTIFICATE.md)

### 3. Frozen D4: quantitative strict binding at every mass split

For the frozen independent two-dimensional Hamiltonian at mass m = m_D4, the constrained infimum obeys:

**`I₂(μ) + I₂(m − μ) − I₂(m) > min(μ, m − μ) / 400000 > 0`** for every `0 < μ < m`.

The proof covers the full interval under the unchanged H²(ℝ²; ℂ) assumptions. Its quantitative bound is an **analytical argument with exact rational certification**, not a separate Lean proof. D4 refers to the source configuration's square symmetry, not four spatial dimensions.

**Read the work:** [Merged proof review, PR #51](https://github.com/rickyjreyes/geometry_of_resonance/pull/51) · [Full derivation](https://github.com/rickyjreyes/geometry_of_resonance/blob/main/docs/d4_frozen_review/PROOF.md)

**More mathematics:** The [F08 rank and signature obstruction](https://github.com/rickyjreyes/math/blob/main/preprints/scalar-gradient-lorentzian-no-go/paper.pdf) concerns a specified positive-semidefinite scalar-gradient tensor; the [complete catalogue](https://github.com/rickyjreyes/math/blob/main/CONTENTS.md) includes spectral concentration, phase locking, Fourier-shell exclusion, curvature operators, counterexamples, and further results.

---

## What I'm building

| Program | Objective and current status | Evidence |
|---|---|---|
| **Wave Confinement Theory** | A proposed geometric wave framework for resonance, curvature locking, localization, and models of mass and effective geometry. Mathematical submodels and physical interpretations are evaluated separately. | [Research hub](https://github.com/rickyjreyes/geometry_of_resonance) · [Foundational paper](https://doi.org/10.5281/zenodo.15644222) |
| **WaveLock / CurvaChain** | Experimental trajectory/path commitments, one-time signing and replay-verifiable ledger systems, accompanied by adversarial tests and explicit remaining security obligations. General one-wayness or cryptographic security is not established. | [Research code](https://github.com/rickyjreyes/Wavelock) |
| **Photonic field computation** | Exploratory software models for encoding instructions into optical states, using phase, wavelength, interference, and propagation as prospective computational degrees of freedom. This is a prototype research direction, not an all-optical hardware demonstration. | Engineering research |
| **Experiments and resonance control** | Optical cavity and photodiode protocols, scientific signal analysis, and applications of industrial process-control engineering. | [Photodiode experiments](https://github.com/rickyjreyes/photodiode) · [Protocol](https://doi.org/10.5281/zenodo.17957713) |

**Long-term goal:** turn mathematically specified wave dynamics into testable physical systems and, eventually, computation performed through light rather than conventional logic alone.

---

## Verified mathematics and reproduction

The public [mathematics repository](https://github.com/rickyjreyes/math) reports **14/14 original manuscripts formally completed** at its exact manuscript scope, with **136 imported Lean modules** and **2,522 theorem/lemma source declarations** (including private supporting lemmas). The declaration count is a proof-library inventory, not a count of independent discoveries.

The [formalization manifest](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml) and [Lean 4 / Mathlib v4.23.0 certification audit](https://github.com/rickyjreyes/math/blob/main/docs/ANALYTIC_CERTIFICATION_2026-10-30.md) link source theorems to explicit assumptions, kernel-checked declarations, and passing CI. Verification establishes what is encoded in Lean, not a separate proof of the full physical WCT model.

**Reproduce:** [Math Lean/PDF build instructions](https://github.com/rickyjreyes/math#verification-and-reproducibility) · [GitHub Actions](https://github.com/rickyjreyes/math/actions) · [Frozen WCT-2026.2 run guide](https://rickyjreyes.github.io/reproduce/) · [WCT release manifest](https://rickyjreyes.github.io/release/WCT-2026.2/release-manifest.json).

---

## Research repositories and reading paths

| Entry point | Purpose |
|---|---|
| [Mathematical manuscripts and Lean 4](https://github.com/rickyjreyes/math) | Verified source theorems, compiled papers, proof-status manifest, counterexamples |
| [Reyes Problem Repository](https://github.com/rickyjreyes/math/tree/main/reyes-problem-repository) | 300 proposed research entries: 65 formally stated questions and 235 preliminary candidate sketches |
| [Geometry of Resonance](https://github.com/rickyjreyes/geometry_of_resonance) | Wave Confinement Theory, derivations, numerical work, and physical research audits |
| [WaveLock / CurvaChain](https://github.com/rickyjreyes/Wavelock) | Experimental cryptographic and ledger architectures |
| [WCT SymPy](https://github.com/rickyjreyes/wct-sympy) · [WCT Lean](https://github.com/rickyjreyes/wct-lean) | Symbolic and formal checks |
| [NIST](https://github.com/rickyjreyes/NIST) · [LHC](https://github.com/rickyjreyes/LHC) · [Photodiode](https://github.com/rickyjreyes/photodiode) | Open-data spectra and experimental protocols |
| [Research website](https://rickyjreyes.github.io/) | Searchable publications, reading maps, and public research archive |

**Start with mathematics:** [F01 manuscripts](https://github.com/rickyjreyes/math#selected-mathematical-results) → [F09 proof](https://github.com/rickyjreyes/math/pull/51) → [verified Lean coverage](https://github.com/rickyjreyes/math/blob/main/lean/formalization.yaml).

**Start with WCT:** [Geometry of Resonance](https://doi.org/10.5281/zenodo.15644222) → [Phase-Flux Field](https://doi.org/10.5281/zenodo.17578766) → [rest-energy curvature model](https://doi.org/10.5281/zenodo.20533537).

---

## Engineering background

**B.S. in Computer Science, San José State University.** Industrial refrigeration and process automation: PLC logic, sequencing, instrumentation, HMIs, alarms, commissioning and troubleshooting. Research and software tools include Python, C/C++, Java, JavaScript, Lean 4 / Mathlib, scientific computing, Docker, GitHub Actions, and Git.

---

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