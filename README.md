# PHRIC-hub
Track Hub for PCCR supported by RNA-RNA contacts derived from RIC-seq

## How it works:
1. Copy the link https://raw.githubusercontent.com/smargasyuk/PHRIC-hub/master/hub.txt
2. Go to UCSC Genome Browser: https://genome.ucsc.edu/
3. Open My Data -> Track Hubs
4. Select My Hubs 
5. Paste the link into the bar and press Add Hub 

Data is avaliable for:
- Human: hg19

## Tracks:

### RIC-seq contacts supporting PCCRs:
RNA-RNA contacts supporting PCCRs. Contacts were derived from RIC-seq data [GSE190214](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE190214) using RNAcontacts(https://github.com/smargasyuk/RNAcontacts) pipeline; PCCRs from [kalmSveta/PCCR](https://github.com/kalmSveta/PCCR) repository.

Two tracks are provided:
+ **All contacts**: contacts with handles in [-150; 150] windows around PCCR handles in any orientation;
+ **I/O contacts**: contacts with handles in [-100; 100] windows around PCCR handles in inner or outer orientation;


### PCCRs supported by RIC-seq:
PCCRs supported by RNA-RNA contacts derived from RIC-seq data. Similar to contact tracks, two PCCR tracks are provided: PCCRs supported by 'All contacts' and PCCRs supported by 'I/O contacts'.


