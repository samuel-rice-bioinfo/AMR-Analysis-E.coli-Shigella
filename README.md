# Comparative Genomic and Structural Analysis of AMR Genes in Escherichia coli/Shigella

## Overview

This project presents a comparative pangenome and structural analysis of antimicrobial resistance (AMR) genes across three clinical Escherichia coli/Shigella strains (GN3, GN6, GN9) using E. coli K12 as a reference. Emphasis is placed on the mutational and structural divergence of AcrR paralogs, key transcriptional regulators of multidrug efflux pumps.

## Key Objectives

* Identify and compare AMR gene distribution across clinical isolates.
* Explore efflux pump diversity and regulation.
* Analyze mutational differences in AcrR paralogs (AcrR1, AcrR2).
* Model protein structures and assess conformational divergence.

## Tools and Technologies Used

* **Sequencing**: PacBio HiFi, SMRTbell Prep Kit
* **Assembly & Quality Control**: Flye, FastQC, Quast
* **Pangenome Analysis**: Panaroo
* **AMR Annotation**: Resistance Gene Identifier (RGI)
* **Homology Search**: Diamond BLASTX with VFDB
* **Data Visualization**: R (Upset plots, heatmaps, barplots)
* **Domain & Phylogeny**: InterPro, MEGA11
* **Structural Modelling**: ColabFold (AlphaFold2), PyMOL
* **Programming**: Python (Entrez for annotation), R

## Summary of Findings

* **135 AMR genes** were shared across all strains, with variation among others.
* **Efflux pumps** (RND, ABC, MFS) were the most dominant AMR mechanism.
* **AcrR paralogs** showed evidence of duplication and sub-functionalisation.
* **AcrR2** displayed significantly higher structural divergence, especially at the C-terminal domain.
* Structural differences suggest possible altered DNA/operator interaction and regulatory roles.

## File Contents

* `WRITEUP_FINAL.docx`: Full academic report with introduction, methods, results, discussion, and figures.
* Scripts for:

  * AMR gene extraction and comparison
  * Phylogenetic tree generation
  * Structural alignment and distance calculation

## Future Directions

* Expand strain comparisons to include additional clinical isolates.
* Integrate transcriptomic data to validate structural insights.
* Investigate operon-level regulation of efflux systems.
* Develop predictive tools for efflux-mediated AMR.

## Citation

If you use this repository, please cite the corresponding report and credit the original authors.
