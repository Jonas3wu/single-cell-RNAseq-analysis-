# Acknowledgments

This single-cell RNAseq analysis pipeline is based on community best practices and learning resources from:

Single-Cell Best Practices – https://www.sc-best-practices.org/preamble.html

scverse Learn – https://scverse.org/learn/


# Public Data Acknowledgment

The scRNA-seq datasets SRR23934263 and SRR23934264 correspond to baseline (diagnosis-stage) bone marrow samples from AML patients. These data were obtained from the GEO dataset GSE227903 and downloaded using the SRA Toolkit, after which reads were split into paired FASTQ files for downstream processing.

# Tailored workflow includes (not limited to)

This workflow follows sc-best-practices but is tailored for reproducible annotation. PCA (top 30 PCs), kNN graph construction, UMAP embedding, and Leiden clustering were performed in prior dimensionality reduction and clustering steps, saved, and reused unchanged during annotation. Cell type annotation integrated manual marker inspection, cluster-level differential expression, and optional automated labeling with CellTypist applied on a copy of the data.

# notebooks
<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/7deaf1bd-27d6-4d51-b483-9e0b56da5ea5" />

