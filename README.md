# ParSE-seq

Interpreting the clinical significance of putative splice-altering variants outside 2-base pair canonical splice sites remains difficult without functional studies. We developed Parallel Splice Effect Sequencing (ParSE-seq), a multiplexed minigene-based assay, to test variant effects on RNA splicing quantified by high-throughput sequencing. This method allows us to explore the landscape of splice-altering variants in the arrhythmia-linked gene SCN5A, the main sodium ion channel of the heart. We study hundreds of variants that allow us to calibrate our assay to ClinGen specifications, interpret VUS and CI variants, correlate with SpliceAI and other in silico predictors, and reveal occasional shortfalls of cDNA-based patch-clamp assays. 

Here we present 2 RMDs that comrpise our main analysis. The first, 'Early Processing' was used to process barcode frequencies, assign barcodes to unique constructs, calculate Percent Splice In associated with each barcode, and then merge on variant. In the second, 'Main Analyses', we explore this data and perform a variety of studies that constitute the main figures of the manuscript. We include additional dataframes and outputs that are generated in Unix and Python in additional folders. All DNA sequencing data will be made available at the NCBI Sequence Read Archive at publication. Please write to matthew.j.oneill@vumc.org or andrew.m.glazer@vumc.org with questions!  
