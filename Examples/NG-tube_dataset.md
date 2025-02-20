**Dataset Name**: "Nasogastric Tube Position Decision Support Chest Radiographs"

**Imaging Details**:

  - "Frontal chest radiographs"

**File Format**:

  - "DICOM"

**Resolution**: "Resolution ranged from 253x902 to 4280x3520 pixels"

**Burned In Phi**: "No identifiable patient data"

**Labeling**: "Labeled for 'satisfactory position', 'malpositioned', or 'bronchial insertion' by three radiologists"

**Missing Information**: "None reported"

**Relationships Between Instances**: "Randomized into stratified sets, maintaining ground truth labels, sex, and view positions without overlapped patient identifiers among splits."

**Noise**: "No specific noise sources mentioned"

**External Data**: "None mentioned"

**Confidentiality**: "No identifiable patient data used, ethical approval granted without consent."

**Subpopulations**: "Demographics such as age and sex considered during stratification."

**Re Identification**: "Not possible, de-identified data used"

**Collection Process**: "Retrospective collection from NHS Greater Glasgow and Clyde. Ethics approval from Local Privacy and Advisory Committee."

**Composition**: "More than 1.13 million retrospectively collected frontal chest radiographs from 14 acute sites, further divided into training, validation, and testing sets."

**Number Of Instances**: "1,132,142 instances (retrospectively collected chest radiographs)"

**Representativeness**: "Collected from routine clinical practice without bias towards specific cases."

**Verification**: "Ground truth based on majority consensus of three certified radiologists."

**Motivation**: "To develop an AI tool for NGT malposition detection in chest radiographs."

**Purpose**: "To assist junior physicians with clinical decisions regarding NGT feeding safety."

**Partioning Scheme**: "Randomized into stratified training (90%), validation (5%), and testing (5%) sets"

**Partitions**:

| Subset Name | Subset Description | Site Count | Patient Count | Number Instances | Age | Sex | Demographic | Criterion |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Training Set | Images used for neural network pretraining and NGT model training | Multiple sites across NHS Greater Glasgow and Clyde | Not specified | 1,132,142 for general pretraining, 7,081 for specific NGT training and testing | Median 66.3 years ± 14.9 SD | Male to female ratio 1.4–1.5:1 | Included adults, excluding pediatrics | Images included if associated with NGT review request |
| Testing Set | Testing set for model performance evaluation | Multiple sites across NHS Greater Glasgow and Clyde | Not specified | 355 | Similar to training set, approximately 66.3 years median | Male to female ratio 1.4–1.5:1 | Matched to NGT model training set | Same as training set, ensuring no overlap in patient identifiers |
| Clinical Evaluation Set | Set for checking AI-assisted decisions | Multiple sites across NHS Greater Glasgow and Clyde | Not specified | 335 | 66.3–67.4 years old | Not specified | Not specified | Used by junior physicians for evaluation under AI support conditions |


**Dataset Availability**: "Not specified in extracted text, but de-identified and ethically approved for research."

**Dataset License**: "CC BY 4.0 license"

