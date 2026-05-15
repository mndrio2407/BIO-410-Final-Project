# BIO 410 Final Project
## Background
The data is made up of 6 samples of the organism Ebola virus. It is a negative-sense single-stranded RNA virus that is responsible for causing the Ebola virus disease which results in hemorrhagic fever in humans and other primates. Ebola virus is under the Filoviridae family and is known to cause major outbreaks in Africa. The identification of the organism is based on BLAST sequence analysis in NCBI nucleotide.

## Purpose

The purpose of this project is to develop a phylogenetic tree for the 6 samples of Ebola virus in order to be able to understand the evolutionary relationship among the samples and find out which ones are similar.

## Methods
Raw next-generation sequencing (NGS) reads were assembled using MEGAHIT. The assembly was aligned using the AlignSeqs function in the R package DECIPHER. Alignment was visualized using BrowseSeqs and converted to HTML. The phylogenetic tree was constructed using maximum likelihood (ML) in the R DECIPHER.

The raw sequencing reads can be found in the original sequencing data directory, while the assembled sequences are in the MEGAHIT output directory. Alignment is saved as alignment.html and tree image is saved as tree.png.
## Results

The phylogenetic tree indicated that samples 2 and 3 were similar to each other and belonged to one cluster with sample 1. The similarity of samples 5 and 6 to each other was also evident, with sample 4 included into another cluster. This indicates that evolutional differences occurred between the samples of the Ebola virus.

On the basis of the obtained phylogenetic tree, it can be stated that six samples belong to two different lineages of viruses, as there are two separate clusters of the tree.
