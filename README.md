# MPI-bioinformatics
An ever-expanding list of bioinformatics software that can be parallelized across multiple compute nodes in an HPC environment

For each tool, I will include the name, the URL where the source code can be downloaded, which "flavors" of MPI it works with (if known), and  how much testing I've done (compile, run, both, or none).  Where applicable, all code was compiled on an Linux node running CentOS 7 and using the following:

| Mvapich | OpenMPI | Mpich | Intel MPI |
| -------- | ------- | ----- | --------- |
| GCC 7.1 & Mvapich2.2 | GCC 7.1 & OpenMPI4.01 | GCC 7.1 & MPICH3.2.1 | Intel Parallel Studio 2020.0.1 |

MPI flavors are abbreviated as follows:

``` MV ``` = Mvapich

``` OP ``` = OpenMPI

``` MP ``` = Mpich

``` IN ``` = Intel

``` ALL ``` = code works with all MPI flavors

If you have any suggestions for software to add, please open an issue!

# Software Categories 

### Genome Assembly

### Functional Annotation

### Multiple Sequence Alignment

### Phylogenetics

| Software | URL | MPI version(s) | Testing | Notes |
| -------- | --- | -------------- | ------- | ----- |
| Mr. Bayes 2.7.1 | https://github.com/NBISweden/MrBayes | ALL | compile | | 

### Misc.
