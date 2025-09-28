# PPI Hotspot Analysis

**Computational Analysis of Protein–Protein Interaction Interfaces to Identify Critical Binding Residues**

This project identifies and visualizes *hotspot* residues—key amino acids that drive protein–protein binding.  
It parses PDB structures, builds an interaction network, and highlights residues most critical for stability or mutational sensitivity.

---

## Features
- **Automated PDB Parsing**: Uses Biopython to read 3D structures.
- **Interface Detection**: Finds residues within a user-defined cutoff distance.
- **Graph Analysis**: Builds an interaction network (NetworkX) to pinpoint central nodes.
- **Visualization**: Optional 3D rendering via py3Dmol.

---

## Repository Structure
ppi-hotspot-analysis/
│
├─ src/ # Core Python scripts
├─ data/ # Input PDB files
├─ notebooks/ # Jupyter notebooks (analysis / demos)
├─ results/ # Figures, CSVs, and output graphs
└─ README.md

---

python3 -m venv env
source env/bin/activate
pip install -r requirements.txt

---

python src/ppi_hotspot.py --pdb 1xyz --cutoff 5.0

Replace 1xyz with actual PDB ID or loacl file path.

---


