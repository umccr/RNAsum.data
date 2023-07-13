
- [RNAsum.data: Data for RNAsum](#rnasumdata-data-for-rnasum)
  - [Installation](#installation)

<!-- README.md is generated from README.Rmd. Please edit that file -->

# RNAsum.data: Data for RNAsum

- Docs: <https://umccr.github.io/RNAsum/>

## Installation

<details>
<summary>
R
</summary>

``` r
remotes::install_github("umccr/RNAsum.data@vX.X.X") # for vX.X.X Release/Tag
remotes::install_github("umccr/RNAsum.data") # for bleeding edge main branch
```

</details>
<details>
<summary>
Conda
</summary>

- Linux & MacOS (non-M1)

``` bash
mamba create \
  -n rnasum_env \
  -c umccr -c bioconda -c conda-forge \
  r-rnasum==Y.Y.Y \
  r-rnasum.data==X.X.X

conda activate rnasum_env
```

- MacOS M1

``` bash
CONDA_SUBDIR=osx-64 \
  mamba create \
  -n rnasum_env \
  -c umccr -c bioconda -c conda-forge \
  r-rnasum==Y.Y.Y \
  r-rnasum.data==X.X.X

conda activate rnasum_env
```

</details>
