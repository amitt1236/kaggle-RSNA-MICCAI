# RSNA-MICCAI Brain Tumor Radiogenomic Classification

## Goal: Predict the status of a genetic biomarker important for brain cancer treatment
  
**Glioblastoma-** is the most common form of brain cancer and considered the deadliest human cancer.

**MGMT promoter methylation-** is the key mechanism of MGMT gene silencing and predicts a favorable outcome in patients with glioblastoma who are exposed to alkylating agent chemotherapy.

Since all the images in train and test sets have tumors, we're not trying o detect tumors. we're trying to predict whether or not chemotherapy will be an effective treatment, and that is done by predicting the genetic subtype of glioblastoma, and more specifically the presence of MGMT promoter methylation.

## Data Set
These 3 cohorts are structured as follows: Each independent case has a dedicated folder identified by a five-digit number. Within each of these “case” folders, there are four sub-folders, each of them corresponding to each of the structural multi-parametric MRI (mpMRI) scans, in DICOM format. The exact mpMRI scans included are:

Fluid Attenuated Inversion Recovery (FLAIR)  
T1-weighted pre-contrast (T1w)  
T1-weighted post-contrast (T1Gd)  
T2-weighted (T2) 

### DICOM
DICOM® — Digital Imaging and Communications in Medicine — is the international standard for medical images and related information. It defines the formats for medical images that can be exchanged with the data and quality necessary for clinical use.

**pydicom**[https://pydicom.github.io/pydicom/stable/]

## Relevant papers for architecture ideas

**TimeSformer**[https://arxiv.org/pdf/2102.05095.pdf]

**TimeSformer implementation**[https://github.com/facebookresearch/TimeSformer]

**ViViT: A Video Vision Transformer**[https://arxiv.org/pdf/2103.15691v1.pdf]

**A 3D densely connected convolution neural network with connection-wise attention mechanism for Alzheimer's disease classification**[https://www.sciencedirect.com/science/article/pii/S0730725X21000138]

**An overview of deep learning in medical imaging focusing on MRI**[https://www.sciencedirect.com/science/article/pii/S0939388918301181]