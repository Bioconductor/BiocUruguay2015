This package contains some of the course material for 'R Bio:
Untangling Genomes' offered in Uruguay in October, 2015. Material in
this package can be found in the 'vignettes' directory, and includes:

- (T) Introduction to R / Bioconductor
- (P) Working with Data: `eSet` and `SummarizedExperiment`
- (P) Genomic Ranges For Genome-Scale Data And Annotation
- (P) Adding Annotation To Your Analysis
- (P) Counting Reads And Working With Large Files
- (P) RNA-Seq Differential Expression
- (P) ChIP-Seq For Understanding Gene Regulation
- (P) Motifs
- (P) Visualizing Genomic Data


(T: Talk, P: Practical) 

The material requires R version 3.2.1 or 3.2.2. To install the
packages used in this course, evaluate the following commands:

    source("http://bioconductor.org/biocLite.R")
    biocLite("Bioconductor/BiocUruguay2015")
    biocLite(packageDescription("BiocUruguay2015")$Suggests)
