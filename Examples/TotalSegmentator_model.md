**Model Name**: "TotalSegmentator"

**Content Code**:

  - "CT - Computed Tomography"
  - "AI - Artificial Intelligence"

**Medical Task**: "Segmentation of 104 anatomic structures in CT images, including 27 organs, 59 bones, 10 muscles, and 8 vessels."

**Date Created**: "2023-07-05"

**License**: "Publicly available via Zenodo and GitHub"

**Funding**: "No funding declared."

**Use Case**:

  - "Segmentation"

**Users**:

  - "Radiologist"
  - "Researcher"
  - "Subspecialist diagnostic radiologist"

**Results**:

| Result Name | Result Metric | Result Value | Result Decision Threshold | Result Description | Result Subset Data |
| --- | --- | --- | --- | --- | --- |
| Model Performance on Test Set | Dice similarity coefficient | 0.943 | NA | High Dice score indicating accurate segmentation on the test set. | Test set of CT images including major abnormalities. |
| Comparison with Public Model | Dice score | 0.932 vs 0.871 | NA | TotalSegmentator significantly outperformed another publicly available segmentation model. | Separate dataset not included in the training set. |


**Caveats**: "The model works robustly across diverse clinical data but has typical failure cases such as missing small parts of organs or mixing up neighboring bones."

**Model Code Availability**: "Available at https://www.github.com/wasserth/TotalSegmentator"

**Sustainability**: "Requires less than 12 GB of RAM and does not require a GPU, which allows running on a normal laptop."

**Time To Train**: "Not specified."

**Time To Inference**: "Measured on local workstation with Intel Core i9 3.5-GHz CPU and NVIDIA GeForce RTX 3090 GPU."

**Hardware Requirements**: "Local workstation with Intel Core i9 3.5-GHz CPU and NVIDIA GeForce RTX 3090 GPU for checking inference runtime."

**Model Architecture**: "Utilizes nnU-Net segmentation algorithm with automated configuration of hyperparameters based on dataset characteristics."

