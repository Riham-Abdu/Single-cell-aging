# Single-cell-aging
## Overview
This project studies how aging affects bone marrow using single-cell RNA sequencing data.  
We compare young and old donors to understand how cell populations change with age.

## Data
- ~49,000 bone marrow cells from healthy donors  
- Includes both young and old individuals  
- Each cell has gene expression and cell type labels  

## Methods
- PCA and UMAP for visualization  
- Leiden clustering to group cells  
- PHATE to capture structure  
- MELD to detect age-related patterns  

## Key Findings
- Cell type (not age) is the main driver of variation  
- Young and old cells overlap globally  
- Aging changes cell composition:
  - Older -> more mature immune cells  
  - Younger -> more progenitor cells  
- Aging effects are subtle and local  

## Takeaway
Aging reduces stem/progenitor activity and increases mature immune cells in bone marrow.

## Limitations
- Small sample size  
- Limited gene panel  
- Results are exploratory  

## Structure
- data/
- analysis/
- presentation/
- figures/

## Slides
See presentation/ for slides
