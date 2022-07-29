# fork notes
The datasets used in the study are downloaded from reference [26], in which Chen et al. collected 495 miRNAs, 383 diseases and 5430 experimentally validated miRNA- disease associations from HMDD v2.0 [46].

# MKGAT
> Code and Datasets for "Predicting miRNA-disease associations based on graph attention networks and dual Laplacian regularized least squares" 

# Data description
* association: the miRNA_disease association matrix, which contain 5430 associations between 495 miRNAs and 383 diseases.
* sd: integrated disease similarity matrix.
* sm: integrated mirna similarity matrix.

# Environment Requirements
* Python 3.7
* Pytorch
* PyTorch Geometric
* numpy
* scipy

### Usage
```shell
git clone 
cd MKGAT/code
python main.py
```
