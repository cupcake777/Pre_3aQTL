# pre_3aQTL
A collection of temporary scripts
This repository contains a curated snapshot of the core analysis modules associated with our current manuscript. Legacy scripts and temporary development files have been removed to ensure the release scope remains focused and clear.

## Release Scope

- [**01_pre/README.md**](01_pre/README.md)  
  Preprocessing and sample-level quality control for downstream QTL mapping.
- [**02_pattern/README.md**](02_pattern/README.md)  
  Temporal trajectory clustering, functional enrichment analysis, and visualization.
- [**03_QTL/README.md**](03_QTL/README.md)  
  Stage-specific 3'aQTL mapping, including downsampling, cross-stage comparisons, and interaction QTL (iQTL) analysis.
- [**04_motif/README.md**](04_motif/README.md)  
  PAS (Polyadenylation Site) motif annotation and mechanistic interpretation of APA events.
- [**05_coloc/README.md**](05_coloc/README.md)  
  Input preparation and implementation of the EasyColoc-based colocalization pipeline.
- [**06_smr/README.md**](06_smr/README.md)  
  SMR-based follow-up analyses and summary statistics derived from harmonized GWAS/QTL inputs.

## Data & File Management

To keep the repository lightweight and focused on the workflow, I have included only the core scripts and essential summary results. **Large data files are intentionally excluded from version control**, including:
* Raw sequence data and large intermediate matrices.
* PLINK binaries and genotype files.
* Runtime logs, caches, and heavy external-tool inputs.

If you need access to the full intermediate data or raw inputs, please refer to the project directory on our local server.

## Reproducibility Note

Several modules rely on site-specific reference resources (e.g., genome builds, annotation files) or external software. These dependencies are explicitly detailed in each module's README to clarify what is immediately runnable and what requires local environment setup.
