# ZIKV Insilico Vaccine Design
In silico immunoinformatics-based pipeline for designing a multi-epitope vaccine (MEV) against the Zika virus (ZIKV), a re-emerging flavivirus associated with severe neurological and congenital disorders
# ZIKV Multi-Epitope Vaccine Design

This project presents an **in silico immunoinformatics-based pipeline** for designing a **multi-epitope vaccine (MEV)** against the **Zika virus (ZIKV)**, a re-emerging flavivirus associated with severe neurological and congenital disorders such as microcephaly and Guillain-Barré syndrome.

## 📌 Objectives

- Predict immunogenic epitopes from key ZIKV proteins.
- Design a multi-epitope vaccine construct with high population coverage.
- Evaluate antigenicity, allergenicity, toxicity, and structural stability.
- Validate interaction with immune receptors (TLR4, MHC I & II).
- Simulate the vaccine-receptor complex dynamics under physiological conditions.
- Optimize codons and predict expression in *E. coli*.

---

## Target Proteins

- **NS5**
- **NS4**
- **Capsid**
- **Envelope**
- **Pre-membrane (prM)**

---

## 🧰 Tools & Databases Used

| Step                          | Tools / Databases                       |
|-------------------------------|-----------------------------------------|
| Epitope Prediction            | IEDB (NetCTL, NetMHCII, BepiPred)       |
| Antigenicity                  | VaxiJen v2.0                            |
| Allergenicity                 | AllerTOP v2.0, AllergenFP               |
| Toxicity                      | ToxinPred                               |
| Population Coverage           | IEDB Population Coverage Tool           |
| Vaccine Construct Design      | Linkers: AAY, GPGPG, GGGS; Adjuvant: β-defensin |
| Secondary Structure           | PSIPRED                                 |
| 3D Structure Modeling         | Robetta                                 |
| Model Refinement & Validation | Ramachandran Plot (SAVES/PROCHECK)     |
| Molecular Docking             | HADDOCK                                 |
| MD Simulation                 | GROMACS                                 |
| Codon Optimization            | JCat                                    |
| In Silico Cloning             | SnapGene or vector visualization tools  |

---

## Highlights

- Selected **7 CTL**, **9 HTL**, and **5 B-cell** epitopes.
- Achieved **91% global population coverage**.
- Strong binding affinity to **TLR4, MHC I, MHC II**.
- Molecular Dynamics confirms **stable complex** with TLR4.
- Codon-optimized vaccine shows high potential for **expression in E. coli**.

---

## Research Outcome & Future Work

This study presents a promising multi-epitope vaccine candidate against ZIKV, supported by strong in silico evidence of immunogenicity, stability, and receptor binding. While the computational results are encouraging, experimental validation through in vitro and in vivo studies will be essential to confirm its real-world efficacy and safety.

---

---
## 📄 License

This project is licensed under the **MIT License**.

## 📬 Contact

For queries, collaborations, please contact: 📧 raghava.332410@gmail.com.

