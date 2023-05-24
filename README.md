# Patel_Study
### Xiaonan Wang
### 24May2023
## Summary: Data analysis of Patel Study

# Abstract
Aged hematopoietic stem cells (HSC) display diminished self-renewal and a myeloid
differentiation bias. However, the physiological drivers and molecular processes that
underpin this fundamental switch are not understood. HSCs produce formaldehyde
and are protected from this metabolite by two tiers of protection: the detoxification
enzymes ALDH2 and ADH5 and the Fanconi anemia (FA) DNA repair pathway. Using
single cell RNA sequencing, we find that the HSC and progenitor cells in young Aldh2-
/- Fancd2-/- mice harbor a transcriptomic signature equivalent to aged wild-type HSCs,
along with increased epigenetic age, telomere attrition and myeloid-biased
progenitors. In addition, the p53 response is vigorously activated in Aldh2-/- Fancd2-/-
HSCs, whilst p53 deletion rescued this aged transcriptomic signature and telomere
attrition. Transplantation of single Aldh2-/- Fancd2-/- HSCs also reveals a predominantly
myeloid output, which is reversed upon p53 deletion. To further define the origins of
the myeloid differentiation bias, a GFP genetic reporter which detects Vwf+ myeloidprimed HSCs was crossed into Aldh2-/- Fancd2-/- mice, revealing a striking enrichment
of these lineage-biased Vwf+ HSCs. These results indicate that metabolism derived
formaldehyde causes endogenous DNA damage which stimulates the p53 response
in HSCs, which then accelerates their aging, resulting in a myeloid lineage biased
output.

Mouse bone marrow Lin-Sca1+cKit+ cells from 6 genotypes:
1. WT
2. Aldh2-/- (Aldh2KO)
3. Fancd2-/- (Fancd2KO)
4. p53-/- (p53KO)
5. Aldh2-/-Fancd2-/- double knock-out (DKO)
6. Aldh2-/-Fancd2-/-p53-/- triple knock-out (TKO)

The cells were sorted using the Smart-Seq2 method and sequenced using the Illumina platform. In total, there were 2554 cells passed QC and were submitted onto GEO with accession number **GSE209742**.

## scRNASeq_SMQ2
This directory should have figures:
- **Figure1**: Fig1B, Fig1C
- **Figure2**: Fig2B, Fig2C
- **Figure3**: Fig3A, Fig3B, Fig3C
- **Figure4**: Fig4A, Fig4B, Fig4C
- **Figure5**: Fig5A, Fig5B, Fig5C, Fig5D
- **Figure6**: Fig6D, Fig6E
- **FigureS2**: FigS2B, FigS2C
- **FigureS3**: FigS3A, FigS3B
- **FigureS4**: FigS4A, FigS4B
- **FigureS5**: FigS5A, FigS5B, FigS5D

