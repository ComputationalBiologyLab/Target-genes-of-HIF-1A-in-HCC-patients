# Introduction

Code to study the effect of Hypoxia inducible factor-1A on the metabolic functions of hepatocellular carcinoma.
# Computational Framework
This pipeline performs the following tasks:

- Retrieve the data from TCGA using the GDC package
- Data filtering and normalization
- Differential expression analysis using deseq2 package
- Data visualization for the results in the form of a volcano plot using ggplot2
- Data visualization based on the different groups we had using boxplot

the whole pipeline is developed with the R language 
## Installation and prerequisites
- Rstudio version 4.1.2 (2021-11-01)
- install the required packages 
Use the R installation [install.package](https://www.rdocumentation.org/packages/utils/versions/3.6.2/topics/install.packages) to install the following packages.

- R packages: 

-DESeq2 1.18.0

-ggplot2 1.6.3

-GDC
-ggplot2

-dplyr

-tidyr

-Bioconductor annotations for:
 Human: org.Hs.eg.db


```R
install.package("deseq2")
```


## Download

- download the project as a zip file and then import the zip file as a project in Rstudio 
- Use git clone:

git clone git@github.com:UMCUGenetics/RNASeq.git

## Usage
Download our RNAseq pipeline. Make sure all dependencies are installed and the right paths are set in the pipeline.

make sure that all the used packages are installed before running the code


