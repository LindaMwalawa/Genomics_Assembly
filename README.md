# De Novo Assembly of ACE2 Gene in Bat species
The workflow involved processing paired end reads sequenced from an unknown bat species. 

## Objective:

To determine the most likely gene or protein encoded by the assembled sequences.

## De novo Assembly Workflow

1. Qaulity control of paired end reads using Fastqc
2. Trimming adapater sequences and removing low quality bases (Phred >33)using Trimmomatic
3. Assembly of the Qcied reads using velveth and velvetg
4. Validation and orientation of consensus contigs in NCBI BLASTN (Top hit matched the Myotis brandtii bat species) 
