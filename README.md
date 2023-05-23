# NGS analysis (RNA-seq) in R
The analysis is based on the work by Rühl C and colleagues who performed the research on alternative splicing patterns in plants with increased and decreased levels of the 3 Arabidopsis Polypyrimidine-tract binding protein homologues in comparison to wild type samples, determined in duplicates.

The database includes, among others, two replicas of readings WT (wild type) and two replicas of readings: OE1, OE2, OE3 (over expressed). Further analysis focused on only OE1 and compared it to the wild type.

Source: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE41433

Analysis steps:
- alignment: Subread analysis
- visual examination: simple comparisons, logarithmic transformations, density plots
- differential expression analysis (DEA): Limma, EdgeR, DESeq2
- final conclusions
