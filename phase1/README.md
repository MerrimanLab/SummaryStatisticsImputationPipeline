# Phase 1: 1000 genomes setup 

Download 1000 genomes VCFs and check md5 sums utilises download\_and\_check\_1kg.py
```bash

```

## Convert 1000 genomes VCF files to beagle using bcftools and vcf2beagle.


```
    # Download vcf2beagle.jar
    wget https://faculty.washington.edu/browning/beagle_utilities/utilities.html#vcf2beagle    
    parallel  "bcftools view {} -v snps | java -jar vcf2beagle.jar . output/{/.}" ::: *.vcf.gz
```
