# Poster No. 25 tRNA Charging and Methionine: Exploring bacterial metabolic mechanisms in Prostate Cancer
*Seshadhri Subramanian, Dr. Rachel Hurst, Dr. Abraham Gihawi, Prof. Colin Cooper, Prof. Daniel Brewer*

## Abstract

### Introduction
Prostate cancer is one of the most common cancers in the world (1 in 8 men will be diagnosed). The main risk factors are old
age, ethnicity and familial history. Infection has also been established as a risk factor in many cancers. Prostate cancer is also
influenced by many bacteria in the prostate microbiome. The identification of the Anaerobic Bacterial Biomarker Set (ABBS)
bacteria could help identify patients at risk of developing aggressive prostate cancer. The five ABBS species so far are from the
following genera – Fenollaria, Peptoniphilus, Anaerococcus, Porphyromonas, and Fusobacterium. Patients with the ABBS
bacteria in them tend to have more aggressive cancers and lower long-term survival. What remains unclear are the metabolic
mechanisms by which the ABBS bacteria act in these cancers.

### Objectives
To use bioinformatics packages on The Pan Prostate Cancer Group whole genome sequencing dataset to determine the
metabolic mechanisms which are enhanced in ABBS-positive versus ABBS-negative cancer patients.

###  Methods
867 tumour samples from the Pan-Prostate Cancer Group (PPCG) dataset were examined for this study. 164 were ABBS-positive
tumours and 704 were ABBS-negative tumours. HUMAnN (HMP Unified Metabolic Analysis Network) were used to analyse
metabolic profiles of these two sets of samples from sequencing data. Analysis was done using a Snakemake pipeline to run
HUMAnN version 3.7 and carried out on the High Performance Computing Cluster supported by the Research and Specialist
Computing Support Service at UEA. The three output files of HUMAnN denoting the abundance and names of Gene families
(grouped by Enzyme Commission number to level 4 using the Uniref90 database), Path abundance and Path coverage are taken
forward for further analysis together with a metadata file. This is done using the Maaslin2 – Microbiome Multivariable
Associations with Linear Models - (version 1.12.0) package on R. Maaslin2 correlated the association between ABBS status
(positivity or negativity) and the gene families that are significantly associated with this. A similar output was generated for path
abundance

### Results
667 gene families and 207 pathways were deemed to be significantly associated with ABBS positivity when the PPCG data was
analysed. tRNA charging pathway genes – tRNA synthetases – for all the 20 amino acids are significantly associated with ABBS
positivity with Glutamine, Valine and Aspartate among the most significant. ABBS positive tumours demonstrate a highly
significant association with pathways that either synthesise or salvage methionine.

### Discussion
tRNA charging which is undertaken by tRNA synthetases refers to the aminoacylation of tRNA through aminoacyl-tRNA
synthetases (ARSs) to form an amino-acyl tRNA which can then allow for the formation of peptide bonds. Tumour suppression
programmes are shown to be inactivated when leucyl-tRNA synthetase is downregulated.Cancer cells can be distinguished from
normal cells due to their dependence on exogenous methionine – Hoffman effect. It has been shown that under methioninerestricted conditions, cancer cells can stop in the S/G2 phases of the cell cycle and altered methionine metabolism may be an
underlying principle behind cancer development.Thus increased tRNA charging and methionine synthesis/salvage could be very
important pathways in aggressive ABBS positive tumours.
### Keywords

prostate cancer; bacteria; microbiome; bioinformatics; cancer; R; ppcg; tRNA; methionine
