# Ghana pilot data analysis
-----------------------
[![DOI](https://zenodo.org/badge/735254926.svg)](https://zenodo.org/doi/10.5281/zenodo.13764593)

Scripts and data for reproducing the "Analysis of DBLα tags from a cross-sectional study in Ghana". All the details of this analysis are in the appendix of my PhD thesis.

### Input data 

- sequence folder stores the ghana pilot dataset.

- data folder stores the isolate information for Ghana pilot data and the 3D7 reference sequences.

### The binary type analysis 

- The binary data are in OTU folder. 

- Scripts for generating RAxML tree and other binary type analysis are in scripts/R_scripts/Sup_ghana_1.Rmd.

### The FFP analysis

- The distance matrix generated by FFP method and other middle files are in ffp_data folder. 

- Scripts for generating FFP tree are in scripts/R_scripts/Sup_ghana_1.Rmd.

### Recombination analysis

- Scripts for running JHMM and collecting JHMM paramters are in scripts/R_scripts/run_JHMM folder.

- The mosaic representations of Ghana pilot data are stored in mosaic_processed_data/results_final_alignment folder.


### Reference
- Tonkin-Hill G, Ruybal-Pesántez S, Tiedje KE, Rougeron V, Duffy MF, Zakeri S,et al. Evolutionary analyses of the major variant surface antigen-encoding genesreveal population structure of *Plasmodium falciparum* within and between continents. PLoS Genetics. 2021;17(2):e1009269.
