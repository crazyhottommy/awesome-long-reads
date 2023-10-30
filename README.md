# awesome-long-reads
tools and notes  for long reads analysis

* [awesome-nanopore](https://github.com/GoekeLab/awesome-nanopore)
* https://labs.epi2me.io/ oxford Nanopore dataset and tutorials
* https://labs.epi2me.io/dataindex/


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

###  DNA methylation.

* Mehtylartist [Tools for parsing and plotting methylation patterns from nanopore data](https://github.com/adamewing/methylartist)

### RNA isoform

* [ESPRESSO: Robust discovery and quantification of transcript isoforms from error-prone long-read RNA-seq data](https://www.science.org/doi/10.1126/sciadv.abq5072)
  
