<img src="https://www.bci.qmul.ac.uk/wp-content/uploads/2020/02/BCI_QMUL_blue_nofill.png" height="75" /> <img src="https://www.nds.ox.ac.uk/images/logos/secondary-logo" height="75" /> <img src="https://www.nds.ox.ac.uk/images/logos/primary-logo" height="75"/> <img src="https://github.com/user-attachments/assets/3615186f-6b02-4df3-a012-afe77714044a" height="75" />

<a href="https://twitter.com/intent/follow?screen_name=lambalastair">
<img src="https://img.shields.io/twitter/follow/lambalastair?style=social&logo=X",alt="follow on Twitter"></a>


[![](https://img.shields.io/badge/SPACEmapX-version0.99-blue.svg)](https://github.com/SPACEgroupX/SPACEgroupX/releases)[![](https://img.shields.io/github/last-commit/SPACEgroupX/SPACEmapX.svg)](https://github.com/SPACEgroupX/SPACEgroupX/commits/main)


# SPACEMapX - Spatial Phylogenetic Analysis and Clonal Evolution: MAPping the lethal clone (X) 

This guide operates as an explantation of a pipeline, built on inferCNV, to use inferred copy number status to determine cancer clonal dynamics from spatial transcriptomic data of Human tissue.

This pipeline uses data from the 10x Genomics Visium v2 platform, but can be easily modified to work with other spatial transcriptomic platforms.

Our particular goal has been identification of the "metastatic clone", defined as the clone which spreads from the primary tissue, in our case from the prostate to the lymph nodes. However, this pipeline can be used for any analysis of clonal evolution and/or somatic mosaicism in heterogeneous tissue.  

If you need any assistance with running this package, please feel free to contact us via GitHub "issue" messaging

## Pre-requirement
This pipeline is based on InferCNV v1.22.0 and Seurat v5.0.3, alongisde heavy use of tiydverse v2.0.0 and ggplot2 v3.5.2 with viridis v0.6.5 colour palette. 

# Funding 
This project was majority funded by Cancer Research UK (CRUK) #C57899/A25812 "Spatial Prostate Assessment and Circulating Environment – The SPACE Study"

The work was conducted by the group of Alastair Lamb at Oxford university and Queen Mary University London (QMUL) Barts Cancer Institute (BCI) alongside the group of Joakim Lundeburg's group based in the SciLifeLab in Sweden. The first author's of the associated publication are Mengxiao He, Sandy Figel and Max A. Beesley.
