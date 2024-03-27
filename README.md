**RNA-Seq Pipeline
**
This pipeline script includes a series of commands for processing Next Generation Sequencing (NGS) data (here, RNA-Seq). The script automates the following steps:

    FastQC: Performs quality control checks on raw sequencing data.
    Fastp Trimming Adapters: Trims adapters and performs quality filtering on the input fastq file.
    Bowtie Indexing and Alignment: Builds an index of the reference genome and aligns the paired-end reads to the indexed genome.
    SAM to BAM: Converts the SAM file to a BAM file.
    Sorting BAM File: Sorts the BAM file by genomic coordinates.
    Indexing BAM File: Indexes the sorted BAM file.
    Converting GFF to BED: Converts a GFF file to a BED file.
    Mapping BAM to BED: Maps the BAM files to a BED file, producing coverage information.

To use the script, run it in a terminal, ensuring that the necessary software tools (FastQC, Fastp, Bowtie2, Samtools, Convert2bed, Bedtools) are installed and configured correctly.
