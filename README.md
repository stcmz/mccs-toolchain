# MCCS Toolchain

This repository contains all in-house command-line tools served in the MCCS protocol as submodules.

## Submodules

|GitHub Repo|Purpose|Build Status|Release Status|
|-|-|-|-|
|[gpcrn](https://github.com/stcmz/gpcrn)|multi-scheme offline GPCR numbering database query|![build workflow](https://github.com/stcmz/gpcrn/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/gpcrn/actions/workflows/release.yml/badge.svg)|
|[mccsx](https://github.com/stcmz/mccsx)|search and analysis of residue energy contribution vectors|![build workflow](https://github.com/stcmz/mccsx/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/mccsx/actions/workflows/release.yml/badge.svg)|
|[pdbget](https://github.com/stcmz/pdbget)|multi-threaded PDB structure download and protein chain split|![build workflow](https://github.com/stcmz/pdbget/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/pdbget/actions/workflows/release.yml/badge.svg)|
|[pdbm](https://github.com/stcmz/pdbm)|measurement of molecule models|![build workflow](https://github.com/stcmz/pdbm/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/pdbm/actions/workflows/release.yml/badge.svg)|
|[pdbqtf](https://github.com/stcmz/pdbqtf)|fixing problematic chemical elements in PDBQT files|![build workflow](https://github.com/stcmz/pdbqtf/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/pdbqtf/actions/workflows/release.yml/badge.svg)|
|[jdock](https://github.com/stcmz/jdock)|fast molecular docking, structure scoring and residue energy contribution vectors computation|![build workflow](https://github.com/stcmz/jdock/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/jdock/actions/workflows/release.yml/badge.svg)|
|[pdbrn](https://github.com/stcmz/pdbrn)|renumbering protein sequence in PDB/PDBQT molecular models|![build workflow](https://github.com/stcmz/pdbrn/actions/workflows/build.yml/badge.svg)|![release workflow](https://github.com/stcmz/pdbrn/actions/workflows/release.yml/badge.svg)|


## Related Repositories

### MCCS Examples

|GitHub Repo|Purpose|Paper|
|-|-|-|
|[mccs-bib-examples](https://github.com/stcmz/mccs-bib-examples)|verification of MCCS protocol using determined X-Ray crystallography or cryoEM structures of GPCRdb proteins|[DOI](https://doi.org/10.1093/bib/bbaa239)<br/>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33051641/)|
|[mccs-jcim-protease](https://github.com/stcmz/mccs-jcim-protease)|characterizing the binding features of inhibitors and modulators in SARS-CoV-2 main protease|Unpublished|
|[mccs-nprot-examples](https://github.com/stcmz/mccs-nprot-examples)|virtual screening against the determined SARS-CoV-2 3CL<sup>pro</sup> structure using approved drugs on DrugBank|[DOI](https://doi.org/10.1093/bib/bbaa260)<br/>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33078827/)|

### MCCS Packages

|GitHub Repo|Purpose|Registry|
|-|-|-|
|[mccs-docker](https://github.com/stcmz/mccs-docker)|scripts to create an MCCS docker image with all first-party and third-party software used in the MCCS protocol|[DockerHub](https://hub.docker.com/r/stcmz/mccs)


## Author

[Maozi Chen]


[Maozi Chen]: https://www.linkedin.com/in/maozichen/
[Briefing in Bioinformatics]: https://academic.oup.com/bib