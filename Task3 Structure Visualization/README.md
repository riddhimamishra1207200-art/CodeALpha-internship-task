# Task 3: Protein Structure Prediction & Visualization

**Internship:** CodeAlpha Bioinformatics Internship
**Protein studied:** Haemoglobin Subunit Beta (HBB) — structural analysis

## Overview
This task involved predicting and visualizing the 3D structure of HBB to explain, at a structural level, why the Glu6Val mutation identified in Tasks 1 and 2 causes sickle cell anaemia.

## Approach
- Retrieved the AlphaFold-predicted structure of human HBB (UniProt P68871) from AlphaFold DB
- Visualized the structure in PyMOL: overall cartoon fold, residue 6 highlighted (stick representation), and a surface representation to assess solvent exposure
- Additionally retrieved the experimentally solved haemoglobin structure (PDB ID: 1A3N) to visualize the full four-subunit tetramer and its four heme groups, since heme is not included in AlphaFold's sequence-based predictions

## Key Findings
- Residue 6 is located on the exposed outer surface of the protein, not buried in its core
- This explains the mechanism behind sickle cell anaemia: replacing the normal, water-attracting Glutamic acid with hydrophobic Valine at an exposed surface position creates a "sticky" patch, causing mutated hemoglobin molecules to clump into rigid fibres that distort red blood cells
- The real structure (1A3N) confirmed hemoglobin's four-subunit architecture, with one heme group embedded in each subunit for oxygen binding
- Together with Tasks 1 and 2, this provides a complete explanation of the sickle cell mutation — from sequence, to evolutionary conservation, to physical structure

## Files
- Full analysis report (Word document)
- PyMOL visualizations: overall structure, residue 6 highlight, surface exposure, and heme group structure (4 images)
