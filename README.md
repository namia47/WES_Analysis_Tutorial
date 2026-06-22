# Germline Whole Exome Sequencing Analysis

**Author:** Eman Koosehlar

**Version:** *1.0*

**Status:** Ready to run in Google Colab

**Last Updated:** *June 2026*

## Overview

This repository contains an educational workflow for
germline Whole Exome Sequencing (WES) analysis using GATK.

**Pipeline:**

FASTQ
↓
FastQC
↓
BWA-MEM
↓
Sort BAM
↓
MarkDuplicates
↓
BQSR
↓
HaplotypeCaller
↓
Hard Filtering
↓
Filtered VCF

## Notebook Series

1. Germline Variant Calling
2. Variant Annotation (planned)
3. Variant Prioritization (planned)
4. ACMG Interpretation (planned)

## Quick Start

1. Click the **Open in Colab** button.
2. Mount Google Drive.
3. Upload or link your FASTQ files.
4. Download the required reference files.
5. Run the notebook cells sequentially.

**<span style="color:grean"> No local installation is required.</span>**

## Project Status

| Notebook | Status |
|-----------|--------|
| Germline Variant Calling | ✅ Complete |
| Variant Annotation | 🚧 Planned |
| Variant Prioritization | 🚧 Planned |
| ACMG Interpretation | 🚧 Planned |


WES-Analysis-Tutorial/

├── README.md
├── .gitignore
├── notebooks/
│   └── 01_Germline_WES.ipynb
│
└── figures/