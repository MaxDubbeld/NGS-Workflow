# NGS-Workflow
Workflow in Galaxy to perform a hybrid assembly, species identification and determine which antibiotics resistance genes are present resulting from paired-end ILLUMINA and Nanopore data.

## Tools
The different NGS tools used are:
1. **FastQC and MultiQC** -> *Quality Control*
2. **Trimmomatic** and **Porechop** -> *Trimming and Filtering Data*
3. **Unicycler** -> *Hybrid Assembly with Trimmed and Filtered Illumina and Nanopore Data*
4. **Quast** -> *Quality Control of Assembly*
5. **Bandage** -> *Contig Visualisation*
6. **Kraken2** -> *Species Identification*
7. **Staramr** and **ABRicate** -> *Resistance Genes Identification*
8. **Prokka** -> *Gene Annotation*
9. **Busco** -> *Assess Genome Assembly and Annotation Completeness*

## Workflow <img width="950" alt="Scherm­afbeelding 2024-03-03 om 22 24 11" src="https://github.com/MaxDubbeld/NGS-Workflow/assets/109160117/214e962d-43c7-4a7f-a9d0-6005b1ea18dc">
