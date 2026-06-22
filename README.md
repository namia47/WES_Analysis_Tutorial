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

1. Click the [![Open In Colab](
https://colab.research.google.com/assets/colab-badge.svg
)](
https://colab.research.google.com/github/namia47/WES_Analysis_Tutorial/blob/main/notebooks/WES_Variant_Calling_Workflow.ipynb
)
3. Mount Google Drive.
4. Upload or link your FASTQ files.
5. Download the required reference files.
6. Run the notebook cells sequentially.

**<span style="color:grean"> No local installation is required.</span>**

## Project Status

| Notebook | Status |
|-----------|--------|
| Germline Variant Calling | ✅ Complete |
| Variant Annotation | 🚧 Planned |
| Variant Prioritization | 🚧 Planned |
| ACMG Interpretation | 🚧 Planned |

