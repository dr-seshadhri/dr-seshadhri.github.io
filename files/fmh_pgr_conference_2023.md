# P-15 Specific Bacteria in Urine Can Indicate Higher Risk for Aggressive Prostate Cancer
*Seshadhri Subramanian, Dr. Rachel Hurst, Dr. Abraham Gihawi, Prof. Colin Cooper, Prof. Daniel Brewer*

## Abstract

### Background
Prostate cancer is one of the most common cancers in the world. Infectious causes for cancer are
well documented. A group of five bacteria genera called the Anaerobic Bacteria Biomarker Set
(ABBS) (1), may help to identify the risk of developing aggressive prostate cancer.

### Objectives of Study
To detect bacteria in urine using 16S bacterial sequencing data, and to compare bacteria profiles
across samples from participants with different grades of prostate cancer.

### Methods
Urine samples from a total of n=46 participants were subjected to 16S rRNA Illumina sequencing
and the results were analysed through the DADA2 pipeline to give an output of number of reads for
each amplicon sequence variant (ASV).

### Analysis
The analysis on the family level taxonomic results was completed using the Phyloseq package in
R. A heatmap of abundances was produced. K-Means clustering was done with Manhattan
distances on a Principal Co-Ordinate Analysis Plot to reveal clusters of participant samples based
on bacterial families.

### Results
The participant urine samples clustered into three groups in terms of their bacterial communities.
One group demonstrated a higher proportion of participants that developed metastases, n=5 out of
6 samples from patients with prostate cancer metastasis were in one cluster while there was only 1
sample in the other two clusters.

### Conclusions/Recommendations
The results show that participants with metastatic prostate cancer tend to group in one cluster
when they are clustered on bacteria taxa at the family level. The data analysed indicates that
specific bacteria that contribute to the urine microbiome may indicate a higher chance of
aggressive prostate cancer.

### Impact
The outcome of this research may help detect patients at risk of aggressive prostate cancer early
and lead to potential treatment options in the future.

### Keywords

prostate cancer; bacteria; microbiome; bioinformatics; cancer; R
