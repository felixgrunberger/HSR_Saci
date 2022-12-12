Transcriptional and translational dynamics underlying heat shock
response in the thermophilic Crenarchaeon *Sulfolobus acidocaldarius*
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

------------------------------------------------------------------------

## About this repository

This is the repository for the manuscript “Insights into rRNA processing
and modifications in Archaea using Nanopore-based RNA sequencing”.

The repository is currently actively developed.

[![Active
Development](https://img.shields.io/badge/Maintenance%20Level-Actively%20Developed-brightgreen.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

<!--## Full documentation here  
https://felixgrunberger.github.io/rRNA_maturation/
-->

## Preprint

This work is based on our previous preprint: [Exploring prokaryotic
transcription, operon structures, rRNA maturation and modifications
using Nanopore-based native RNA
sequencing.](%22https://www.biorxiv.org/content/10.1101/2019.12.18.880849v2.full%22)

## What can you find here

A description of the workflow using publicly available tools used to
basecall, demultiplex, trim and map (*direct cDNA*) data and data
preparation for modified base detection (*using direct RNA*) can be
found in the [pipeline](pipeline) section.

Downstream analysis, including  
- quality control  
- detection of rRNA processing sites and classification of rRNA
intermediates  
- Circular RNA detection  
- Modified base detection  
are based on custom Rscripts that are also described in the
[pipeline](pipeline) section.

## Data availability

Raw direct RNA data (gzipped raw FAST5 files) have been uploaded to the
Sequence Read Archive (SRA) and are available under project accession
number [PRJNA632538](https://www.ncbi.nlm.nih.gov/sra/?term=PRJNA632538)
(WT run: SRR11991303, ∆KsgA run: SRR11991308).  
Direct cDNA data are available at the European Nucleotide Archive (ENA,
<https://www.ebi.ac.uk/ena>) under project accession number PRJEB57168.
ERP142133 ERR10466882

------------------------------------------------------------------------

## License

This project is under the general MIT License - see the
[LICENSE](LICENSE) file for details
