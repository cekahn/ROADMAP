**Dataset Name**: "TotalSegmentator Dataset"

**Imaging Details**:

  - "CT images"
  - "1.5 mm isotropic resolution"
  - "3 mm isotropic resolution"
  - "Various slice thickness"
  - "Different contrast phases: native, arterial, portal venous, late phase, and others"

**File Format**:

  - "nrrd"

**Resolution**: "1.5-mm isotropic and 3-mm isotropic resolutions are used for images"

**Burned In Phi**: "Not mentioned"

**Labeling**: "The dataset contains segmentations of 104 anatomic structures (27 organs, 59 bones, 10 muscles, and eight vessels). Annotation was supervised by two physicians."

**Missing Information**: "CT series of upper and lower extremities, CT series with missing slices, and series where structures were distorted due to abnormalities were excluded."

**Relationships Between Instances**: "No specific relationships like longitudinal studies are pointed out, dataset contains different patients."

**Noise**: "Images with high ambiguity or distortion were excluded"

**External Data**: "The study does not mention the use of external data."

**Confidentiality**: "The dataset was collected with approval from Ethics Committee Northwest and Central Switzerland, stating that an ethics waiver was applicable for the retrospective study."

**Subpopulations**: "Includes patients with various abnormalities: tumor, vascular, trauma, inflammation, bleeding and also patients with no abnormalities, distributed by age and different CT scan setups."

**Re Identification**: "Not directly mentioned, but since it is a medical dataset and includes CT images with anatomical structures, re-identification risks cannot be fully ruled out without anonymization."

**Collection Process**: "1368 CT examinations were randomly sampled from the University Hospital Basel's PACS, excluding those with missing slices or ambiguous segments. The final dataset included 1204 examinations across various years and conditions."

**Composition**: "1204 CT examinations; samples exhibit high variance in terms of slice thickness, resolution, and contrasts, including both normal and abnormal pathology cases."

**Number Of Instances**: "1204 CT examinations for training; 4004 whole-body CT examinations for an aging study."

**Representativeness**: "The dataset is characterized as a real-world dataset containing CT images randomly sampled from routine clinical studies."

**Verification**: "Real-world clinical settings verification."

**Motivation**: "To improve the accessibility and coverage of segmentation models for a wide array of anatomical structures on CT Imaging."

**Purpose**: "To develop a model for robust and accurate segmentation of 104 anatomical structures usable in general radiology and specific surgical or therapeutic planning."

**Partioning Scheme**: "90% training, 5% validation, 5% test"

**Partitions**:

| Subset Name | Subset Description | Site Count | Patient Count | Number Instances | Age | Sex | Demographic | Criterion |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Training | Dataset for training the nnU-Net model | 8 | 1082 | 1082 CT examinations | Diverse age range | Includes both male and female | Not explicitly detailed, includes multiple abnormality types | Includes 104 segmented anatomical structures, excluding ambiguous and distorted CT instances |
| Validation | Dataset for validating the nnU-Net model | 8 | 57 | 57 CT examinations | Diverse age range | Includes both male and female | Not explicitly detailed, includes multiple abnormality types | Includes 104 segmented anatomical structures, excluding ambiguous and distorted CT instances |
| Testing | Dataset to test the nnU-Net model | 8 | 65 | 65 CT examinations | Diverse age range | Includes both male and female | Not explicitly detailed, includes multiple abnormality types | Includes 104 segmented anatomical structures, excluding ambiguous and distorted CT instances |


**Dataset Availability**: "Publicly available."

**Dataset License**: "Public domain (https://doi.org/10.5281/zenodo.6802613)"

