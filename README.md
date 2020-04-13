# Supplemental Data for 'Pioneer factor GAF cooperates with PBAP and NURF to regulate transcription'

Julius Judd<sup>1</sup>, Fabiana M. Duarte<sup>2</sup>, and John T. Lis<sup>1</sup>

<sup>1</sup>Department of Molecular Biology and Genetics, Cornell University, Ithaca, New York 14835, USA
<sup>2</sup>Broad Institute of MIT and Harvard, Cambridge, MA 02142, USA


This is a GitHub repository that contains supplemental data for the paper "Pioneer factor GAF cooperates with PBAP and NURF to regulate transcription".  

## Analysis code
All code used for analysis can be found in the file "GAF_SupplementalInformation_JAJ.Rmd", or in the accompanying pdf file.  

## Data
### DESeq_results 
Contains all DESeq2 differential expression testing output for all comparisions performed in the paper.  

### Bed
Contains bed format files, including macs2 peak calls for ATAC-seq and GAF ChIP-seq data, lists of GAF-bound genes with or without GAF-dependent pause signal, and lists of genes that are dependent on GAF and PBAP for pausing, only GAF, or only PBAP.  Also included is a filtered list of PRO-cap corrected, unique dm6 transcripts that passed our upstream transcription filter.

### bw
Contains bigWig format files of data. ATAC-seq, PROseq, RNAseq, and CUTANDRUN data was generated for this paper. For each data type, there are bigWig files for raw, un-normalized signal (of individual replicates), and merged normalized tracks. RNA-seq and PRO-seq are normalized by spike-in control, and ATAC-seq was normalized using DESeq2 sizeFactors. ChIP-seq contains published data that was reanalyzed for this paper, either by realignment of raw data or by liftOver of signal tracks. M1BP PRO-seq contains published M1BP knockdown PRO-seq signal tracks that were lifted over to the dm6 genome assembly.

### Genome
Contains a bed file of PRO-cap corrected dm6 genes.





