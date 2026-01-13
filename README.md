# Gut microbial signatures expose the westernized lifestyle of urban Ethiopian children

This repository contains R Markdown analysis pipelines supporting the manuscript:

**“Gut microbial signatures expose the westernized lifestyle of urban Ethiopian children” (Communications Biology)**

The repository includes two independent workflows for:

1. 16S rRNA gene sequencing data processing and analysis using QIIME2  
2. Shotgun metagenomic data processing, taxonomic profiling, and functional pathway analysis  

These pipelines were developed to analyse fecal microbiome data from 207 urban Ethiopian children aged 2–5 years living in Adama, Ethiopia, and to enable transparent, reproducible microbiome research.

---

## Repository structure

- `Kirsche_et_al_16S_pipeline.rmd`  
  R Markdown workflow for QIIME2-based 16S rRNA gene sequencing analysis, including diversity analyses and downstream visualisation.

- `Kirsche_et_al_shotgun_metagenomics.rmd`  
  R Markdown workflow for shotgun metagenomic data processing, taxonomic profiling, and functional pathway analysis.

---

## Scientific context

The study investigates how an urban, westernized lifestyle in a developing country shapes the gut microbiome of young children, and how traditional dietary components such as fermented teff products may mitigate these effects.
The pipelines were used to generate the microbiome results reported in the associated manuscript.

---

## Requirements

- R ≥ 4.2  
- RStudio (recommended)  
- QIIME2 (for 16S processing pipeline)  
- Conda or mamba environment recommended for QIIME2  
- R packages listed at the end of each `.Rmd` file  

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

2. Open the desired `.Rmd` file in RStudio.
3. Adjust file paths and parameters in the configuration sections.
4. Execute the document to reproduce the analyses.

## Cite

If you use the data, or find this work useful, please cite:

### Gut microbial signatures expose the westernized lifestyle of urban Ethiopian children.
Lydia Kirsche, Peter Leary, Martin J. Blaser, Michael Scharl, Adugna Negussie and Anne Müller

The repository is archived on Zenodo with a DOI.

---

## Licence

This project is released under the MIT License.

---

## Contact

Lydia Kirsche  
Institute for Molecular Cancer Research  
University of Zurich

