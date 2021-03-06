# sandra_mcallister_lung_distal_tumor
Repository for analysis of McAllister RNAseq data comparing lungs of mice with and without distal tumors.

Code for analysis of [bcbio](https://bcbio-nextgen.readthedocs.io/en/latest/) processed RNA-seq data (see bcbio_info for parameters) using the [bcbioRNASeq 0.1.4](https://github.com/hbc/bcbioRNASeq) R package.

## File descriptions

### Main folder files:

QC.Rmd - Rmarkdown code for Quality control analysis report
QC.html - Quality control analysis report (includes all R packages versions used in analysis)


DE.Rmd - Rmarkdown code for differential expression analysis report
DE.html - Differential expression analysis report (includes all R packages versions used in analysis)


func.Rmd - Rmarkdown code for functional enrichment analysis report
func.html - Functional enrichment analysis report (includes all R packages versions used in analysis)


Cell_deconvolution.Rmd - Rmarkdown code for cell signature analysis report
Cell_deconvolution.html - Cell signature analysis report


*_header.Rmd, _output.yaml, setup.R, bibliography.bib -* code for report generation from Rmarkdown reports*

### bcbio_info subfolder:

bcbio-nextgen-commands.log - commands run during bcbio data processing

bcbio-nextgen.log - stdout from bcbio data processing 

data_versions.csv - versions of metadata (i.e. genome versions) used by bcbio in data processing

programs.txt - list of all programs and versions installed in build of bcbio



[![DOI](https://zenodo.org/badge/120795022.svg)](https://zenodo.org/badge/latestdoi/120795022)

