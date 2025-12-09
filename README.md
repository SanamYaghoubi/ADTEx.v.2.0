# ADTEx.v.2.0/ Amarasinghe KC, Li J, Hunter SM, Ryland GL, Cowin PA, Campbell IG and Halgamuge SK: Inferring copy number and genotype in tumour exome data. BMC Genomics 2014, 15:732 doi: 10.1186/1471-2164-15-732

Introduction

ADTEx is a freely available software package coded using R statistical language and Python to detect somatic copy number variations (CNVs) and genotypes in tumour whole exome samples. ADTEx is suitable for paired tumour/matched normal samples. The overall algorithm consists of few steps including,

Calculate depth of coverage (DOC) ratios and B allele frequencies (BAFs)
Noise reduction in ratios
Apply first HMM to predict CNVs
Select heterozygous SNP loci in normal sample
Apply second HMM to predict genotypes
Availability

Source code, supporting files and user manual are freely available under GNU General Public License version 3.0 (GPLv3) for download for academic and non-profit use. A complete tutorial can be found here.

Installing ADTEx

Download ADTEx tarball and decompress it with the following command:
    tar -xvzf ADTEx.<version>.tar.gz
Operating System

Linux

Requirements

R statistical language (R2.15)
http://www.r-project.org/
wmtsa R package
http://cran.r-project.org/web/packages/wmtsa/index.html
DNAcopy R package
http://www.bioconductor.org/packages/release/bioc/html/DNAcopy.html
Python 2.7
http://www.python.org/
BEDTools
http://code.google.com/p/bedtools/
