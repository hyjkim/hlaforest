HLAforest is a tool for predicting the HLA haplotypes of an individual from high throughput sequencing data. It weights reads hierarchically to all reference sequences in the IMGT database in order to distribute evidence to the most likely HLA candidates.

HLAforest is optimized for RNA-seq data, where it obtains an overall 4 digit (unique peptide level) accuracy of 92% for the most diverse genes in the IMGT database. It can also be applied to WGS or exome data, albeit with reduced accuracy.

The software is availble through git. Clone a local copy with:

```
git clone https://code.google.com/p/hlaforest/ 
```