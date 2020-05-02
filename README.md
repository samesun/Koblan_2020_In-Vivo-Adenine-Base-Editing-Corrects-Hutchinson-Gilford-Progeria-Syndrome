# Koblan_2020_In-Vivo-Adenine-Base-Editing-Corrects-Hutchinson-Gilford-Progeria-Syndrome
Scripts used in In Vivo Adenine Base Editing Corrects Hutchinson-Gilford Progeria Syndrome. 
 
# Preprocessing and Alignment 
Scripts are designed for used on the Cannon High Performance Computing Cluster at Harvard (SLURM scheduler).

## Trim reads:

### Requirements:

Trimmomatic - http://www.usadellab.org/cms/?page=trimmomatic

run Trimmomatic.sh

## Perform 2-Pass STAR alignment to genome:

### Requirements: 

STAR - https://github.com/alexdobin/STAR

Reference genome - Ensemble (https://useast.ensembl.org/info/data/ftp/index.html)

### Index genome with STAR: 

### Align reads to indexed reference genome using STAR:

run STAR1stPASS.sh

# A to I quantification

## REDItools

https://github.com/BioinfoUNIBA/REDItools

## A to I quantification in R 

### Percent A to I 

### A to I sites 

# Differential Expression

## Counting

## Limma-Voom

## Visualization


