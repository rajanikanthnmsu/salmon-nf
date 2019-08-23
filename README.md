# salmon-nf
Detection of presence of viral genome integrations using RNA-seq data.

## Installation

### Nextflow
Install `nextflow` following the [instructions](https://www.nextflow.io/docs/latest/getstarted.html).

Be sure to run at least Nextflow version 0.30.2.

### Singularity
Install `singularity` following the instructions at
https://singularity.lbl.gov/install-linux

### salmon-nf pipeline

The most convenient way is to install `salmon-nf` is to use `nextflow`'s built-in `pull` command
```bash
nextflow pull t-neumann/salmon-nf
```

## Documentation

* Salmon: Collect and quantify splice-variants in the dataset.

```bash
nextflow run t-neumann/salmon-nf --help
```

## Credits
[Nextflow](https://github.com/nextflow-io/nextflow):  Paolo Di Tommaso

[Singularity](https://singularity.lbl.gov): Singularityware

[Centrifuge](https://ccb.jhu.edu/software/centrifuge/): Daehwan Kim, Salzberg Lab

[bwa](http://bio-bwa.sourceforge.net/): Hl3

[Sailfish](https://github.com/kingsfordgroup/sailfish) - Kingsford Group
