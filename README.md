# CRC_sc_analysis

## In silico prediction of biomarkers expression levels and pathways in colorectal Cancer based on public single cell RNASeq and functional data analysis

**Institution:** Faculty of Medicine of Tunis

---

## Overview

This repository contains the complete bioinformatics pipeline and analysis code for characterizing the cellular landscape of colorectal cancer (CRC) through single-cell RNA sequencing data analysis. This work aims to identify novel biomarkers and elucidate key signaling pathways involved in CRC progression.

## Objectives

This study aims to bridge critical knowledge gaps by leveraging in silico approaches to characterize the cellular signature of colorectal cancer through rigorous analysis of publicly available single-cell RNA sequencing datasets. Specifically, we seek to:

1. **Develop and validate a comprehensive bioinformatics pipeline** for single-cell RNA-seq analysis in colorectal cancer, incorporating state-of-the-art computational tools for data preprocessing, quality control, and advanced analytical frameworks.

2. Identify cell type-specific transcriptional signatures and potential biomarkers across the spectrum of colorectal cancer progression, with particular emphasis on **markers that could serve as diagnostic indicators or therapeutic targets**.

3. **Elucidate key signaling pathways and biological processes differentially regulated across distinct cellular compartments** within the tumor microenvironment, thereby providing insights into the functional consequences of transcriptional alterations.

4. Establish a predictive framework for biomarker expression patterns that could inform personalized therapeutic strategies, addressing the persistent challenges of treatment resistance and disease heterogeneity.

## Datasets

This analysis integrates two publicly available single-cell RNA-seq datasets from the Gene Expression Omnibus (GEO):

- **GSE188711** - 
- **GSE200997** - 

Both datasets contain:
- Tumoral and normal tissue samples
- Left-sided and right-sided CRC samples

## Analysis Pipeline

The bioinformatics workflow implemented in this repository includes:

1. **Quality Control (QC)** - Filtering low-quality cells and genes
2. **Data Integration** - Batch correction and harmonization across datasets
3. **Cell Type Annotation** - Both automated and manual annotation strategies
4. **Normalization & Clustering** - Data normalization and unsupervised clustering
5. **Differential Expression Analysis (DEG)** - Identification of differentially expressed genes
6. **Functional Analysis** - Pathway enrichment and biological process analysis

## Technologies & Tools

- **Programming Language:** Python
- **Primary Framework:** Scanpy (Single-Cell Analysis in Python)
- **Additional Libraries:** NumPy, Pandas, Matplotlib, Seaborn

`

## Citation

If you use this code or find it helpful for your research, please cite:

```
[Your Name]. (2025). In silico prediction of biomarkers expression levels 
and pathways in colorectal Cancer based on public single cell RNASeq and 
functional data analysis. Faculty of Medicine of Tunis.
```

## Contact

For questions or collaboration inquiries, please contact:
- GitHub: [@naili-mortadha](https://github.com/naili-mortadha)

## License

This project is available for academic and research purposes.

---

**Note:** Large data files (`.h5ad`, `.h5`, raw sequencing files) are not included in this repository due to size constraints. Please download the original datasets from GEO using the accession numbers provided above.
