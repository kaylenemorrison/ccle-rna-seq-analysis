# Exploratory Data Analysis of Stomach Cancer Cell Lines

differential expressional analysis of stomach cancer RNA-Seq data from Cancer Cell Line Encyclopedia


## Background

This project aims to identify genes that are differentially expressed between biologically distinct groups of 
stomach cancer cell lines—defined using PCA and hierarchical clustering—and to explore potential factors underlying the
differences between these groups

## Environment Setup 
This project uses renv for dependency management to ensure reproducibility.

# Install renv if not already installed
install.packages("renv")

# Restore the project environment
renv::restore()

## Directory Structure

ccle-rna-seq-analysis/
├── README.md                # Project overview and instructions
├── .gitignore               # files/folders to ignore in git
├── renv.lock / renv/        # for reproducible package management
├── data/
│   ├── raw/                 # Original, immutable data
│   └── processed/           # Cleaned data
├── code/
    ├── Analysis.qmd.        # bulk of the analysis (PCA, Hierachical clustering, Differential Expression)
    └── pre_process.qmd      # preprocesses data stored in raw/ and outputs into processed/
    
## Data

Go to <https://depmap.org/portal/data_page/?tab=allData>
    -   Check that "Select a file set to view" is set to "CCLE 2019"
    -   Download "CCLE_RNAseq_genes_counts_20180929.gct.gz"
    -   Download "Cell_lines_annotations_20181226.txt"



    
  

