# AID-mediated mutations shape the pre-immune BCR repertoire in adult mice


## Descriptions
This repository contains the data for manuscript titled as AID-mediated mutations shape the pre-immune BCR reperotire in adult mice. The data table is in tab-delimited format and is named as AID-MS-data.txt


### Column header descriptions

```
Header: Sequence unique identifer consisting of the UMI barcode and the UMI count, as well as isotype where available

CloneID: The unique ID for row entry that shares the same V-J-gene-segment usage and the same CDRH3AA

LineageID: The unique ID for row entry that shares the same V-J-gene-segment usage and the same CDRH3AA length at 85% or higher sequence identity

Clone: V-gene:J-gene:CDRH3AA

V-J-CDR3Length: V-gene:J-gene:CDRH3AA-length

CDR3NT: CDR3 in nucleotides

Sample: Sample identification

Compartment: Tissue compartment origin of B-cells

Identity: Sequence Identity in % against annotated germline

V-gene: V-gene segment annotation

J-gene: J-gene segment annotation

MatchNT: # of matching nucleotides to germline

MismatchNT: # of mismatching nucleotides to germline

FR1mismatchNT: # of mismatching nucleotides to Framework 1 germline

CDR1mismatchNT: # of mismatching nucleotides to CDR 1 germline

FR2mismatchNT: # of mismatching nucleotides to Framework 2 germline

CDR2mismatchNT: # of mismatching nucleotides to CDR 2 germline

FR3mismatchNT: # of mismatching nucleotides to Framework 3 germline

CDR3mismatchNT: # of mismatching nucleotides to CDR 3 germline

CDR1-CDR2-CDR3-AA: CDR1-CDR2-CDR3 sequences in amino acids

CDR3length: CDR3 length in amino acids

FR1AA: Framework 1 in amino acids

CDR1AA: CDR 1 in amino acids

FR2AA: Framework 2 in amino acids

CDR2AA: CDR 2 in amino acids

FR3AA: Framework 3 in amino acids

CDR3AA: CDR 3 in amino acids

FR4AA: Framework 4 in amino acids

CDR1-CDR2-CDR3-NT: CDR1-CDR2-CDR3 sequences in nucleotides

FR1NT: Framework 1 in nucleotides

CDR1NT: CDR 1 in nucleotides

FR2NT: Framework 2 in nucleotides

CDR2NT: CDR 2 in nucleotides

FR3NT: Framework 3 in nucleotides

FR4NT: Framework 4 in nucleotides

NT: Full-length nucleotide sequence

RawSeqCount: # of sequences sharing the same Full-length amino acids sequence

UniEntPerClone: # of enrty row sharing the same CloneID

UniEntPerLineage: # of entry row sharing the same LineageID

ClonePerLineage: # of unique clones sharing the same LineageID

Campaign: Experimental campaign

FullAA: Full-length amino acids sequence

RSCgrp: RawSeqCount binning groups with increments of 250 reads per binning group

Isotype: BCR isotype

Redundancy: UMI barcode read counts representing the number of redundant reads resulted from PCR amplification

Treatment: Tamoxifen treatment or antibiotics treatment

GC: whether the B-cells were sorted on Germinal center B cells markers

FRAIDHS: Framework AID hotspot mutations

CDRAIDHS: CDR AID hotspot mutations

TOTAIDHS: Sum of FRAIDHS and CDRAIDHS

TOTMISMATCH: Total number of nucleotide mismatches from germline

```

## Authors

* Katherine Bao, Juan Zhang, Alexis Scherl, James Ziai, Azi Hadadianpour, Daqi Xu, Christopher Dela Cruz, John Liu, Yuxin Liang, Lucinda Tam, C. Alex Corzo, Merone Roose-Girma, Soren Warming, Zora Modrusan, Wyne P. Lee, Kam Hon Hoi and Ali A. Zarrin

## Citations

* Bao, K. et al. Activation-Induced Cytidine Deaminase Impacts the Primary Antibody Repertoire in Naive Mice. The Journal of Immunology 208, 2632–2642 (2022).


