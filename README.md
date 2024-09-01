# Introduction

Code to study the effect of Hypoxia inducible factor-1A on the metabolic functions of hepatocellular carcinoma.
# Computational Framework
This pipeline performs the following tasks:

- Retrieve the data from TCGA using the GDC package
- Data filtering and normalization
- Differential expression analysis using deseq2 package
- Data visualization for the results in the form of a volcano plot using ggplot2
- Data visualization based on the different groups we had using boxplot
- Principal Component Analysis to identify and visualize the most significant components and their correlation to demographic data. 
- Survival Analysis to examine the correlation between candidate genes expression levels and patient survival times.

## Installation and Prerequisites

the whole pipeline is developed with the R language 
## Installation and prerequisites
- Rstudio version 4.1.2 (2021-11-01)
- install the required packages 
Use the R installation [install.package](https://www.rdocumentation.org/packages/utils/versions/3.6.2/topics/install.packages) to install the following packages.

- R packages: 

	-DESeq2 1.18.0
	-ggplot2 1.6.3 
	-tidyr
	-GDC -ggplot2
	-survival 3.5.7
	-cowplot 1.1.3
	-survminer 0.4.9
	-ggplot2 3.5.1


-Bioconductor annotations for:
 Human: org.Hs.eg.db


```R
install.package("deseq2")
```


## Download

- download the project as a zip file and then import the zip file as a project in Rstudio 
- Use git clone

## Usage
Download our RNAseq pipeline. Make sure all dependencies are installed and the right paths are set in the pipeline.

make sure that all the used packages are installed before running the code.

The initial data download step from TCGA can be bypassed by utilizing the pre-existing data file named "Gene_Counts.zip" within the designated "data" folder. This Gene_Counts file can be directly employed for conducting Deseq2_analysis.
