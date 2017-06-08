# scicore-pipeline-2

This container includes the following apps:

* Bowtie2/2.2.9 - http://bowtie-bio.sourceforge.net/bowtie2/index.shtml
* SAMtools/1.3.1 - http://www.htslib.org/
* freebayes/1.1.0 - https://github.com/ekg/freebayes
* vcftools/0.1.14 - https://vcftools.github.io
* Optional tools only used to download the public data and downsample it
* SRA-Toolkit/2.8.1-3-centos_linux64 - https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=std
* Seqtk/1.2 - https://github.com/lh3/seqtk


## Downloading the container with Singularity

   `$> singularity pull -n "pipeline2.img" docker://pescobar/scicore-pipeline2:latest`

## Using the container with singularity

   `$> singularity exec pipeline2.img samtools -h`

## Interactive shell inside the container with singularity

   `$> singularity shell pipeline2.img`



