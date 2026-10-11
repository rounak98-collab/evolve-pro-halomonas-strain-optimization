# Evolve-Pro: Halomonas Research

A developing computational research project exploring *Halomonas* biology, ectoine-related pathways, and reproducible data analysis.

## Notebooks in this repository

- [`Evolve_Pro.ipynb`](Evolve_Pro.ipynb) — **legacy synthetic-data demonstration.** It generates simulated RNA/protein-like values in code; it does not ingest or reanalyse the cited experimental dataset.
- [`notebooks/HALOMONAS_ULTIMATE_PIPELINE_SIMULATION_DEMO.ipynb`](notebooks/HALOMONAS_ULTIMATE_PIPELINE_SIMULATION_DEMO.ipynb) — synthetic-data demonstration for testing notebook structure and visualizations.

**Important:** Outputs from these notebooks must not be treated as experimental findings. In particular, the 20-fold ectoine-production result reported in Qiao et al. (2024) is an ectoine-production outcome, not evidence that the notebook's simulated `ectA`, `ectB`, and `ectC` transcript values each increased 20-fold.

## Primary study and data sources under investigation

Qiao L, Shen G, Han R, et al. (2024). “Expression of ABC transporters negatively correlates with ectoine biosynthesis in *Halomonas campaniensis* under NaCl and ultraviolet mutagenesis treatments revealed by transcriptomic and proteomics combined analysis.” *BMC Genomics* 25, 1114.  
- Article: https://doi.org/10.1186/s12864-024-11003-9
- Proteomics accession reported in the paper: **PXD057477** (iProX: https://www.iprox.cn/)
- The study describes six groups (UV0, UV0-NaCl, UV1, UV1-NaCl, UV2, UV2-NaCl) with three biological replicates per group.
- The paper's main Data Availability statement identifies the proteomics accession but does not provide a raw RNA-seq accession. Raw transcriptome source discovery or author confirmation is therefore still required for an independent count-level reanalysis.

## Current status

**Real-data integration and validation are still in progress.** The immediate goals are to obtain traceable source tables/files, preserve source accessions and file hashes, validate sample labels and biological replicates, apply assay-appropriate QC/statistics, and document limitations. No experimental conclusions should be reported until those steps have been completed.

## Reproducibility and privacy

Record source URLs/accessions, file hashes, sample metadata, software versions, processing steps and analysis parameters. Do not commit credentials, patient-identifiable/private data, or datasets without permission to redistribute them.
