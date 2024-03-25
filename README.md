# Identification of Cancer Risk Groups through Multi-Omics Integration using Autoencoder and Tensor Analysis



## The original data can be downloaded from linkedomics directly, or access the google drive(original/matched) via link https://drive.google.com/drive/folders/1-Duhzo_m4aCRvrT64GdcOYoPtQpt4zKj?usp=sharing


1. Breast Invasive Carcinoma (can be downloaded from https://drive.google.com/drive/folders/1xKUbh9XJrlS7OyI4eDgABqwXbF-eiJzX?usp=share_link)

retrieved from http://linkedomics.org/data_download/TCGA-BRCA/

Selected omics:

  (1) Methylation (CpG-site level, HM450K)

  (2) miRNA (HiSeq, Gene level)

  (3) RNAseq (HiSeq, Gene level)

  (4) SCNV (Focal level, log-ratio)

  (5) Clinical

2. Glioma (can be downloaded from https://drive.google.com/drive/folders/1ZFsTRkBtyTHrEQxi5f-XIYmWO8Kxs2LB?usp=share_link)

retrieved from http://linkedomics.org/data_download/TCGA-GBMLGG/

Selected omics:

  (1) Methylation (CpG-site level, HM450K)

  (2) miRNA (Gene level)

  (3) RNAseq (HiSeq, Gene level)

  (4) SCNV (Focal level, log-ratio)

  (5) Clinical


## Catalogue
## Datasets

#### Original Datasets

Containing the omics data before matching with the clinical

#### Data preprocessing

The omics data after matching with the clinical as well as the related code

#### Breast/Glioma datasets after feature extraction

The omics data after compressing it with each related autoencoder model.

Train set: generated by the saved trained autoencoder models(trained by training data), input: train set

Test set: generated by the saved trained autoencoder models(trained by training data), input: test set

#### Cp decomposed results sets

Containing the optimal results from CP decomposition

## Architecture and codes.
#### Autoencoder Models

The architecture of autoencoder models for each single omics

p.s. AE model for miRNA is migrated in one Jupyter notebook located in the Autoencoder models/Breast

#### Tensor Analysis

The process of migrating compressed omics data from different autoencoders and different omics

#### Code for Survival Analysis

The experiment of different clustering methods for survival analysis

#### Classification of TP of breast

The experiment and code for the classification on tumor purity from breast data.

## Results

#### Survival analysis results

The results from survival analysis




