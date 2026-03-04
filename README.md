# Phylogenetics analysis of the CCR-NLR clade in green plants

[![DOI](https://img.shields.io/badge/bioRxiv-doi.org/10.1101/2024.09.19.613839-BE2634.svg)](https://doi.org/10.1101/2024.09.19.613839)

# Supporting scripts and material for "A helper NLR channels organellar calcium to trigger plant immunity "
Tarhan Ibrahim†, Freddie J. King†, AmirAli Toghani, Luyao Wang, Saskia Jenkins, Enoch Lok Him Yuen, Hung-Yu Wang, Cristina Vuolo, Nick Eilmann1, Vanda Adamkova, Khong-Sam Chia, Baptiste Castel, Jonathan D. G. Jones, Philip Carella, Chih-Hang Wu, Jiorgos Kourelis*, Sophien Kamoun*, Tolga O. Bozkurt*


Resources:
Software                            | Source
------------------------------------| ------------------------------------
*FAMSA v2.2.2*                      | ([https://github.com/refresh-bio/FAMSA](https://github.com/refresh-bio/FAMSA))
*MAFFT v7.525*                      | (https://github.com/GSLBiotech/mafft)
*ClipKIT v2.3.0*                    | ([https://github.com/GSLBiotech/mafft](https://github.com/JLSteenwyk/ClipKIT))
*FastTree v2.1.10*                  | ([http://www.microbesonline.org/fasttree/](http://www.microbesonline.org/fasttree/))
*IQ-TREE v3.0.1*                    | ([[http://www.microbesonline.org/fasttree/](http://www.microbesonline.org/fasttree/)](https://iqtree.github.io/))
*R v4.3.3*                          | ([https://cran.r-project.org/](https://cran.r-project.org/))
*NLRtracker*                        | ([https://github.com/slt666666/NLRtracker](https://github.com/slt666666/NLRtracker))



R packages:
```R
install.packages("tidyverse")

if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Biostrings")
install.packages("ggtree")
```
