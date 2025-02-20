**Model Name**: "An Artificial Neural Network for Nasogastric Tube Position Decision Support"

**Content Code**:

  - "AI - Artificial Intelligence"
  - "CH - Chest Radiology"

**Medical Task**: "Detection of nasogastric tube malposition on chest radiographs, with decision support for junior physicians in determining feeding safety"

**Date Created**: "2023-02-01"

**License**: "CC BY 4.0"

**Funding**: "Bering Limited and the Industrial Centre for AI Research in Digital Diagnostics (iCAIRD) funded by Innovate UK"

**Use Case**:

  - "Detection"
  - "Decision support"

**Users**:

  - "Diagnostic radiologist"
  - "General diagnostic radiologist"
  - "Radiologist"
  - "Radiology technologist"
  - "Researcher"
  - "Subspecialist diagnostic radiologist"
  - "Physician"

**Results**:

| Result Name | Result Metric | Result Value | Result Decision Threshold | Result Description | Result Subset Data |
| --- | --- | --- | --- | --- | --- |
| Testing Set Performance - Satisfactory Position | AUC | 0.82 | NA | Area under the ROC curve for detection of satisfactory nasogastric tube positions in testing set | Testing set of 355 images |
| Testing Set Performance - Malpositioned Position | AUC | 0.77 | NA | Area under the ROC curve for detection of malpositioned nasogastric tube positions in testing set | Testing set of 355 images |
| Testing Set Performance - Bronchial Position | AUC | 0.98 | NA | Area under the ROC curve for detection of bronchial nasogastric tube positions in testing set | Testing set of 355 images |
| Agreement with Radiologists - Unaided | Cohen κ | 0.53 ± 0.05 | NA | Mean agreement between junior physicians and radiologists on feeding decisions without AI support | Clinical evaluation set of 335 images |
| Agreement with Radiologists - AI-aided | Cohen κ | 0.65 ± 0.09 | NA | Mean agreement between junior physicians and radiologists on feeding decisions with AI support | Clinical evaluation set of 335 images |


**Caveats**: "Model limited to classifying NGT malpositions; not evaluated in typical radiologist workstation; relies on retrospective data which may not represent real-world prevalence; does not include lateral chest radiographs."

**Model Code Availability**: "Not specified in the text"

**Sustainability**: "Not detailed in the text"

**Time To Train**: "The low-resolution (764 × 764 pixels) and high-resolution (1024 × 1024 pixels) models trained for 16 and 19 epochs, respectively"

**Time To Inference**: "Not specified in the text"

**Hardware Requirements**: "Not specified in the text"

**Model Architecture**: "Neural network ensemble using modified InceptionV3 architecture with high and low resolution inputs."

