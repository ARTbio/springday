# Data

The original data is available at NCBI Gene Expression Omnibus (GEO)
under accession number [GSE18508](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE18508).
It is also mirrored at the EBI Small Read Archive under the accession number
[SRP001537](https://www.ebi.ac.uk/ena/data/view/SRP001537)

The data was generated through deep Sequencing of mRNA from the Drosophila melanogaster
S2-DRSC cells that have been RNAi depleted of mRNAs encoding RNA binding proteins.

In the tutorial, we are going to focus on 7 datasets generated to study the effect of the
*Pasilla* gene inactivation by RNAi knock-down.

- 4 untreated samples: GSM461176, GSM461177, GSM461178, GSM461182
- 3 treated samples (Pasilla gene depleted by RNAi): GSM461179, GSM461180, GSM461181 

Each sample constitutes a separate biological replicate of the corresponding condition
(treated or untreated).

Two of the treated and two of the untreated samples are from a paired-end sequencing assay,
while the remaining samples are from a single-end sequencing experiment. Thus the following
table will be (very) useful in our analysis since each of the 7 datasets are designated
with (i) its original ID in GEO (or EBI SRA) (ii)  its condition (untreated or treated)
and (iii) the sequencing technology used (single read or paired-end).

- GSM461176_untreat_single <-> SRR031709_untreat_single
- GSM461177_untreat_paired <-> SRR031714_untreat_paired
- GSM461178_untreat_paired <-> SRR031716_untreat_paired
- GSM461179_treat_single <-> SRR031718_treat_single
- GSM461180_treat_paired <-> SRR031724_treat_paired
- GSM461181_treat_paired <-> SRR031726_treat_paired
- GSM461182_untreat_single <-> SRR031728_untreat_single

## Data upload

We will take benefit of this mandatory stage, to review various possibilities to upload
dataset in Galaxy.

Then you will have the possibility to import the full set of the 7 FASTQ files in one of your
histories, from a data library that has been pre-set in your Galaxy server for this training
session.

### Uploading data from your local computer

1. Download the sample [GSM461176/SRR031709](ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR031/SRR031709/SRR031709.fastq.gz) to your
computer.
2. Upload this local file SRR031709.fastq.gz to your Galaxy history using the upload/Download
Galaxy interface that pops up if you click the upload icone (put image).

### Importing data via links
