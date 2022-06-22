# T2T-G42_WM_Genome

## <div align='center'>Watermelon G42 Genome</div>
### <div align='center'>Home | Search | Batch query | BLAST | Genome Browser | Pathway | [Download](http://www.watermelondb.cn/)</div>
+ Overview
    |**Full Name**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&thinsp;|Citrullus lanatus subsp. vulgaris cv. G42|
    |:-|:-|
    |**Genus**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|Citrullus|
    |**Species**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&thinsp;&thinsp;&thinsp;|lanatus|
    |**Subspecies**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|vulgaris|
    |**Cultivar**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&thinsp;&thinsp;&thinsp;|G42|
  
  
+ Feature 
    |**Feature Type**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Count**|
    |:-|-:|     
   |Chromosome&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;	11&emsp;&emsp;|
   |Gene&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;	24,205|
   |mRNA&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;	24,205|
   |Protein&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;	24,205|
+ Description  
    + To develop a high quality genome assembly for watermelon inbred line G42, different sequencing platforms were applied. We generated 20.62G (~55.9 coverage) HiFi reads by PacBio sequel II platform, and 21.08 Gb (~57.1 coverage) Oxford Nanopore Technology (ONT) ultra-long reads. The N50 length of HiFi reads was greater than 16 kb, whereas the N50 length of ONT reads was greater than 77 Kb. For the PacBio HiFi reads assemblies, the preliminary assembly applied Hifiasm on HiFi reads, generated contigs with the N50 length 32.5Mb. NextDenovo was used to assemble the ONT data, forming 11 contigs representing 11 chromosomes. To correct, order and orient the contigs of G42, 40.72 Gb chromosome conformation capture sequencing (Hi-C) data of G42 were generated.Then the gap-free ONT genome was used to fill the gaps of the HiFi assembled reference. After filling all remaining gaps, the gap-free reference genome was generated, which was named G42pku, containing 11 chromosomes with a total length of 369,321,829 bp. First, the Illumina mapping rate was 99.54% and the coverage was 99.96%. Secondly, BUSCO was used to evaluate genomic completeness. About 99.13% of the core conserved plant genes (1,600 out of 1,614 BUSCOs) were found complete in the G42 genome assembly. Finally, the LTR assembly index (LAI) value for G42 genome was 9.65. 24,205 protein-coding genes were predicted in our assembled genome. Using 500kb intervals across the 11 chromosomes, we counted the densities for GC content, genes, TEs, SNPs, and indels in the genome.
