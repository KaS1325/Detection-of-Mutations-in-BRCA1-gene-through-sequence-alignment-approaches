#  BRCA1 Mutation Study Using Sequence Alignment

This project presents a comparative analysis of the *BRCA1 gene* between Homo sapiens (human) and Mus musculus (mouse) using sequence alignment approaches via NCBI BLAST. The goal is to identify conserved regions, detect mutations, and understand evolutionary divergence relevant to cancer research and bioinformatics.

---

##  Project Overview

- *Title*: Detection of Mutations in BRCA1 Gene Through Sequence Alignment Approaches
- *Tools Used*: NCBI BLASTn, FASTA format sequences, GenBank
- *Focus*: Comparative genomics, gene mutation analysis, sequence similarity search
- *Target Audience*: Biotech students, bioinformatics researchers, and genomic data analysts

---

##  Research Objective

1. Retrieve BRCA1 gene sequences from human and mouse from NCBI.
2. Align human BRCA1 mRNA against mouse BRCA1 mRNA using BLASTn.
3. Identify regions of conservation and mutation.
4. Analyze functional implications of mutations.

---

##  Materials & Methods

- *Query Sequence*: Human BRCA1 mRNA (Accession: [NM_007294.4](https://www.ncbi.nlm.nih.gov/nuccore/NM_007294.4))
- *Subject Sequence*: Mouse BRCA1 mRNA (Accession: [U36475.1](https://www.ncbi.nlm.nih.gov/nuccore/U36475.1))
- *Database*: NCBI Nucleotide collection (nr/nt)
- *Platform*: NCBI BLASTn online tool
- *Alignment Type*: Local pairwise alignment using megablast

See methods.md for a complete step-by-step protocol.

---

##  Results Summary

- *% Identity*: ~76%
- *Alignment Length*: 6469 bp
- *Gaps*: 109 (~3%)
- *Accession of best match*: U36475.1

BLAST alignment output showed substantial sequence conservation between human and mouse BRCA1, with several regions showing point mutations and small indels.

For details, see:
- results.md → numerical summary
- alignment.fasta → aligned sequences
- alignment_screenshot.jpg → visual output

---

##  Discussion Highlights

- Conserved regions suggest functional significance, especially in DNA repair domains.
- Mismatches and gaps could point to species-specific regulatory or non-critical sequence evolution.
- Findings validate the use of mouse as a model organism but highlight the importance of validating mutation impacts.

See discussion.md for detailed interpretation.

---

