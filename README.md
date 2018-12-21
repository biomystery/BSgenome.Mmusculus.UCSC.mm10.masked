BSgenome.Mmusculus.UCSC.mm10.masked
====================

Added TRF masker into the orignial `BSgenome.Mmusculus.UCSC.mm10.masked`. Full masked genome sequences for Mus musculus (UCSC version mm10)                                                                        
* **Description**: Full genome sequences for Mus musculus (Mouse) as provided by UCSC (mm10, Dec. 2011) and stored in Biostrings objects. The sequences are the same as in BSgenome.Mmusculus.UCSC.mm10, except that each of them has the 2 following masks on top: (1) the mask of assembly gaps (AGAPS mask), (2) the mask of intra-contig ambiguities (AMB mask), (3) the mask of repeats from RepeatMasker (RM mask), and (4) the mask of repeats from Tandem Repeats Finder (TRF mask). Only the AGAPS and AMB masks are "active" by default.

## Requirement 
* [BSgenome.Mmusculus.UCSC.mm10](http://bioconductor.org/packages/release/data/annotation/html/BSgenome.Mmusculus.UCSC.mm10.html)


## Install 
``` Shell
git clone git@github.com:biomystery/BSgenome.Mmusculus.UCSC.mm10.masked.git
R CMD INSTALL BSgenome.Mmusculus.UCSC.mm10.masked
```
