# EGFR T790M Computational Drug Discovery

## Project Overview

This project investigates the binding of FDA-approved EGFR inhibitors against the EGFR T790M resistance mutation using computational drug discovery approaches.

The study compares four clinically relevant inhibitors:

- Gefitinib
- Erlotinib
- Afatinib
- Osimertinib

The objective was to identify the inhibitor with the strongest predicted binding affinity toward the EGFR T790M mutant structure.

---

## Target Protein

- Protein: Epidermal Growth Factor Receptor (EGFR)
- Mutation: T790M
- PDB ID: 3IKA

---

## Methodology

### Ligand Preparation

Ligands were obtained from PubChem and prepared using:

- RDKit
- Meeko

### Protein Preparation

Protein structure preparation included:

- Removal of unnecessary molecules
- Receptor preparation
- PDBQT conversion

### Molecular Property Analysis

Calculated properties:

- Molecular Weight
- LogP
- Hydrogen Bond Donors
- Hydrogen Bond Acceptors
- Rotatable Bonds

### Docking

Docking was performed using:

- AutoDock Vina v1.2.7

Binding pocket coordinates:

X = -11.849

Y = 16.897

Z = 31.836

Grid Size:

20 × 20 × 20 Å

---

## Docking Results

| Drug | Binding Affinity (kcal/mol) |
|--------|--------|
| Afatinib | -8.241 |
| Osimertinib | -8.121 |
| Gefitinib | -8.103 |
| Erlotinib | -7.442 |

---

## Ranking

1. Afatinib
2. Osimertinib
3. Gefitinib
4. Erlotinib

---

## Key Binding Pocket Residues

- LEU718
- GLY719
- VAL726
- MET790
- GLN791
- LEU792
- MET793
- PRO794
- PHE795
- GLY796
- CYS797
- ASP800
- ASN842
- LEU844
- THR854

---

## Visualization

PyMOL was used for:

- Binding pose visualization
- Pocket residue visualization
- Mutation highlighting
- Protein-ligand interaction analysis

---

## Tools Used

- Python
- RDKit
- BioPython
- Pandas
- Matplotlib
- Meeko
- AutoDock Vina
- PyMOL

---

## Conclusion

Afatinib demonstrated the strongest predicted binding affinity toward EGFR T790M among the tested inhibitors, suggesting favorable interactions within the ATP-binding pocket.

This project demonstrates a complete computational drug discovery workflow from molecular analysis to docking and structural visualization.