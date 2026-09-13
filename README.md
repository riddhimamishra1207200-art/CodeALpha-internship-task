# CodeAlpha Bioinformatics Internship — HBB Project

**Author:** [Riddhima Mishra]
**Internship:** CodeAlpha Bioinformatics Internship
**Focus protein:** Haemoglobin Subunit Beta (HBB) — UniProt P68871

## Project Overview

This repository documents a connected, three-part bioinformatics investigation into the human HBB protein, tracing a single well-known disease-causing mutation (Glu6Val, responsible for sickle cell anaemia) from its sequence, through its evolutionary conservation, to its physical structural explanation.

Rather than treating each task as an isolated exercise, this project builds one continuous story:

1. **Task 1 — Sequence Analysis (BLASTp):** Identified how similar HBB is across species and species records, and discovered an additional clinically relevant variant (Haemoglobin O-Arab) as an unexpected finding.
2. **Task 2 — Multiple Sequence Alignment:** Aligned HBB across 5 species (4 primates + mouse) to show that the sickle cell mutation site is conserved specifically within primates, hinting at why it is so mutation-sensitive.
3. **Task 3 — Structure Prediction & Visualization:** Used AlphaFold and PyMOL to show that the mutation site sits on the protein's exposed surface — explaining, at a physical level, why replacing Glutamic acid with hydrophobic Valine causes hemoglobin molecules to clump and deform red blood cells.

## Repository Structure

```
├── Task1_BLAST_Analysis/
│   ├── Task1_Report.docx
│   ├── hbb_blast_analysis.py       (Biopython automation script)
│   ├── blast_summary_table.csv
│   ├── blast_identity_vs_evalue.png
│   └── README.md
├── Task2_MSA/
│   ├── Task2_Report.docx
│   ├── alignment_screenshots/
│   └── README.md
├── Task3_Structure_Visualization/
│   ├── Task3_Report.docx
│   ├── structure_screenshots/
│   └── README.md
```

## Key Tools Used
- **Biopython** — automated NCBI BLASTp querying and XML parsing
- **NCBI BLAST** — sequence similarity search
- **UniProt** — sequence retrieval
- **Clustal Omega (EBI)** — multiple sequence alignment
- **AlphaFold DB** — predicted protein structure
- **PyMOL** — 3D molecular visualization
- **RCSB PDB** — real experimental structure (1A3N) for heme group visualization

## Summary of Findings
A single amino acid substitution (Glu6Val) in HBB is enough to cause sickle cell anaemia because this position is (1) highly conserved among primates, indicating functional importance, and (2) located on the protein's exposed surface, meaning that substituting a hydrophobic amino acid there creates an abnormal "sticky" patch — causing hemoglobin molecules to polymerize into rigid fibres and deform red blood cells into the characteristic sickle shape.# CodeALpha-internship-task
