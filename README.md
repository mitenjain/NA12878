# NA12878 Human Reference on Oxford Nanopore MinION

## Contributors

Mark Akeson (1), Andrew D. Beggs (2), Thomas Nieto (2), Miten Jain (1), Nicholas J. Loman (3), Matt Loose (4), Sunir Malla (4), Justin O’Grady (5), Hugh E. Olsen (1), Josh Quick (3), Hollian Richardson (5), Jared T. Simpson (6,7), Terrance P. Snutch (8), Louise Tee (2), John R. Tyson (8)

   1. University of California, Santa Cruz, Santa Cruz, CA, USA
   2. University of Birmingham, Birmingham, B15 2TT
   3. Institute of Microbiology and Infection, School of Biosciences, University of Birmingham, Birmingham, B15 2TT, United Kingdom
   4. DeepSeq, School of Life Sciences, University of Nottingham, Nottingham, UK
   5. Norwich Medical School, University of East Anglia, Norwich, NR4 7UQ, United Kingdom.
   6. Ontario Institute for Cancer Research, Toronto, Canada
   7. Department of Computer Science, University of Toronto, Toronto, Canada
   8. Michael Smith Laboratories, University of British Columbia, Vancouver, Canada

## Background

We have sequenced the CEPH1463 (NA12878/GM12878, Ceph/Utah pedigree) human genome reference standard on the Oxford Nanopore MinION using 1D ligation kits (450 bp/s) using R9.4 chemistry (FLO-MIN106).

Human genomic DNA from GM12878 human cell line (Ceph/Utah pedigree) was either purchased from Coriell - "DNA" - (cat no NA12878) or extracted from the cultured cell line - "cells".  As the DNA is native, modified bases will be preserved.

## Data availability

Check back in the next few days for the remaining reads, alignments and raw signal-level reads.

### rel2

We have processed approximately 2/3rds of the total dataset.

The current release `rel2` consists of:

* 25 flowcells
* 58958035887 bases
* 9053909 reads

| flowcell_id | reads  | bases      | flowcell_id | Date     | Centre  | SampleType | Links                                                                                            | 
|-------------|--------|------------|-------------|----------|---------|------------|--------------------------------------------------------------------------------------------------| 
| FAB39075    | 466324 | 2439308482 | FAB39075    | 20/09/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4246400039-FAB39075.fastq.gz) | 
| FAB39043    | 305667 | 1543725551 | FAB39043    | 23/09/16 | Bham    | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3709921973-FAB39043.fastq.gz) | 
| FAB42706    | 400751 | 1857323339 | FAB42706    | 12/10/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4111103328-FAB42706.fastq.gz) | 
| FAB42316    | 107013 | 606761274  | FAB42316    | 14/10/16 | Notts   | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-216722908-FAB42316.fastq.gz)  | 
| FAB42205    | 312666 | 1664297400 | FAB42205    | 14/10/16 | Notts   | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3573838535-FAB42205.fastq.gz) | 
| FAB42561    | 231562 | 1510037000 | FAB42561    | 19/10/16 | Notts   | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-356443753-FAB42561.fastq.gz)  | 
| FAB42473    | 598480 | 3140575707 | FAB42473    | 20/10/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4179682758-FAB42473.fastq.gz) | 
| FAB42476    | 376897 | 2061807133 | FAB42476    | 27/10/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3843483077-FAB42476.fastq.gz) | 
| FAB42451    | 769524 | 4256154457 | FAB42451    | 28/10/16 | Notts   | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4239353418-FAB42451.fastq.gz) | 
| FAB42704    | 276151 | 1750146174 | FAB42704    | 28/10/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-87746129-FAB42704.fastq.gz)   | 
| FAB42810    | 265456 | 1665251718 | FAB42810    | 02/11/16 | Norwich | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-352384898-FAB42810.fastq.gz)  | 
| FAB46683    | 72602  | 286264094  | FAB46683    | 17/11/16 | Bham    | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4246923067-FAB46683.fastq.gz) | 
| FAB45332    | 530913 | 2863965040 | FAB45332    | 17/11/16 | UBC     | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-551111640-FAB45332.fastq.gz)  | 
| FAB43577    | 241646 | 1423672212 | FAB43577    | 18/11/16 | UCSC    | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3574887596-FAB43577.fastq.gz) | 
| FAB44989    | 558195 | 3443623448 | FAB44989    | 18/11/16 | UCSC    | DNA        | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-2567311907-FAB44989.fastq.gz) | 
| FAF01169    | 16489  | 120873419  | FAF01169    | 22/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-4245879798-FAF01169.fastq.gz) | 
| FAF01441    | 43281  | 358912895  | FAF01441    | 22/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3910073345-FAF01441.fastq.gz) | 
| FAB45277    | 53541  | 445614920  | FAB45277    | 22/11/16 | Notts   | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-86567043-FAB45277.fastq.gz)   | 
| FAB45321    | 299172 | 2583989736 | FAB45321    | 22/11/16 | Notts   | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-19064779-FAB45321.fastq.gz)   | 
| FAF01132    | 689781 | 5455971336 | FAF01132    | 25/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-84868110-FAF01132.fastq.gz)   | 
| FAF01127    | 632728 | 4972081712 | FAF01127    | 25/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-353303576-FAF01127.fastq.gz)  | 
| FAB49712    | 592317 | 4589575564 | FAB49712    | 28/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-622291475-FAB49712.fastq.gz)  | 
| FAF01253    | 442221 | 3476220233 | FAF01253    | 28/11/16 | Bham    | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-83756522-FAF01253.fastq.gz)   | 
| FAB49914    | 309162 | 2840857895 | FAB49914    | 28/11/16 | Notts   | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-3775529215-FAB49914.fastq.gz) | 
| FAB45271    | 461370 | 3601025148 | FAB45271    | 28/11/16 | Notts   | Cells      | [FASTQ](http://s3.climb.ac.uk/nanopore-human-wgs/rel2-nanopore-wgs-152889212-FAB45271.fastq.gz)  | 


Please verify downloads against <a href="lol.txt">MD5 hashes and list of links</a>.

# Read lengths

![Cellular library read length distribution](cells_readlength.png)

Figure: A typical read length distribution from a flowcell where we have run a cell-extracted DNA library. The y-axis shows the count of bases. Mean read length ~8.6kb with N50 of ~12.5kb (vertical line). Reads longer than 60kb are not expected due to limitations of the QIAGEN extraction kit employed.

# Acknowledgements

We would like to acknowledge the support of Oxford Nanopore Technologies in generating this dataset, with particular thanks to Rosemary Dokos, Oliver Hartwell, Jonathan Pugh and Clive Brown. We would like to thank Radoslaw Poplawski and Simon Thompson for technical assistance with configuration and optimising of the CLIMB platform file system.

# Contact

Please raise issues on this Github repository concerning this dataset. A preprint describing the dataset in more detail will be available shortly.

# History

    * rel1: 1st December 2016. Initial release.

