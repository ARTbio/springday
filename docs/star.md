![](images/galaxylogo.png)

# RNA STAR (option for 50 % of attendees)

For information to set proper value for STAR parameters:

![](images/multiqc_samples_length.png)

----
![](images/tool_small.png)

  1. create a new history and name it `RNA STAR`
  2. Import the 11 datasets from the RNAseq data library to this `RNA STAR` history, plus the Drosophila_melanogaster.BDGP6.95.gtf file
  3. Select the `RNA STAR` tool with the following parameters to map your reads on the reference genome:
      1. `Single-end or paired-end reads`: Single-end
      2. `RNA-Seq FASTQ/FASTA file` (as multiple datasets), Cmd-shift Select:
          - `GSM461176_untreat_single.fastq.gz`
          - `GSM461179_treat_single.fastq.gz`
      3. `Custom or built-in reference genome:` Use a built-in index
      4. `Reference genome with or without an annotation:` use genome reference without builtin gene-model
      5. `Select reference genome:` Drosophila Melanogaster (dm6)
      6. `Gene model (gff3,gtf) file for splice junctions:` the imported Drosophila_melanogaster.BDGP6.95.gtf
      7. `Length of the genomic sequence around annotated junctions:` 44 (This parameter should be length of reads - 1, see above table from fastQC/multiQC analysis)
  4. `Execute`
----
![](images/redo.png)

  Redo the STAR run with

  **3.2**	 Select the `RNA STAR` tool with the following parameters to map your reads on the reference genome:
   `RNA-Seq FASTQ/FASTA file` (as multiple datasets), Cmd-shift Select:
          - `GSM461182_untreat_single.fastq.gz`
          
  **3.7**	 `Length of the genomic sequence around annotated junctions:` 74 (This parameter should be length of reads - 1, see above table from fastQC/multiQC analysis)
