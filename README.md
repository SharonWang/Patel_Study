# Patel_Study
### Xiaonan Wang
### 15July2022
## Summary: Data analysis of Patel Study - SmartSeq2

## Introduction
Mouse bone marrow Lin-Sca1+cKit+ cells from 6 genotypes:
1. WT
2. Aldh2-/-
3. Fancd2-/-
4. p53-/-
5. Aldh2-/-Fancd2-/- double knock-out 
6. Aldh2-/-Fancd2-/-p53-/- triple knock-out

The cells were sorted using the Smart-Seq2 method and sequenced using the Illumina platform. In total, there were 2554 cells passed QC and were submitted onto GEO with accession number xxx.

## Notebooks_SMQ2
The analysis include:
  - <ins>**[Patel_all](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Patel_SMQ2_analysis.ipynb)**</ins>: Analysis of all cells in general, then split into EryA and LSK
  - <ins>**[Patel_LSK1](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Patel_SMQ2_LSK_analysis_part1.ipynb)**</ins>: Pre-processing of LSK cells
  - <ins>**[Patel_LSK2](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Patel_SMQ2_LSK_analysis_part2.ipynb)**</ins>: Downstream analysis of LSK cells
  - <ins>**[Patel_LSK_proj1](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Project_LSK_onto_Dahlin_landscape.ipynb)**</ins>: Projection of LSK cells onto [Niki haematopoietic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/)
  - <ins>**[Patel_LSK_proj2](https://github.com/SharonWang/Patel_Study/tree/master/SMQ2_notebooks/Project_LSK_onto_Nestorowa_landscape.ipynb)**</ins>: Projection of LSK cells onto [Nestorowa haematopoietic landscape](https://pubmed.ncbi.nlm.nih.gov/27365425/)
