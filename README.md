# PPI Hotspot Analysis

Computational Analysis of Protein–Protein Interaction Interfaces to Identify Critical Binding Residues

---

## Overview

This project identifies and visualizes *hotspot* residues—key amino acids that drive protein–protein binding.  
It parses PDB structures, builds an interaction network, and highlights residues most critical for stability or mutational sensitivity.

---

## Features
- Automated PDB Parsing: Uses Biopython to read 3D structures.
- Interface Detection: Finds residues within a user-defined cutoff distance.
- Graph Analysis: Builds an interaction network (NetworkX) to pinpoint central nodes.
- Visualization: Optional 3D rendering via py3Dmol.

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/YOUR_USERNAME/PPI-hotspot-analysis.git
cd PPI-hotspot-analysis
```

2. **Installation Dependencies**

```bash
pip install -r requirements.txt
```


