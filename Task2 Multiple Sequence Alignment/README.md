# Task 2: Multiple Sequence Alignment (MSA)

**Internship:** CodeAlpha Bioinformatics Internship
**Protein studied:** Haemoglobin Subunit Beta (HBB) across 5 species

## Overview
This task involved aligning HBB protein sequences from five species using Clustal Omega to identify conserved and variable regions, building on the sequence similarity findings from Task 1.

## Approach
- Selected 5 species: human, gorilla, chimpanzee, and orangutan (primates, closely related) plus mouse (a more evolutionarily distant species, for contrast)
- Retrieved each sequence manually from UniProt, verifying correct gene identity (corrected an initial mix-up where orangutan and mouse entries matched the wrong, embryonic-stage globin genes)
- Ran the alignment using Clustal Omega (EBI web server)
- Interpreted the conservation symbols (*, :, .) across all three alignment blocks

## Key Findings
- The four primate sequences were nearly identical to one another, reflecting their recent shared evolutionary history
- The mouse sequence showed considerably more variation, consistent with a much older evolutionary divergence (~90 million years vs ~15–20 million years for primates)
- Position 6/7 (the site of the clinically significant Glu6Val sickle cell mutation) was fully conserved across all four primates, but differed in mouse (Alanine instead of Glutamic acid) — suggesting that the type of amino acid substitution, not just the presence of a change, determines whether a mutation is tolerated

## Files
- Full analysis report (Word document)
- Clustal Omega alignment output screenshots (coloured + plain text)
