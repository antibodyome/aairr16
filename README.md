# aairr16
Analysis of adaptive immune receptor repertoires (2016) course slides and notes.

## Cloning this repository

This repository contains large sequence and tabular files stored using Git-LFS, which can be installed from [here](https://git-lfs.github.com/).

Once the `lfs` subcommand is installed, the repository can be cloned as follows.

```
git lfs clone https://github.com/antibodyome/aairr16
```

## Required software

### General requirements

You will need to have the following installed on your computer:

- Python 3
- R
- wget

### EDirect

Entrez Direct, or EDirect, allows programmatic access to NCBI. It is available for download from [ftp://ftp.ncbi.nlm.nih.gov/entrez/entrezdirect/](ftp://ftp.ncbi.nlm.nih.gov/entrez/entrezdirect/).

### IgBLAST

IgBLAST compares reassorted BCR/TCR sequences against a germline database using a modified version of BLAST. It is available from [ftp://ftp.ncbi.nih.gov/blast/executables/igblast/release/](ftp://ftp.ncbi.nih.gov/blast/executables/igblast/release/).

### Python packages

This course makes heavy use of Jupyter notebooks. You will need to install Jupyter e.g.

```
pip3 install notebook
```

The slides make use of the RISE extension:

```
pip3 install RISE
jupyter-nbextension install rise --py --sys-prefix
jupyter-nbextension enable rise --py --sys-prefix
```

`--sys-prefix` can be replaced by `--user` or `--system` depending on the type of installation desired.

In addition, the following packages are required (and can be installed using `pip`)

- rpy2
- biopython
- presto
- changeo

### R packages

- ggplot2
- alakazam
- shazam
