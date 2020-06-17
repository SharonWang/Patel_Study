# Patel_Study
### Xiaonan Wang
### 27May2020
## Summary: Data analysis of Patel Study

## Introduction
The data has been sequenced using both
  1. Smart-Seq2
  2. TenX
  
**The raw data files included in this study are listed below:**  

| SLX Number   | Species | Batch | Type                              | Project Manager | Collaborator | Published? | GEO | Location |
|--------------|---------|-------|-----------------------------------|-----------------|--------------|------------|-----|----------|
| SLX_14719    | mouse   | B1    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_14789    | mouse   | B1    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_14873_B1 | mouse   | B2    | Pools of cells, sequenced 2 times | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_14873_B2 | mouse   | B2    | Pools of cells, sequenced 2 times | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_14256    | mouse   | B3    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_14257    | mouse   | B3    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_16885    | mouse   | B4    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_16886    | mouse   | B4    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_16888    | mouse   | B4    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_16889    | mouse   | B4    |                                   | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_16890    | mouse   | B4    | pools of cells                    | Nicola          | KJ Patel     | no         |     | rfs      |
| SLX_18782    | mouse   | B1    | TenX                              | Nicola          | KJ Patel     | no         |     | rfs      |

## Notebooks_SMQ2
The analysis include:
  - <ins>**[Patel_all](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_SMQ2/Patel_SMQ2_analysis.ipynb)**</ins>: Analysis of all cells in general, then split into EryA and LSK
  - <ins>**[Patel_EryA](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_SMQ2/Patel_SMQ2_EryA_analysis.ipynb)**</ins>: Analysis of EryA cells
  - <ins>**[Patel_LSK](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_SMQ2/Patel_SMQ2_LSK_analysis.ipynb)**</ins>: Analysis of LSK cells
  - <ins>**[Patel_LSK_proj](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_SMQ2/Project_LSK_onto_Niki_landscape.ipynb)**</ins>: Projection of LSK cells onto [Niki haematopoeitic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/)
  - <ins>**[Patel_LSK_HSCscore_pred](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_SMQ2/HSCscore_prediction_LSK.ipynb)**</ins>: Calculation of HSCscores using [hscScore](https://github.com/fionahamey/hscScore) developed by Fiona Hamey. The orginal paper can be found [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6900257/).

## Notebooks_TenX
The analysis include:
  - <ins>**[Patel_LK](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_TenX/Patel_TenX_analysis.ipynb)**</ins>: Analysis of all cells
  - <ins>**[Patel_LK_proj](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_TenX/Project_onto_Niki_landscape.ipynb)**</ins>: Projection of LK cells onto [Niki haematopoeitic landscape](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969381/)
  - <ins>**[Patel_LK_HSCscore_pred](https://github.com/SharonWang/Patel_Study/blob/master/Notebooks_TenX/HSCscore_prediction.ipynb)**</ins>: Calculation of HSCscores using [hscScore](https://github.com/fionahamey/hscScore) developed by Fiona Hamey. The orginal paper can be found [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6900257/).

