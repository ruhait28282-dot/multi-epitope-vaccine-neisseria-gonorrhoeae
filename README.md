# 🧬 Multi-Epitope Vaccine Design Against *Neisseria gonorrhoeae*

## Project Overview

This repository documents my undergraduate research project focused on the computational design and evaluation of a multi-epitope vaccine candidate against *Neisseria gonorrhoeae* using reverse vaccinology and immunoinformatics approaches.

The project integrates bioinformatics, structural biology, and computational immunology to identify promising vaccine candidates through an in silico workflow.

---

## Research Objectives

- Identify potential vaccine targets from the pathogen proteome.
- Predict immunogenic B-cell and T-cell epitopes.
- Design a multi-epitope vaccine construct.
- Evaluate structural quality and stability.
- Assess the vaccine candidate using computational validation techniques.

---

## 🧭 Computational Workflow

![Computational Workflow](Workflow/pipleline.png)

*Figure 1. Computational workflow illustrating the reverse vaccinology and immunoinformatics pipeline used for the computational design and evaluation of a multi-epitope vaccine candidate against* **Neisseria gonorrhoeae**.

---

## 🔬 Research Methodology

The computational workflow followed a reverse vaccinology and immunoinformatics pipeline consisting of the following stages:

1. Retrieval of the complete proteome of *Neisseria gonorrhoeae* from UniProt.
2. Removal of redundant protein sequences using CD-HIT.
3. Identification of essential proteins.
4. Prediction of subcellular localization.
5. Screening for antigenicity and allergenicity.
6. Prediction of CTL, HTL, and B-cell epitopes.
7. Population coverage analysis using the IEDB Population Coverage tool.
8. Construction of a multi-epitope vaccine using AAY, GPGPG, and EAAAK linkers.
9. Evaluation of physicochemical properties.
10. Three-dimensional structure prediction.
11. Structure refinement.
12. Structural validation.
13. Molecular docking with Toll-like receptor 3 (TLR3).
14. Molecular dynamics and stability analysis using iMODS.
15. Codon optimization using JCat.
16. In silico cloning into the pET-28a(+) expression vector using Serial Cloner.
17. Immune simulation using C-ImmSim.

---

| Category | Tools |
|----------|-------|
| Protein Database | UniProt |
| Redundancy Removal | CD-HIT |
| Essential Protein Analysis | DEG |
| Subcellular Localization | PSORTb, CELLO |
| Antigenicity Prediction | VaxiJen |
| Allergenicity Prediction | AllerTOP |
| Epitope Prediction | IEDB Analysis Resource |
| Population Coverage | IEDB Population Coverage |
| Structure Prediction | AlphaFold |
| Structure Refinement | GalaxyRefine |
| Structure Validation | PROCHECK (Ramachandran Plot), ERRAT |
| Molecular Docking | ClusPro |
| Molecular Dynamics | iMODS |
| Codon Optimization | JCat |
| In Silico Cloning | Serial Cloner |
| Immune Simulation | C-ImmSim |

---
## 📊 Results and Validation

### Structural Validation

The refined vaccine construct was evaluated using Ramachandran plot analysis to assess its stereochemical quality.

![Ramachandran Plot](ramachandran.png)

*Figure 2. Ramachandran plot of the refined vaccine construct showing the distribution of residues in favored, allowed, and disallowed regions.*


## 📊 Key Results

| Parameter | Result |
|-----------|--------|
| Vaccine Construct Length | 354 amino acids |
| Optimized Coding Sequence | 936 bp |
| Allergenicity | Non-allergenic |
| Solubility | Soluble |
| Ramachandran Plot | 93.5% residues in most favored regions (98.0% favored after refinement) |
| ERRAT Quality Score | 66.087% |
| Best Docking Score (TLR3) | -1183.0 |
| Molecular Dynamics Analysis | Stable vaccine–TLR3 complex supported by iMODS |
| Immune Simulation | Strong immune response with antigen clearance by Day 5 |
| Peak IFN-γ Response | ~420,000 ng/mL (Day 10) |
| Codon Adaptation Index (CAI) | Improved from 0.7325 to 0.9574 |
| GC Content | Improved from 64.93% to 70.36% |

---

### Highlights

- Successfully designed a computational multi-epitope vaccine candidate against *Neisseria gonorrhoeae*.
- Predicted vaccine construct was non-allergenic and soluble.
- Structural refinement improved model quality before docking.
- Molecular docking demonstrated favorable interaction with TLR3.
- iMODS analysis suggested a stable vaccine–receptor complex.
- Immune simulation predicted robust humoral and cellular immune responses.
- Codon optimization improved the construct for potential expression in *Escherichia coli*.
