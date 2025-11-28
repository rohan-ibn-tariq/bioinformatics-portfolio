# bioinformatics-portfolio
This is Muhammad Rohan Ali Asmat's work portfolio in the domain of bioinformatics.

The table of contents are as follows: 
1. [Papers](#papers)
2. [Workflows](#workflows)
3. [Feature Requests](#feature-requests-or-implementations)
4. [Bugs Reported](#bugs-reported)
5. [Documentation](#documentation)
6. [Chore](#chore)
7. [UX Issues](#ux-issues)
8. 



## Papers 

## Workflows

## Feature Requests or Implementations

| Project       | Subcategory        | Description                                                                                                                                                                                                                                  | Status                  | Work Affiliation                           | Languages / Technologies                   |
| ------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------ | ------------------------------------------ |
| Varlociraptor | Estimation         | Implements microsatellite instability (MSI) detection with subclonal resolution and uncertainty quantification, going beyond traditional binary MSI-H/MSS classification. [PR #527](https://github.com/varlociraptor/varlociraptor/pull/527) | **I Implemented**       | Koster lab, supervised by Johannes Kooster | Rust, dynamic programming |
| Rust-Bio      | —                  | Implementing UCSC Binning Scheme [Issue #647](https://github.com/rust-bio/rust-bio/issues/647)                                                                                                                                               |   | Koster lab, supervised by Johannes Kooster |                             |
| Rust-Bio      | —                  | Utility functions for converting between linear error probabilities and PHRED. [Issue #649](https://github.com/rust-bio/rust-bio/issues/649)                                                                                                 |   | Koster lab, supervised by Johannes Kooster |           |
| Snakemake     | Snakemake-Wrappers | Added wrapper for Tandem Repeat Finder (TRF). [PR #4160](https://github.com/snakemake/snakemake-wrappers/pull/4160)                                                                                                                          | **I Implemented**       | Koster lab, supervised by Johannes Kooster | Snakemake, Python, TRF          |
| Snakemake     | Snakemake-Wrappers | Added 4 wrappers for pytrf utility (extract, findatr, findgtr, findstr). [PR #4745](https://github.com/snakemake/snakemake-wrappers/pull/4745)                                                                                               | **I Implemented**       | Koster lab, supervised by Johannes Kooster | Snakemake, Python, pytrf         |
| Snakemake     | Wrapper Utils      | Make `get_format` function support more FASTA extensions. [Issue #48](https://github.com/snakemake/snakemake-wrapper-utils/issues/48)                                                                                                        | **Someone Implemented** | Koster lab, supervised by Johannes Kooster | -                    |

## Bugs Reported
1. Varlociraptor
   1. [Fixing Color Issue](https://github.com/varlociraptor/varlociraptor/pull/520) -- **iFixed🔐**
2. pytrf
    1. [Reported Issue: Extract command crashes with TypeError: "delimiter" must be string, not type (PyTRF 1.4.2)](https://github.com/lmdu/pytrf/issues/6)


## Documentation
1. Snakemake
   1. Snakemake-Fmt-Provider
      1. [Two Readme Improvements: Elaborated help for snakefmt.trace.server & snakefmt.disableLinting](https://github.com/tfehlmann/vscode-snakefmt-provider/issues/127)
   2. Snakemake-Plugin-Catalog
      1. [Expanded installation instructions to include guidance for users installing the plugin with the "pixi" package manager](https://github.com/snakemake/snakemake-plugin-catalog/pull/14) -- **iFixed🔐**
   3. Snakemake
      1. [Updated Requirement Section of The Tutorial With Warning of Not Installing The Tools Manually. Improves Readability and Usability](https://github.com/snakemake/snakemake/pull/3607) -- **iFixed🔐**
      2. [Artifacts That can be added Docsets, Biolerplate(s), Cheatsheet(s)](https://github.com/snakemake/snakemake/issues/3584)
      3. [Updated Wrapper Version in Tutorial and Used Simple Rule For Consistency & Ease](https://github.com/snakemake/snakemake/pull/3605) -- **iFixed🔐**
      4. [Added snakemake command to execute the rule plot_with_python](https://github.com/snakemake/snakemake/pull/3608) -- **iFixed🔐** -- Fixes [#3587](https://github.com/snakemake/snakemake/issues/3587)
      5. [Updated Reporting Section of The Tutorial(Interaction, Visualization, and Reporting with Snakemake)](https://github.com/snakemake/snakemake/pull/3606) **iFixed🔐** -- Fixes [#3588](https://github.com/snakemake/snakemake/issues/3588)
   4. Snakemake-Wrappers  
      1. Alignoth  
         1. [ALIGNOTH documents section formatting is not right](https://github.com/snakemake/snakemake-wrappers/issues/4743)  
2. teaching-data-analysis-visualization-reproducibility  
   1. [Corrected sentence meaning by specifying that select() returns a new DataFrame](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/2) -- **iFixed**  
   2. [Polars:Step 6 - made clear in the sentence that select() returns a new DataFrame instead of modifying old](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/3) -- **iFixed**
   3. [Altair-Step 9: fixed typing mistake from vertial to vertical](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/4) -- **iFixed**
   4. [Altair-Step12: corrected the parameter from global to local(df)](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/5) -- **iFixed**
   5. [Corrected sentence in Instantiating classes section](https://github.com/koesterlab/teaching-data-analysis-visualization-reproducibility/pull/1) -- **iFixed**
3. pytrf
   1. [Reported missing dependency at bioconda: pyfastx for pytrf](https://github.com/lmdu/pytrf/issues/5)
4. bioconda  
   1. [Documentation displays dependencies for only one Python variant despite multiple builds existing](https://github.com/bioconda/bioconda-docs/issues/46)  

## Chore
1. TRF
   1. [Version mismatch in build with github tag](https://github.com/Benson-Genomics-Lab/TRF/issues/32)
2. Biconda
   1. [Update: trf 4.09.1 to trf 4.10.0rc2](https://github.com/bioconda/bioconda-recipes/pull/56931) -- **iupdated🔐**
3. Snakemake
   1. Snakemake-Wrappers
      1. [Updated trf to 4.10.0rc2](https://github.com/snakemake/snakemake-wrappers/pull/4297) -- **iupdated🔐**

## UX Issues
1. Varlociraptor
   1. [UX Issue](https://github.com/varlociraptor/varlociraptor/issues/521)
2. Snakemake
   1. Snakemake  
      1. [In Generating Global Report, there are UI/UX issues related to presentation of report](https://github.com/snakemake/snakemake/issues/3589) -- **Johannes closed it, but I gave demonstration to him(I think later) explaining how the issue was critical from UX perspective in terms of maintaining state(s) and visual cue(s).**
