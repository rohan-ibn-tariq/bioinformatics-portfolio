# bioinformatics-portfolio
This is Muhammad Rohan Ali Asmat's work portfolio in the domain of bioinformatics.

The table of contents are as follows: 
1. [Papers](#papers)
2. [Presentations](#presentations)
3. [Workflows](#workflows)
4. [Benchmarks and Tests](#benchmarks-and-tests)
5. [Feature Requests](#feature-requests-or-implementations)
6. [Bugs Reported](#bugs-reported)
7. [Documentation](#documentation)
8. [Chore](#chore)
9. [UX Issues](#ux-issues)
10. 



## Papers 

## Presentations

## Workflows

| Project                | Subcategory        | Description                                                                                                                                                                                                                                                                                                            | Status          | Work Affiliation                                                | Languages / Technologies / Concepts                                                                                                                                                                        |  
| ---------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  
| MSI-Snakemake-Workflow | Snakemake Workflow | Comprehensive Snakemake workflow for **Microsatellite Instability (MSI) detection** in human chromosome. Includes reference genome download, tandem repeat discovery, variant simulation, MSI-targeted indel injection, read simulation, alignment, probabilistic variant calling, and MSI quantification/analysis. [Repository](https://github.com/rohan-ibn-tariq/MSI-Snakemake-Workflow) - [Prototype of PR #527](https://github.com/varlociraptor/varlociraptor/pull/527) | **Implemented** | Intern @ Köster lab, supervised by Johannes Köster | Snakemake, Python, shell scripting, Ensembl API, BWA, PyTRF, Mason (Simulator & Variator), samtools, Varlociraptor, bcftools, bedtools, awk, Altair, Polars, interval binning, genomic data analysis |
| MSI-Snakemake-Workflow | Snakemake Workflow | Comprehensive Snakemake workflow for **Microsatellite Instability (MSI) detection** in generic tumor only samples. Includes reference genome download, tandem repeat discovery, alignment, probabilistic variant calling, and MSI quantification/analysis. [Repository](https://github.com/rohan-ibn-tariq/Estimate-MSI-Workflow) - [Test Workflow for PR #527](https://github.com/varlociraptor/varlociraptor/pull/527) | **In Progress** | Intern @ Köster lab, supervised by Johannes Köster | Snakemake, Snakemake-wrappers, Python, shell scripting, Ensembl API, BWA, PyTRF, Msisensor2, Msisensor-pro, samtools, freebayes, Varlociraptor, bcftools, bedtools, awk, aria2, picard, genomic data analysis |

## Benchmarks and Tests

| Project            | Subcategory     | Description                                                                                  | Status         | Work Affiliation                    | Languages / Technologies / Concepts         |
|--------------------|-----------------|--------------------------------------------------------------------------------------------------------------|----------------|-------------------------------------------|---------------------------------------------|
| pytrf-test         | TRF vs pytrf | Created and reported comparison tests for pytrf vs TRF, for the purpose of microsatellite instability quantification or simulating indel injections. [Repository](https://github.com/rohan-ibn-tariq/pytrf-test/tree/master) | **Implemented & reported** | Intern @ Köster lab, supervised by Johannes Köster | Python, shell script, pytrf, TRF, micromamba |


## Feature Requests or Implementations

| Project       | Subcategory        | Description                                                                                                                                                                                                                                  | Status                  | Work Affiliation                           | Languages/Technologies/Concepts             |
| ------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------ | ------------------------------------------ |
| Varlociraptor | Estimation         | Implements microsatellite instability (MSI) detection with subclonal resolution and uncertainty quantification, going beyond traditional binary MSI-H/MSS classification. [PR #527](https://github.com/varlociraptor/varlociraptor/pull/527) | **Implemented**, Sample Visualizations: [Distribution Plot](Assets/Outputs/Varlociraptor/Estimation/MSI/distribution-plot.svg) - [Pseudotime Plot](Assets/Outputs/Varlociraptor/Estimation/MSI/pseudotime-plot.svg)       | Intern @ Köster lab, supervised by Johannes Köster | Rust, dynamic programming |
| Rust-Bio      | —                  | Implementing UCSC Binning Scheme [Issue #647](https://github.com/rust-bio/rust-bio/issues/647)                                                                                                                                               | Reported  | Intern @ Köster lab, supervised by Johannes Köster |                             |
| Rust-Bio      | —                  | Utility functions for converting between linear error probabilities and PHRED. [Issue #649](https://github.com/rust-bio/rust-bio/issues/649)                                                                                                 | Reported | Intern @ Köster lab, supervised by Johannes Köster |           |
| Snakemake     | Snakemake-Wrappers | Added wrapper for Tandem Repeat Finder (TRF). [PR #4160](https://github.com/snakemake/snakemake-wrappers/pull/4160)                                                                                                                          | **Implemented**       | Intern @ Köster lab, supervised by Johannes Köster | Snakemake, Snakemake-Wrappers, Python, TRF          |
| Snakemake     | Snakemake-Wrappers | Added 4 wrappers for pytrf utility (extract, findatr, findgtr, findstr). [PR #4745](https://github.com/snakemake/snakemake-wrappers/pull/4745)                                                                                               | **Implemented**       | Intern @ Köster lab, supervised by Johannes Köster | Snakemake, Snakemake-Wrappers, Python, pytrf         |
| Snakemake     | Snakemake-Wrappers | Feature Request: Adding Wrapper(s) for Gnomad Resources. [Issue #4921](https://github.com/snakemake/snakemake-wrappers/issues/4921)                                                                                               | Reported       | Intern @ Köster lab, supervised by Johannes Köster |         |
| Snakemake     | Wrapper Utils      | Make `get_format` function support more FASTA extensions. [Issue #48](https://github.com/snakemake/snakemake-wrapper-utils/issues/48)                                                                                                        | Reported | Intern @ Köster lab, supervised by Johannes Köster | -                    |

## Bugs Reported

| Project       | Subcategory | Description / Issue                                                                                                               | Status   | Work Affiliation                           | Languages/Technologies/Concepts |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------------------------------ | ------------------------ |
| Varlociraptor | CLI  | Fixed color-handling issue. [Issue #519](https://github.com/varlociraptor/varlociraptor/issues/519) - [PR #520](https://github.com/varlociraptor/varlociraptor/pull/520)                                    | Reported & Fixed  | Intern @ Köster lab, supervised by Johannes Köster | Rust                     |
| pytrf         |  -  | Extract command crashes with TypeError (“delimiter” must be string). [Issue #6](https://github.com/lmdu/pytrf/issues/6) | Reported | Intern @ Köster lab, supervised by Johannes Köster | -                    |
| pytrf         |  -  | Pytrf findstr 'bed' output format not working. [Issue #7](https://github.com/lmdu/pytrf/issues/7) | Reported | Intern @ Köster lab, supervised by Johannes Köster | -                    |
| SeqAn   | Mason Variator | mason_variator: invalid FORMAT column in VCF output, [issue #1671](https://github.com/seqan/seqan/issues/1671). | **Verified & Notified** | Intern @ Köster lab, supervised by Johannes Köster | Mason Variator, Snakemake |
| Snakemake | Core  | Reporeted AmbiguousRuleException Issue [Issue #1219](https://github.com/snakemake/snakemake/issues/1219#issuecomment-3710745526)            | Reported  | Intern @ Köster lab, supervised by Johannes Köster | Snakemake, S3
| Snakemake | Core  | Reporeted **performance/UX** issue that the dry run should handle the environments also based on actual execution flow like it handles the rules [Issue #3954](https://github.com/snakemake/snakemake/issues/3954)            | Reported  | Intern @ Köster lab, supervised by Johannes Köster | Snakemake


## Documentation

| Project       | Subcategory | Description / Issue                                                                                                               | Status   | Work Affiliation                           | Languages/Technologies/Concepts |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------------------------------ | ------------------------ |
| Snakemake | Snakemake-Fmt-Provider | Two Readme Improvements: Elaborated help for snakefmt.trace.server & snakefmt.disableLinting. [Issue #127](https://github.com/tfehlmann/vscode-snakefmt-provider/issues/127) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |
| Snakemake | Snakemake-Plugin-Catalog | Expanded installation instructions to include guidance for users installing the plugin with the "pixi" package manager. [PR #14](https://github.com/snakemake/snakemake-plugin-catalog/pull/14) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, Jinja2, RST |
| Snakemake | Snakemake | Updated Requirement Section of The Tutorial With Warning of Not Installing The Tools Manually. [PR #3607](https://github.com/snakemake/snakemake/pull/3607) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| Snakemake | Snakemake | Artifacts That can be added Docsets, Biolerplate(s), Cheatsheet(s). [Issue #3584](https://github.com/snakemake/snakemake/issues/3584) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |
| Snakemake | Snakemake | Updated Wrapper Version in Tutorial and Used Simple Rule For Consistency & Ease. [PR #3605](https://github.com/snakemake/snakemake/pull/3605) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| Snakemake | Snakemake | Added snakemake command to execute the rule plot_with_python. [PR #3608](https://github.com/snakemake/snakemake/pull/3608) - Fixes [#3587](https://github.com/snakemake/snakemake/issues/3587) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| Snakemake | Snakemake | Updated Reporting Section of The Tutorial. [PR #3606](https://github.com/snakemake/snakemake/pull/3606) - Fixes [#3588](https://github.com/snakemake/snakemake/issues/3588) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| Snakemake | Snakemake-Wrappers | ALIGNOTH documents section formatting is not right. [Issue #4743](https://github.com/snakemake/snakemake-wrappers/issues/4743) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |
| Snakemake | Snakemake-Wrappers | Docs: Update Contribution Guidelines to Hint About Conventions [Issue #4915](https://github.com/snakemake/snakemake-wrappers/issues/4915) | Reported after suggestion of reviewer | Intern @ Köster lab, supervised by Johannes Köster |  |
| teaching-data-analysis-visualization-reproducibility | - | Corrected sentence meaning by specifying that select() returns a new DataFrame. [PR #2](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/2) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| teaching-data-analysis-visualization-reproducibility | - | Polars:Step 6 - made clear in the sentence that select() returns a new DataFrame. [PR #3](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/3) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| teaching-data-analysis-visualization-reproducibility | - | Altair-Step 9: fixed typing mistake from vertial to vertical. [PR #4](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/4) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| teaching-data-analysis-visualization-reproducibility | - | Altair-Step12: corrected the parameter from global to local(df). [PR #5](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/5) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| teaching-data-analysis-visualization-reproducibility | - | Corrected sentence in Instantiating classes section. [PR #1](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/1) | **Reported & Fixed** | Intern @ Köster lab, supervised by Johannes Köster | Sphinx, RST |
| pytrf | - | Reported missing dependency at bioconda: pyfastx for pytrf. [Issue #5](https://github.com/lmdu/pytrf/issues/5) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |
| bioconda | Bioconda-Docs | Documentation displays dependencies for only one Python variant despite multiple builds existing. [Issue #46](https://github.com/bioconda/bioconda-docs/issues/46) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |
| Alignoth | - | Docs: Coordinate system (1-based vs 0-based) Clarification for --region. [Issue #425](https://github.com/alignoth/alignoth/issues/425) | Reported | Intern @ Köster lab, supervised by Johannes Köster |  |


## Chore

| Project       | Subcategory | Description / Issue                                                                                                               | Status   | Work Affiliation                           | Languages/Technologies/Concepts |
| ------------- | ----------- | --------------------------------------------------------------------------------------------------------------------------------- | -------- | ------------------------------------------ | ------------------------ |
| TRF | — | Version mismatch in build with github tag. [Issue #32](https://github.com/Benson-Genomics-Lab/TRF/issues/32) | Reported | Intern @ Köster lab, supervised by Johannes Köster | - |
| Bioconda | Bioconda-Recipes | Update: trf 4.09.1 to trf 4.10.0rc2. [PR #56931](https://github.com/bioconda/bioconda-recipes/pull/56931) | **Updated** | Intern @ Köster lab, supervised by Johannes Köster | shell script, yaml |
| Snakemake | Snakemake-Wrappers | Updated trf to 4.10.0rc2. [PR #4297](https://github.com/snakemake/snakemake-wrappers/pull/4297) | **Updated** | Intern @ Köster lab, supervised by Johannes Köster | python |


## UX Issues

| Project       | Subcategory | Description / Issue                                                                                                                                                                                                                         | Status       | Work Affiliation                           | Languages / Technologies |
| ------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------ | ------------------------ |
| Varlociraptor | UX Issue    | Reported UX issue regarding interface/interaction. [Issue #521](https://github.com/varlociraptor/varlociraptor/issues/521)                                                                                                                  | Reported     | Intern @ Köster lab, supervised by Johannes Köster |                      |
| Varlociraptor | UX Issue    | Reported inconsistency in conformity of probabilities description field in VCF's meta-information to latest standard [Issue #531](https://github.com/varlociraptor/varlociraptor/issues/531)                                                                                                                  | Reported     | Intern @ Köster lab, supervised by Johannes Köster | VCF               |
| Snakemake     | UX Issue    | UI/UX issues in the global report generation (presentation, state management, and visual cues). [Issue #3589](https://github.com/snakemake/snakemake/issues/3589) — *Closed by Johannes; I later demonstrated the importance of the issue.* | Reported & Demonstrated | Intern @ Köster lab, supervised by Johannes Köster |        |
