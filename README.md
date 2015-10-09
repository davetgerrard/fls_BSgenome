
# Patterns and features on genomes in R: Biostrings, BSgenome and GenomicRanges.
## 'FLS' R group - October 2015
## Dave Gerrard

Biostrings, BSgenomes and GenomicRanges.

# PRE-REQUISITES --------------------------------
Multiple bioconductor packages but should get them all by doing this. 
try http if https is not available
```{r, eval=FALSE}
source("https://bioconductor.org/biocLite.R")
biocLite("BSgenome.Scerevisiae.UCSC.sacCer3")     # 'should' also install Biostrings, BSgenomes and GenomicRanges if not already installed.
```
# The Plan. --------------------------------------
Find instances of a DNA-sequence motif in a genome that also have evidence of binding from a ChIP-seq experiment.
1. Biostrings
2. BSgenome
3. GenomicRanges
