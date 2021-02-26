# zdq_deg
 A Deseq2 R script for DEG analysis
## Quick Start
1. -STEP01:
	-INSTALL Dependencies: (OR RUN THIS SCRIPTS WITH A DOCKER IMAGES)
	```bash
	if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
    BiocManager::install("DESeq2")
    BiocManager::install("BiocParallel")
    BiocManager::install("optparse")
    BiocManager::install("ggplot2")
    BiocManager::install("RColorBrewer")
    BiocManager::install("pheatmap")
    BiocManager::install("dplyr")
    BiocManager::install("ggrepel")
    BiocManager::install("clusterProfiler")
    BiocManager::install("amap")
    BiocManager::install("AnnotationHub")
    BiocManager::install("org.Hs.eg.db")
	```

2. -STEP02_Usage:( YOU CAN RUN FOLLOW SCRIPTS TO RUN A TEST pipeline )
	```bash
	Rscript deseq.r \
	--count_file ./reads.txt \
	--coldata_file ./coldata.txt \
	--sample_con "tumor-normal" \
	--outprefix "zdq_deseq2"
	```