The analysis include:
  - <ins>**[Patel_all](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Patel_SMQ2_analysis.ipynb)**</ins>: Analysis of all cells in general, then split into EryA and LSK
  - <ins>**[Patel_LSK1](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Patel_SMQ2_LSK_analysis_part1.ipynb)**</ins>: Pre-processing of LSK cells
  - <ins>**[Patel_LSK2](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Patel_SMQ2_LSK_analysis_part2.ipynb)**</ins>: Downstream analysis of LSK cells
  - <ins>**[Patel_LSK_proj1](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Project_LSK_onto_Dahlin_landscape.ipynb)**</ins>: Cell type annotation using the [Dahlin haematopoietic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/) as reference
  - <ins>**[Patel_LSK_proj2](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Project_LSK_onto_Nestorowa_landscape.ipynb)**</ins>: Cell type annotation using the [Nestorowa haematopoietic landscape](https://pubmed.ncbi.nlm.nih.gov/27365425/) as reference
  - <ins>**[Aging_score](https://github.com/SharonWang/Patel_Study/blob/master/scRNASeq_SMQ2/Ageing_Score_Cal.ipynb)**</ins>: Aging score calculation using the top 20 defined aging genes

## WT_Ageing_Data
To investigate the impact of aging, mouse bone marrow Lin-cKit+ cells from 3 conditions:
1. Young WT (16-weeks)
2. Old WT (68-weeks)
3. Older Hetero Fancd2 (88-weeks)

This directory should have figures:
- **Figure2**: Fig2A
- **Figure6**: Fig6B
- **FigureS7**: FigS7

The analysis include:
  - <ins>**[Aging_Preprocess](https://github.com/SharonWang/Patel_Study/blob/master/WT_Ageing_Data/Ageing_mice_preanalysis.ipynb)**</ins>: Pre-processing of the aging data
  - <ins>**[Aging_proj1](https://github.com/SharonWang/Patel_Study/blob/master/WT_Ageing_Data/Project_onto_Dahlin_Landscape.ipynb)**</ins>: Cell type annotation using the [Dahlin haematopoietic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/) as reference
  - <ins>**[Aging_proj2](https://github.com/SharonWang/Patel_Study/blob/master/WT_Ageing_Data/Project_onto_Nestorowa_Landscape.ipynb)**</ins>: Cell type annotation using the [Nestorowa haematopoietic landscape](https://pubmed.ncbi.nlm.nih.gov/27365425/) as reference
  - <ins>**[Aging_score](https://github.com/SharonWang/Patel_Study/blob/master/WT_Ageing_Data/Ageing_Score_Cal.ipynb)**</ins>: Aging score calculation using the top 20 defined aging genes
  - <ins>**[p53_score](https://github.com/SharonWang/Patel_Study/blob/master/WT_Ageing_Data/p53_Score_Cal.ipynb)**</ins>:
p53 score calculation using the 16 defined p53-associated target genes

## GSE157832_Aldh2_Adh5
The datasets were downloaded from [GSE157832](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE157832) from [Dingler et al., Mol Cell. 2020](https://pubmed.ncbi.nlm.nih.gov/33147438/).

This directory should have figures:
- **Figure2**: Fig2G
- **Figure3**: Fig3D
- **FigureS5**: FigS5C

The analysis include:
  - <ins>**[Aldh2_Adh5_Preprocess](https://github.com/SharonWang/Patel_Study/blob/master/GSE157832_Aldh2_Adh5/Aldh2_Adh5_preanalysis.ipynb)**</ins>: Pre-processing of the Aldh2_Adh5 10X LK data
  - <ins>**[Aldh2_Adh5_HSPC](https://github.com/SharonWang/Patel_Study/blob/master/GSE157832_Aldh2_Adh5/HSPC_analysis.ipynb)**</ins>: HSPCs were extracted from the LK data and been processed
  - <ins>**[Aldh2_Adh5_proj1](https://github.com/SharonWang/Patel_Study/blob/master/GSE157832_Aldh2_Adh5/Project_onto_Dahlin_Landscape.ipynb)**</ins>: Cell type annotation using the [Dahlin haematopoietic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/) as reference
  - <ins>**[Aldh2_Adh5_proj2](https://github.com/SharonWang/Patel_Study/blob/master/GSE157832_Aldh2_Adh5/Project_onto_Nestorowa_Landscape.ipynb)**</ins>: Cell type annotation using the [Nestorowa haematopoietic landscape](https://pubmed.ncbi.nlm.nih.gov/27365425/) as reference
  - <ins>**[Aging_score](https://github.com/SharonWang/Patel_Study/blob/master/GSE157832_Aldh2_Adh5/Ageing_Score_Cal.ipynb)**</ins>: Aging score calculation using the top 20 defined aging genes

## GSE116256_HumanAML
The human AML dataset downloaded from [GEO:GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256) from [Galen et al., Cell 2019](https://pubmed.ncbi.nlm.nih.gov/30827681/).

This directory should have figures:
- **Figure5**: Fig5E

The analysis include:
  - <ins>**[Human_AML](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Human_AMLdata.ipynb)**</ins>: 
