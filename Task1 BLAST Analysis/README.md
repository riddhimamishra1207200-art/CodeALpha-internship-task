# Task 1: DNA/Protein Sequence Analysis (BLASTp)

**Internship:** CodeAlpha Bioinformatics Internship
**Protein studied:** Human Hemoglobin Subunit Beta (HBB), UniProt accession P68871

## Overview
This task involved retrieving the human HBB protein sequence from UniProt and running a protein BLAST (BLASTp) search against NCBI's non-redundant protein database to identify homologous sequences across species and detect clinically relevant variants.

## Approach
- Retrieved the canonical HBB sequence from UniProt (P68871)
- Automated the BLASTp search using Biopython (`Bio.Blast.NCBIWWW`), rather than the manual NCBI web interface, for a reproducible workflow
- Parsed the XML results to extract % identity, % query coverage, E-value, and bit score for the top 15 hits
- Visualized results with a % identity vs E-value scatter plot

## Key Findings
- Confirmed 100% identity to the canonical human HBB sequence
- Found 99.32% identity to gorilla HBB (1 amino acid difference), reflecting strong evolutionary conservation
- Independently discovered a known clinical variant, Hemoglobin O-Arab (Glu121Lys), within the BLAST results — demonstrating that HBB carries multiple documented disease-relevant mutation hotspots, not just the well-known sickle cell site
- Identified two Protein Data Bank (PDB) entries (1A3N, 7K4M) among the hits, providing real experimental 3D structures for further study

## Files
- Full analysis report (Word document)
- BLAST summary table (CSV)
- Identity vs E-value plot (PNG)
