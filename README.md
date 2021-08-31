# RSNA-MICCAI Brain Tumor Radiogenomic Classification

## Goal: Predict the status of a genetic biomarker important for brain cancer treatment
  
**Glioblastoma-** is the most common form of brain cancer and considered the deadliest human cancer.

**MGMT promoter methylation-** is the key mechanism of MGMT gene silencing and predicts a favorable outcome in patients with glioblastoma who are exposed to alkylating agent chemotherapy.

Since all the images in train and test sets have tumors, we're not trying o detect tumors. we're trying to predict whether or not chemotherapy will be an effective treatment, and that is done by predicting the genetic subtype of glioblastoma, and more specifically the presence of MGMT promoter methylation.

### Data Set
These 3 cohorts are structured as follows: Each independent case has a dedicated folder identified by a five-digit number. Within each of these “case” folders, there are four sub-folders, each of them corresponding to each of the structural multi-parametric MRI (mpMRI) scans, in DICOM format. The exact mpMRI scans included are:

Fluid Attenuated Inversion Recovery (FLAIR)
T1-weighted pre-contrast (T1w)
T1-weighted post-contrast (T1Gd)
T2-weighted (T2)