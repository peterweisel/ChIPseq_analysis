# ChIP-seq Analysis for Cut14 in S. pombe

## Overview

This repository contains scripts for the analysis of ChIP-seq data for the Cut14 protein in fission yeast. The analysis includes Bowtie2 alignment, peak calling, and quantification of protein binding across RNA polymerase II transcribed genes.

## Scripts

1. [bowtie2_mapping_alignment.sh]: Shell script for aligning paired-end ChIP-seq FASTQ files to the Bowtie2 reference genome.

2. [PeakCalling_MACS2.sh]: Shell script for performing peak calling using MACS2 on ChIP-seq treatment and control samples.

3. [average_score_groups.sh]: Shell script for quantifying protein binding across different genes based on expression levels.

4. [average_score_pol2_groups.R]: R script for visualizing average protein binding at RNAP2 transcribed genes based on location.

## Results

### Average score of protein binding of Cut14 across RNA polymerase II transcribed genes of differing expression levels
<img width="726" alt="Cut14_expression_gp" src="https://github.com/peterweisel/ChIPseq_analysis/assets/116852337/6c0bd64e-1871-4fc7-bef8-49ab240c0b70">

### Genome coverage of Cut14 across fission yeast genome
<img width="726" alt="IGV_Cut14" src="https://github.com/peterweisel/ChIPseq_analysis/assets/116852337/74cb3469-5a85-4d35-aa9b-b5682c8856f5">

