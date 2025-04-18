# awesome-long-reads
tools and notes  for long reads analysis

* [awesome-nanopore](https://github.com/GoekeLab/awesome-nanopore)
* https://labs.epi2me.io/ oxford Nanopore dataset and tutorials
* https://labs.epi2me.io/dataindex/

[slow5curl](https://github.com/BonsonW/slow5curl)  is a command line tool and a library and for fetching reads from remote BLOW5 files, which is built on top of slow5lib and libcurl. 

### Variant

* [Accelerated identification of disease-causing variants with ultra-rapid nanopore genome sequencing](https://www.nature.com/articles/s41587-022-01221-5)

* Pipeline is Dorado, minimap2, sniffles2, deepvariant, you can do it under 1 hour now https://x.com/erictdawson/status/1710118874300219881?s=20
https://developer.nvidia.com/blog/boosting-ultra-rapid-nanopore-sequencing-analysis-on-nvidia-dgx-a100/

* Dorado is a high-performance, easy-to-use, open source basecaller for Oxford Nanopore reads: https://github.com/nanoporetech/dorado

pipeline: Mapping: Minimap2 or NGMLR
SNVs: Clair3
SVs: Sniffles2
Phasing SNVs: WhatsHap
Phasing SVs: Sniffles2
Extend Phasing: PRINCESS-subtool
Phased Methylation: Nanopolish + PRINCESS-subtool
QC Statistics for each step

https://github.com/MeHelmy/princess
and https://github.com/epi2me-labs/wf-human-variation

* [Severus](https://github.com/KolmogorovLab/Severus) is a somatic structural variation (SV) caller for long reads (both PacBio and ONT).

* CTAT-LR-fusion: accurate fusion transcript identification from long and short read isoform sequencing at bulk or single cell resolution https://www.biorxiv.org/content/10.1101/2024.02.24.581862v1.full
* Detecting Somatic Mutations Without Matched Normal Samples Using Long Reads https://www.biorxiv.org/content/10.1101/2024.02.26.582089v1

###  DNA methylation.

* Mehtylartist [Tools for parsing and plotting methylation patterns from nanopore data](https://github.com/adamewing/methylartist)
* Computational analysis of DNA methylation from long-read sequencing https://www.nature.com/articles/s41576-025-00822-5

### RNA isoform

* [ESPRESSO: Robust discovery and quantification of transcript isoforms from error-prone long-read RNA-seq data](https://www.science.org/doi/10.1126/sciadv.abq5072)

### RNA modification

* [Enhanced detection of RNA modifications and mappability with high-accuracy nanopore RNA basecalling models](https://www.biorxiv.org/content/10.1101/2023.11.28.568965v1)
  
