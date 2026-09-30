# Talk: In-silico functional profiles of anaerobic bacteria in prostate cancer
*Seshadhri Subramanian, Dr. Rachel Hurst, Dr. Abraham Gihawi, Prof. Colin Cooper, Prof. Daniel Brewer*

## Abstract

### Introduction
Prostate cancer is among the most common cancers globally (1 in 8 men in the UK
will be diagnosed in their lifetime). Major risk factors include age, ethnicity, and family
history. Microbial infections contribute to many cancers, and the prostate microbiome
influences prostate cancer. Identifying the Anaerobic Bacterial Biomarker Set (ABBS)
bacteria—Fenollaria, Ezakiella, Peptoniphilus, Anaerococcus, Porphyromonas, and
Fusobacterium—may help predict aggressive prostate cancer at diagnosis. ABBSpositive samples are linked to more aggressive disease, and the mechanisms of
actions of these bacteria are important to investigate.

### Materials and methods
Whole genome sequencing data from 650 tumour samples in the Pan-Prostate Cancer
Group (PPCG) were analysed for microbial content. Unmapped reads were qualitytrimmed, human-depleted, and classified using Kraken. The metabolic profiles of
ABBS-positive and negative samples were assessed using HUMAnN (v3.7). Gene
families and pathways were analysed with Maaslin2 (v1.12.0) in R (v4.2.0).

### Results and Discussion
ABBS-positive tumours had 888 significantly enriched gene families and 336
metabolic pathways, including genes for tRNA synthetases for all 20 amino acids and
methionine synthesis/salvage pathways. This was significantly higher than the 75
gene families and 17 pathways found in ABBS-negative tumours. Key ABBSassociated pathways include methionine salvage/synthesis and tRNA charging.
Cancer cells rely heavily on external methionine (Hoffman effect) and arrest in the
S/G2 cell cycle phase under methionine restriction. Methionine metabolism may be a
core feature of cancer development. tRNA charging, facilitated by aminoacyl-tRNA
synthetases (ARSs), enables peptide bond formation. Aberrant ARS expression is
linked to the transformation from benign to malignant cells, with ARS-encoding genes
exhibiting expression profiles similar to Cancer-Associated Genes (CAGs) in 10
cancers.

### Conclusion
These findings suggest microbial metabolism may contribute to prostate cancer
progression when ABBS bacteria are present. Future work will look at mutational
profiles in the PPCG that are associated with ABBS positive tumours, identifying
additional bacteria with a similar metabolic profile and investigating the relationship of
enzymes and pathways affected in ABBS positive tumours with long term survival in
ABBS positive patients.

### Keywords

prostate cancer; bacteria; microbiome; bioinformatics; cancer; R
