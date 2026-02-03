# T2D-Skin-BulkRNAseq
Bulk RNA-seq analysis of human skin tissue comparing Type 2 diabetic and non-diabetic samples using GEO data (GSE144441). Includes QC, DESeq2 differential expression, and functional enrichment highlighting adherens junction disruption in diabetic skin.

### Objective
To identify differentially expressed genes and enriched biological pathways associated with Type 2 diabetes in human skin tissue.

### Dataset
- Source: NCBI GEO
- Accession: GSE144441
- Organism: Homo sapiens
- Samples:
  - Type 2 Diabetes: n = 15
  - Non-diabetic Controls: n = 12
  
### Analysis Workflow
1. Data acquisition from GEO/SRA
2. Quality control and preprocessing (FastQC, MultiQC)
3. Alignment and quantification
4. Differential gene expression analysis (DESeq2)
5. Visualization (volcano plot, MA plot, heatmap)
6. Functional enrichment analysis

### Tools & Software
- NCBI GEO
- NCBI SRA
- SRA Toolkit
- FastQC & MultiQC
- STAR (v2.7.1a)
- Reference Genome & Annotation:
  - Human genome: GRCh38
  - GTF annotations from shared reference dataset
-  Subread: featureCounts
- R
- DESeq2

### Computing & Workflow Environment
- Conda
- SLURM
- Linux/Unix shell
- scp

### Contributors
- Manuela O Deigh
- Adetomiwa Adeusi
- Nia J. Walker

### License
This repository is intended for academic and educational use. Data are derived from publicly available sources.
