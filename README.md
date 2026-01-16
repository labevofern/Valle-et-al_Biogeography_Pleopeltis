# Valle-et-al_Biogeography_Pleopeltis

This repository contains data and scripts generated for the study:

Valle C, Salino A, Lima LV, Moura IO, Almeida TE. 2026. Mesoamerican roots: the biogeographic history of the fern genus Pleopeltis. Botanical Journal of the Linnean Society, in press.

Repository Contents
1. Species_occurrence_data.xlsx
Raw occurrence data compiled from biodiversity databases (GBIF and speciesLink). This file contains the georeferenced locality records used for distributional analyses.

2. Phylogenetic Data
DNA sequence alignments used for phylogenetic inference:

Alignment_rps4_gene.fas – Alignment for the rps4 gene.
Alignment_rps4_IGS_.fas – Alignment for the rps4 IGS spacer.
Alignment_trnL-F.fas – Alignment for the trnL-F region.
Alignment_rbcL.fas – Alignment for the rbcL gene.

3. Phylogenetic Output
MRCA_Pleopeltis_outputBeast.tre – The Maximum Clade Credibility (MCC) tree used for biogeographic analysis. This tree was generated from the posterior distribution of 1000 BEAST trees (with 10% burn-in discarded) using TreeAnnotator.

4. Analysis Script
scriptR_BioGOEBEARS_Pleopeltis.R – The complete R script used to perform biogeographic ancestral range reconstruction and Bayesian Stochastic Mapping (BSM) analyses in BioGeoBEARS.

Usage Notes
The .tre file can be opened in tree visualization software (e.g., FigTree, IcyTree) or read directly in R using packages like ape or phytools.

The R script (scriptR_BioGOEBEARS_Pleopeltis.R) requires the BioGeoBEARS package and its dependencies to run. It is provided for full reproducibility of the biogeographic analyses.

The raw occurrence data file is provided in its original compiled format for transparency.

Citation
If you use any of these data or scripts, please cite the original publication listed above.
