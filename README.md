# Mid-Cayman Rise microbial eukaryote study

Sarah Hu _In preparation_

https://shu251.github.io/midcayman-rise-microeuk/

Sequences [![DOI](https://img.shields.io/badge/NSF-OCE0939564-blue.svg)](https://www.bco-dmo.org/dataset/828392)

[SRA sequence](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA802868/)

## Premise

Deep-sea hydrothermal vent geochemistry shapes the foundation of the microbial food web by fueling chemolithoautotrophic microbial activity. Microbial eukaryotes play a critical role in hydrothermal vent food webs as consumers, hosts of symbiotic bacteria, and as a nutritional source to higher trophic levels. This study aims to measure the cell concentration and grazing pressures of vent-associated microbial eukaryotes in low temperature diffuse hydrothermal fluids using grazing assays conducted at both ambient (shipboard) and in situ pressures. Fluids from the Von Damm and Piccard vent fields at the Mid-Cayman Rise in the Caribbean Sea were targeted, as each field represents a distinct geologic setting with correspondingly distinct fluid compositions. Results from in situ pressure experiments generally showed higher grazing rates and cell concentrations relative to the shipboard experiments, likely due to the impact of depressurization. This new quantification of protistan biomass in deep-sea hydrothermal vent ecosystems contributes to a more comprehensive understanding of the microbial food web in these environments. Hydrothermally-fuelled microbial food webs play a significant role in the broader deep-sea carbon budget by contributing to local carbon export and supply of nutrient resources to the deep ocean.


## File summary

List of needed files to run code

```input-data/```
* MCR-amplicon-data.RData
* table_wenv.txt
* samplelist-metadata.csv
* euk-counts-compiled.txt
* raw-avg-eukcount.RData
* prokINSITU-counts-compiled.txt
* cellcount_previousyr.csv
* flp-exp-metadata-compiled.txt
* flp_exp_metadata.csv
* bac-counts-compiled.txt
* biovol-euk-12-10-2020.txt
* md-lessard-2000.txt

```output-data/```
* supp-table-sequencestats.csv
* supp_table_MCR_metadata.csv
* MCR-cellcount-dfs
* table-wcalc.txt
* grazing-cellcounts-GR_MCR.txt
* tables1-grazing-exp-list.txt

### Quarto navigation

Main page, see index.qmd and _quarto.yml for navigation. 
To update, Render all documents. Output to ```/docs``` where gitpage is hosted. Add, commit, and push changes to update site.
