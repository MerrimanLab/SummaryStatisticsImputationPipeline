# SummaryStatisticsImputationPipeline

Imputation pipeline for GWAS summary statistics.

## Processing phases

- *Phase 1*: Download and convert 1000 genomes phase 3 into the appropriate format.
- *Phase 2*: Impute summary statistics using Impg-Summary.  

## Tools in use.

- Impg-Summary (http://bogdan.bioinformatics.ucla.edu/software/impg/) [1]
- GNU Parallel (http://www.gnu.org/software/parallel/) [2]
- R (https://www.r-project.org/) [3]

## References

- [1] Pasaniuc, Bogdan, Noah Zaitlen, Huwenbo Shi, Gaurav Bhatia, Alexander Gusev, Joseph Pickrell, Joel Hirschhorn, David P. Strachan, Nick Patterson, and Alkes L. Price. 2014. “Fast and Accurate Imputation of Summary Statistics Enhances Evidence of Functional Enrichment.” Bioinformatics  30 (20): 2906–14.
- [2] Tange, Ole, and Others. 2011. “Gnu Parallel-the Command-Line Power Tool.” The USENIX Magazine 36 (1). usenix.org: 42–47.
- [3] Team, R. Core. 2015. “R: A Language and Environment for Statistical Computing. Vienna, Austria; 2014.” URL Http://www. R-Project. Org.
