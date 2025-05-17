# GD3-Transcriptomic-Outputs
The repository is organized to include both raw and processed data, as well as intermediate results such as pathway gene sets, biomarker intersections, and drug prediction outcomes. The aim is to ensure full transparency, reproducibility, and accessibility of the analytical pipeline applied in the study.
 
# Repository Structure
GEO2R_outputs/
Contains original output files (.tsv) from GEO2R analysis of dataset GSE21899 for GD1 vs Control and GD3 vs Control comparisons.

Filtered_DEGs/
Curated and threshold-filtered DEG lists (adjusted p-value < 0.05 and |log2FC| > 0.585) used in all downstream analyses.

WP2004_pathway_data/
Includes gene sets retrieved from WikiPathways (WP2004: miRNA targeted genes in lymphocytes), in .tsv and .xlsx formats.

Intersection_and_Biomarkers/
Files showing overlapping genes between GD3-specific DEGs and the WP2004 pathway. Includes biomarker classification as upregulated or downregulated.

Drug_Repositioning/
Results obtained from the L1000CDS² platform based on GD3-specific biomarkers. File includes ranked compounds and metadata.

# Thesis Citation
Title: Transcriptomic-Guided Drug Repositioning in Gaucher Disease Type 3

Author: Berrenur İnandı

Institution: Department of Engineering and Natural Sciences, Istanbul Medeniyet University

Year: 2025

Note: This dataset is part of an undergraduate thesis and not intended for clinical use without further validation.
