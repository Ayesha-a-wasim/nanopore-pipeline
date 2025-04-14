# nanopore-pipeline – Microbiome Analysis
Pipeline for Nanopore sequencing data Preprocessing and downstream analysis.

This repository contains a pipeline for downstream analysis of Nanopore sequencing data, focused on taxonomic classification and diversity analysis of microbiome samples, particularly from colorectal cancer patients.

## 🧬 Key Features
- Basecalling (Guppy/EPI2ME)
- Quality filtering and demultiplexing (fastqc, nanofilt)
- Taxonomic profiling using Kraken2 (in progress)
- Diversity analysis using R packages (phyloseq, vegan)
- Integration with QIIME2 for comparative analysis

## 🔧 Tools Used
- Nanopore Sequencing (MinION)
- QIIME2
- R: phyloseq, vegan
- Python (for preprocessing scripts)
- Snakemake (pipeline organization)

## 📂 Folder Structure
- `scripts/` – preprocessing and parsing scripts
- `results/` – processed data and outputs
- `README.md` – project overview

## 📈 Status
This pipeline is under development as part of my PhD project (MSCA Fellowship). Contributions and feedback are welcome.

## 📫 Contact
For questions or collaboration: ayesha.wasim@udc.es
