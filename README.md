# RSNA-MICCAI Brain Tumor Radiogenomic Classification

## goal: Detect the presence of MGMT promoter methylation from the MRI images  

Domain Knowledge:  
  
Glioblastoma is the most common form of brain cancer and considered the deadliest human cancer.  
MGMT promoter methylation is the key mechanism of MGMT gene silencing and predicts a favorable outcome in patients with glioblastoma who are exposed to alkylating agent chemotherapy.
MGMT gene - ( 𝑂6
O
6
 -methylguanine-DNA methyltransferase) is a DNA repair enzyme that protects normal and glioma cells from alkylating chemotherapeutic agents.
Methylation - presence of it means that the gene is repressed (not expressed)
Thus, the goal of this competition is not on detecting tumors (since all the images in train and test sets have tumors/glioblastomas) but on predicting whether or not chemotherapy will be an effective treatment by predicting if the brain is methylated (MGMT_value=0) or not (MGMT_value=1). If successful, doctors will have better clinical decisions on the type of treatments to be given to their cancer patients with glioblastoma.
