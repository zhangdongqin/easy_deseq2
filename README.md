# zdq_deg
 A Deseq2 R script for DEG analysis
Dependencies:
	library(optparse)
	library(DESeq2)
	library(BiocParallel)
	library(ggplot2)
	library(RColorBrewer)
	library(pheatmap)
	library(dplyr)
	library(org.Hs.eg.db)
	library(AnnotationHub)
	library(ggrepel)
	library(amap)
	library(clusterProfiler)

Usage:
Rscript deseq.r \
--count_file ./reads.txt \
--coldata_file ./coldata.txt \
--sample_con "tumor-normal" \
--outprefix "zdq_deseq2"


Results:
