# Proposed `supports` mappings: AI resource metadata → non-CLAIM / non-TRAM-AI guidelines

**Source ontology:** ROADMAP 2026-08 (`ROADMAP.ttl`). **Proposal size:** 313 new `:supports` axioms over 52 metadata classes.

## Why these are missing today

In the shipped ontology, `:supports` axioms whose subject is an `AI resource metadata` class (03788) point only at **CLAIM items (62)**, **TRAM-AI items (8)**, **FAIR principles (18)** and **FUTURE-AI principles (17)**. The other ten guideline classes already in the ontology — STARD-AI, CONSORT-AI, SPIRIT-AI, TRIPOD+AI, DECIDE-AI, MINIMAR, MI-CLAIM, PROBAST+AI (development and evaluation), REFINE — are linked *only downward* to ethical principles, never *upward* from metadata. So a resource described with ROADMAP metadata can be checked against CLAIM but not against any of the others.

## Proposed mappings

### name (`03597`)
*Name of the AI resource, that is, the project, model, or dataset.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00497` REFINE item 1.1 | Model name, vendor/developer, version/identifier, release date, and training/knowledge cutoff date. |

### date (`00065`)
*The calendar date on which the AI resource has been created, published, or updated.*

| Guideline | Item | Item text |
|---|---|---|
| SPIRIT-AI | `00372` SPIRIT-AI item 3 | Date and version identifier. |
| REFINE | `00497` REFINE item 1.1 | Model name, vendor/developer, version/identifier, release date, and training/knowledge cutoff date. |

### publication date (`03420`)
*The date on which the AI resource has been published.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00517` REFINE item 4.4 | Prior dataset usage and publication date. |

### update date (`03421`)
*The date on which an AI resource was updated.*

| Guideline | Item | Item text |
|---|---|---|
| DECIDE-AI | `00584` DECIDE-AI item 11 - Modifications | Report any changes made to the AI system or its hardware platform during the study. Report the timing of th… |
| REFINE | `00531` REFINE item 5.8 | Model version comparisons and temporal performance variation. |

### version (`00066`)
*The number or date of the version of the AI resource.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| SPIRIT-AI | `00372` SPIRIT-AI item 3 | Date and version identifier. |
| DECIDE-AI | `00572` DECIDE-AI item 4 - Al system | a) Briefly describe the AI system, specifying its version and type of underlying algorithm used. Describe, … |
| REFINE | `00497` REFINE item 1.1 | Model name, vendor/developer, version/identifier, release date, and training/knowledge cutoff date. |
| REFINE | `00531` REFINE item 5.8 | Model version comparisons and temporal performance variation. |

### reference (`00067`)
*A reference about the resource, such as a clinical trial identifier or a pointer to a peer-reviewed publication or conference proceedings.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00322` STARD-AI item 37 | Where the full study protocol can be accessed. |
| CONSORT-AI | `00368` CONSORT-AI item 24 | Where the full trial protocol can be accessed, if available. |
| TRIPOD+AI | `00453` TRIPOD+AI item 18c | Indicate where the study protocol can be accessed or state that a protocol was not prepared. |
| DECIDE-AI | `00570` DECIDE-AI item III - Research governance | Provide a reference to any study protocol, study registration number, and ethics approval. |

### clinical trial number (`03623`)
*A clinical trial identifier, such as issues by ClinicalTrials.gov.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00321` STARD-AI item 36 | Registration number and name of registry. |
| CONSORT-AI | `00367` CONSORT-AI item 23 | Registration number and name of trial registry. |
| SPIRIT-AI | `00370` SPIRIT-AI item 2a | Trial identifier and registry name. |
| TRIPOD+AI | `00454` TRIPOD+AI item 18d | Provide registration information for the study, including register name and registration number, or state t… |
| DECIDE-AI | `00570` DECIDE-AI item III - Research governance | Provide a reference to any study protocol, study registration number, and ethics approval. |

### published results identifier (`03624`)
*A unique reference ID such as Digital Object Identifier or PubMed Identifier.*

| Guideline | Item | Item text |
|---|---|---|
| DECIDE-AI | `00572` DECIDE-AI item 4 - Al system | a) Briefly describe the AI system, specifying its version and type of underlying algorithm used. Describe, … |
| REFINE | `00514` REFINE item 4.1 | Dataset name, version, access type, source citation, license, and compliance statement. |

### license (`00068`)
*The licensing model under which the model or dataset is made available, for example, CC 4.0 BY-ND-NC.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00369` CONSORT-AI item 25 | Sources of funding and other support (such as supply of drugs), role of funders. State whether and how the … |
| SPIRIT-AI | `00413` SPIRIT-AI item 29 | Dataset access. Access to AI code. |
| TRIPOD+AI | `00461` TRIPOD+AI item 22 | Provide details of the full prediction model (e.g., formula, code, object, API) to allow predictions in new… |
| DECIDE-AI | `00591` DECIDE-AI item 17 - Data availability | Disclose if and how data and relevant code are available. |
| MINIMAR | `00565` MINIMAR item 4.4 - Transparency | How code and data are shared with the community.. |
| MI-CLAIM | `00611` MI-CLAIM item 19 | Reproducibility: choose appropriate tier of transparency. |
| REFINE | `00503` REFINE item 1.7 | Sharing of code, data, and model artifacts. |
| REFINE | `00514` REFINE item 4.1 | Dataset name, version, access type, source citation, license, and compliance statement. |

### contact information (`00069`)
*Physical address or email address of a contact.*

| Guideline | Item | Item text |
|---|---|---|
| SPIRIT-AI | `00374` SPIRIT-AI item 5a | Names, affiliations, roles of contributors. |
| SPIRIT-AI | `00375` SPIRIT-AI item 5b | Trial sponsor contact info. |

### summary (`00167`)
*Textual summary of an AI resource.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00280` STARD-AI item 02 | Structured summary of study design, methods, results and conclusions (for specific guidance, please see STA… |
| CONSORT-AI | `00333` CONSORT-AI item 1b | Structured summary of trial design, methods, results, and conclusions (for specific guidance see CONSORT fo… |
| TRIPOD+AI | `00421` TRIPOD+AI item 02 | See TRIPOD+AI for Abstracts checklist. |
| DECIDE-AI | `00567` DECIDE-AI item I - Abstract | Provide a structured summary of the study. Consider including: intended use of the AI system, type of under… |

### funding (`03385`)
*Source(s) of support, monetary or otherwise.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00324` STARD-AI item 39 | Commercial interests, if applicable. |
| CONSORT-AI | `00369` CONSORT-AI item 25 | Sources of funding and other support (such as supply of drugs), role of funders. State whether and how the … |
| SPIRIT-AI | `00373` SPIRIT-AI item 4 | Sources and types of support. |
| SPIRIT-AI | `00376` SPIRIT-AI item 5c | Role of sponsor and funders. |
| TRIPOD+AI | `00462` TRIPOD+AI item 18a | Give the source of funding and the role of the funders for the present study. |
| TRIPOD+AI | `00452` TRIPOD+AI item 18b | Declare any conflicts of interest and financial disclosures for all authors. |
| DECIDE-AI | `00592` DECIDE-AI item X - Conflicts of interest | Disclose any relevant conflicts of interest, including the source of funding for the study, the role of fun… |

### ethical review (`03418`)
*Describes the ethical review of the AI resource by an Institutional Review Board (IRB) or other review body.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00284` STARD-AI item 06 | Formal approval from an ethics committee. If not required, justify why. |
| SPIRIT-AI | `00407` SPIRIT-AI item 24 | IRB approval plans. |
| SPIRIT-AI | `00409` SPIRIT-AI item 26a | Informed consent process. |
| TRIPOD+AI | `00451` TRIPOD+AI item 17 | Name the institutional research board or ethics committee that approved the study and describe the particip… |
| DECIDE-AI | `00570` DECIDE-AI item III - Research governance | Provide a reference to any study protocol, study registration number, and ethics approval. |
| REFINE | `00516` REFINE item 4.3 | Ethics and consent statements. |

### link (`03723`)
*Uniform Resource Identifier (URI) of the site where the resource (model, dataset, or project) can be obtained.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00369` CONSORT-AI item 25 | Sources of funding and other support (such as supply of drugs), role of funders. State whether and how the … |
| SPIRIT-AI | `00413` SPIRIT-AI item 29 | Dataset access. Access to AI code. |
| TRIPOD+AI | `00455` TRIPOD+AI item 18e | Provide details of the availability of the study data. |
| TRIPOD+AI | `00456` TRIPOD+AI item 18f | Provide details of the availability of the analytical code7. |
| TRIPOD+AI | `00461` TRIPOD+AI item 22 | Provide details of the full prediction model (e.g., formula, code, object, API) to allow predictions in new… |
| DECIDE-AI | `00591` DECIDE-AI item 17 - Data availability | Disclose if and how data and relevant code are available. |
| MINIMAR | `00565` MINIMAR item 4.4 - Transparency | How code and data are shared with the community.. |
| REFINE | `00502` REFINE item 1.6 | Model access. |
| REFINE | `00503` REFINE item 1.7 | Sharing of code, data, and model artifacts. |

### model use (`00011`)
*The ways in which a model is used: can include intended uses, out-of-scope uses, and excluded uses.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00281` STARD-AI item 03 | Scientific and clinical background, including the intended use of the index test, whether it is novel or an… |
| STARD-AI | `00319` STARD-AI item 34 | Implications for practice, including the intended use and clinical role of the index test. |
| CONSORT-AI | `00332` CONSORT-AI item 01a | Identification as a randomized trial in the title. Indicate that the intervention involves artificial intel… |
| CONSORT-AI | `00334` CONSORT-AI item 2a | Scientific background and explanation of rationale. Explain the intended use of the AI intervention in the … |
| SPIRIT-AI | `00345` SPIRIT-AI item 1 | Descriptive title identifying study design, population, interventions, and trial acronym. Indicate interven… |
| SPIRIT-AI | `00378` SPIRIT-AI item 6a | Research question and justification. Explain intended AI use in clinical pathway. Describe pre-existing evi… |
| TRIPOD+AI | `00423` TRIPOD+AI item 03b | Describe the target population and the intended purpose of the prediction model in the context of the care … |
| DECIDE-AI | `00588` DECIDE-AI item 15 - Support for intended use | Discuss whether the results obtained support the intended use of the AI system in clinical settings. |
| DECIDE-AI | `00568` DECIDE-AI item 2 - Intended use | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and … |
| MI-CLAIM | `00593` MI-CLAIM item 01 | The clinical problem in which the model will be employed is clearly detailed in the paper. |
| REFINE | `00534` REFINE item 6.1 | Declared intended application and scope of use. |

### out-of-scope model use (`00013`)
*Out-of-scope model use refers to applying a machine learning model, AI system, or project deliverable to tasks, data, or environments outside its intended desig*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00537` REFINE item 6.4 | Model limitations, explicit clinical non-use cases, and potential misuse considerations. |

### excluded model use (`00014`)
*An excluded model use is the application of an AI model to tasks, data, or environments where it should not be used.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00537` REFINE item 6.4 | Model limitations, explicit clinical non-use cases, and potential misuse considerations. |

### model user (`00036`)
*The types of individuals who might use the model: can include intended, out-of-scope, and excluded users.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00296` STARD-AI item 15d | The specified end user of the index test and the level of expertise required of users. |
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| CONSORT-AI | `00334` CONSORT-AI item 2a | Scientific background and explanation of rationale. Explain the intended use of the AI intervention in the … |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| TRIPOD+AI | `00470` TRIPOD+AI item 27b | Discuss whether users will be required to interact in the handling of the input data or use of the model, a… |
| DECIDE-AI | `00568` DECIDE-AI item 2 - Intended use | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and … |
| MINIMAR | `00554` MINIMAR item 3.2 - Target user | The indented user of the model output (eg, clinician, hospital management team, insurance company). |

### decision threshold (`03351`)
*A decision threshold is the point at which a classification algorithm or model decides whether a case (or pixel) belongs to a certain category based on its rati*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00295` STARD-AI item 15c | Definition of and rationale for test positivity cut-offs or result categories of the index test, distinguis… |
| TRIPOD+AI | `00449` TRIPOD+AI item 15 | Specify the output of the prediction model (e.g., probabilities, classification). Provide details and ratio… |
| REFINE | `00511` REFINE item 3.1 | Generation parameters. |

### ethical consideration (`03352`)
*The set of moral principles, guidelines, and techniques used to ensure that artificial intelligence is developed, deployed, and used in ways that are fair, tran*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00320` STARD-AI item 35 | Ethical considerations and adherence to ethical standards associated with the use of the index test and iss… |
| TRIPOD+AI | `00448` TRIPOD+AI item 14 | Describe any approaches that were used to address model fairness and their rationale. |
| DECIDE-AI | `00578` DECIDE-AI item 8 - Ethics | Describe whether specific methodologies were utilised to fulfil an ethics-related goal (such as algorithmic… |
| REFINE | `00516` REFINE item 4.3 | Ethics and consent statements. |
| REFINE | `00540` REFINE item 6.7 | Governance, auditability, and oversight. |

### recommendation (`03354`)
*Text information to guide overall use of the AI model.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00319` STARD-AI item 34 | Implications for practice, including the intended use and clinical role of the index test. |
| DECIDE-AI | `00588` DECIDE-AI item 15 - Support for intended use | Discuss whether the results obtained support the intended use of the AI system in clinical settings. |
| REFINE | `00534` REFINE item 6.1 | Declared intended application and scope of use. |

### model availability (`03373`)

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00369` CONSORT-AI item 25 | Sources of funding and other support (such as supply of drugs), role of funders. State whether and how the … |
| SPIRIT-AI | `00413` SPIRIT-AI item 29 | Dataset access. Access to AI code. |
| TRIPOD+AI | `00456` TRIPOD+AI item 18f | Provide details of the availability of the analytical code7. |
| TRIPOD+AI | `00461` TRIPOD+AI item 22 | Provide details of the full prediction model (e.g., formula, code, object, API) to allow predictions in new… |
| DECIDE-AI | `00591` DECIDE-AI item 17 - Data availability | Disclose if and how data and relevant code are available. |
| MINIMAR | `00565` MINIMAR item 4.4 - Transparency | How code and data are shared with the community.. |
| MI-CLAIM | `00611` MI-CLAIM item 19 | Reproducibility: choose appropriate tier of transparency. |
| REFINE | `00502` REFINE item 1.6 | Model access. |
| REFINE | `00503` REFINE item 1.7 | Sharing of code, data, and model artifacts. |

### sustainability (`03376`)
*Describes parameters associated with use of the AI model related to energy consumption, running time, and other factors.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00504` REFINE item 1.8 | Computational requirements. |

### time to train model (`03377`)
*The amount of time required to train an AI model.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00504` REFINE item 1.8 | Computational requirements. |

### time to evaluate single input (`03378`)
*The amount of time required to apply a trained AI model to a single input.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00504` REFINE item 1.8 | Computational requirements. |

### required processors (`03379`)
*Information about the hardware needed to train and/or apply the model.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00504` REFINE item 1.8 | Computational requirements. |

### model input (`03481`)

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00293` STARD-AI item 15a | Index test, in sufficient detail to allow replication. |
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| CONSORT-AI | `00338` CONSORT-AI item 4a | Eligibility criteria for participants. State the inclusion and exclusion criteria at the level of participa… |
| SPIRIT-AI | `00383` SPIRIT-AI item 10 | Inclusion/exclusion criteria. Participant-level criteria. Input data criteria. |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| TRIPOD+AI | `00436` TRIPOD+AI item 09b | Clearly define all predictors, including how and when they were measured (and any actions to blind assessme… |
| TRIPOD+AI | `00469` TRIPOD+AI item 27a | Describe how poor quality or unavailable input data (e.g., predictor values) should be assessed and handled… |
| MINIMAR | `00559` MINIMAR item 3.7 - Features | List of variables used in the model and how they were used in the model in terms of categories or transform… |
| MI-CLAIM | `00602` MI-CLAIM item 10 | Is the input data type structured or unstructured? |
| PROBAST+AI dev | `00617` PROBAST+AI model development item 2.1 | Were predictors defined and assessed in a similar way for all participants? |
| PROBAST+AI dev | `00620` PROBAST+AI model development item 2.4 | Were the predictors included in the model available at the time the model was intended to be used? |
| PROBAST+AI dev | `00626` PROBAST+AI model development item 4.2 | Were continuous and categorical predictors handled appropriately? |
| PROBAST+AI eval | `00639` PROBAST+AI model evaluation item 2.1 | Were predictors defined and assessed in a similar way for all participants? |
| PROBAST+AI eval | `00642` PROBAST+AI model evaluation item 2.4 | Were the predictors included in the model available at the time the model was intended to be used? |
| REFINE | `00500` REFINE item 1.4 | Modality support details (input and output) and limitations. |
| REFINE | `00507` REFINE item 2.3 | Prompt modality, language, technical input specification, and full content. |

### model output (`03482`)
*Describes the type of output produced by the model, such as classification (diagnosis) results or image segmentation.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| TRIPOD+AI | `00449` TRIPOD+AI item 15 | Specify the output of the prediction model (e.g., probabilities, classification). Provide details and ratio… |
| MINIMAR | `00553` MINIMAR item 3.1 - Model output | The computed result of the model. |
| MINIMAR | `00557` MINIMAR item 3.5 - Model task | Classification or prediction. |
| REFINE | `00500` REFINE item 1.4 | Modality support details (input and output) and limitations. |
| REFINE | `00510` REFINE item 2.6 | Output handling. |

### model architecture (`03598`)
*Textual description of underlying model technology, e.g., \"Convolutional Neural Network\".*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00332` CONSORT-AI item 01a | Identification as a randomized trial in the title. Indicate that the intervention involves artificial intel… |
| SPIRIT-AI | `00345` SPIRIT-AI item 1 | Descriptive title identifying study design, population, interventions, and trial acronym. Indicate interven… |
| TRIPOD+AI | `00442` TRIPOD+AI item 12c | Specify the type of model, rationale2, all model-building steps, including any hyperparameter tuning, and m… |
| DECIDE-AI | `00572` DECIDE-AI item 4 - Al system | a) Briefly describe the AI system, specifying its version and type of underlying algorithm used. Describe, … |
| MINIMAR | `00558` MINIMAR item 3.6 - Model architecture | Algorithm type (eg, machine learning, deep learning, etc.). |
| MI-CLAIM | `00601` MI-CLAIM item 09 | Details on the models that were evaluated and the code developed to select the best model are provided. |
| REFINE | `00498` REFINE item 1.2 | Model architecture and key characteristics. |
| REFINE | `00499` REFINE item 1.3 | Model pretraining, post-training, and inference-time adaptation strategy. |

### indication for use (`03600`)

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00281` STARD-AI item 03 | Scientific and clinical background, including the intended use of the index test, whether it is novel or an… |
| TRIPOD+AI | `00422` TRIPOD+AI item 03a | Explain the healthcare context (including whether diagnostic or prognostic) and rationale for developing or… |
| DECIDE-AI | `00568` DECIDE-AI item 2 - Intended use | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and … |
| MI-CLAIM | `00593` MI-CLAIM item 01 | The clinical problem in which the model will be employed is clearly detailed in the paper. |
| REFINE | `00534` REFINE item 6.1 | Declared intended application and scope of use. |

### instructions for use (`03601`)
*Directions and recommendations for optimal use of the model.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| TRIPOD+AI | `00469` TRIPOD+AI item 27a | Describe how poor quality or unavailable input data (e.g., predictor values) should be assessed and handled… |
| TRIPOD+AI | `00470` TRIPOD+AI item 27b | Discuss whether users will be required to interact in the handling of the input data or use of the model, a… |
| DECIDE-AI | `00581` DECIDE-AI item 10 - Implementation | a) Report on the user exposure to the AI system, on the number of instances the AI system was used, and on … |
| REFINE | `00505` REFINE item 2.1 | Prompt engineering protocol with versioning. |
| REFINE | `00506` REFINE item 2.2 | Prompting strategy, format, and length. |
| REFINE | `00509` REFINE item 2.5 | Interaction style and session memory policy. |
| REFINE | `00535` REFINE item 6.2 | Clinical workflow integration. |

### regulatory information (`03602`)
*Information used to support or document regulatory review.*

| Guideline | Item | Item text |
|---|---|---|
| REFINE | `00540` REFINE item 6.7 | Governance, auditability, and oversight. |

### clinical benefit (`03612`)
*Clinical benefits, such as diagnosis, risk assessment, or treatment selection.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00319` STARD-AI item 34 | Implications for practice, including the intended use and clinical role of the index test. |
| CONSORT-AI | `00366` CONSORT-AI item 22 | Interpretation consistent with results, balancing benefits and harms, and considering other relevant evidence. |
| DECIDE-AI | `00588` DECIDE-AI item 15 - Support for intended use | Discuss whether the results obtained support the intended use of the AI system in clinical settings. |
| DECIDE-AI | `00568` DECIDE-AI item 2 - Intended use | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and … |
| MI-CLAIM | `00604` MI-CLAIM item 12 | The primary metric selected to evaluate the clinical utility of the model (e.g., PPV, NNT, etc.), including… |
| REFINE | `00536` REFINE item 6.3 | Measured clinical utility or added value. |

### clinical workflow phase (`03613`)
*A part of the activities involved in patient care.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00281` STARD-AI item 03 | Scientific and clinical background, including the intended use of the index test, whether it is novel or an… |
| CONSORT-AI | `00339` CONSORT-AI item 4b | Settings and locations where the data were collected. Describe how the AI intervention was integrated into … |
| SPIRIT-AI | `00382` SPIRIT-AI item 9 | Study settings and locations. Integration requirements for AI. |
| TRIPOD+AI | `00423` TRIPOD+AI item 03b | Describe the target population and the intended purpose of the prediction model in the context of the care … |
| DECIDE-AI | `00568` DECIDE-AI item 2 - Intended use | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and … |
| DECIDE-AI | `00573` DECIDE-AI item 5 - Implementation | a) Describe the settings in which the AI system was evaluated. |
| REFINE | `00535` REFINE item 6.2 | Clinical workflow integration. |

### degree of automation (`03614`)
*Degree of automation compared to the current standard of care, including whether the device supports or automates decision making.*

| Guideline | Item | Item text |
|---|---|---|
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| SPIRIT-AI | `00384` SPIRIT-AI item 11a | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI in… |
| TRIPOD+AI | `00470` TRIPOD+AI item 27b | Discuss whether users will be required to interact in the handling of the input data or use of the model, a… |
| DECIDE-AI | `00585` DECIDE-AI item 12 - Human-computer agreement | Report on the user agreement with the AI system. Describe any instances of and reasons for user variation f… |
| REFINE | `00535` REFINE item 6.2 | Clinical workflow integration. |

### reproducibility (`03620`)
*Describes the AI model's reproducibility associated with the provided outputs.*

| Guideline | Item | Item text |
|---|---|---|
| TRIPOD+AI | `00456` TRIPOD+AI item 18f | Provide details of the availability of the analytical code7. |
| MINIMAR | `00565` MINIMAR item 4.4 - Transparency | How code and data are shared with the community.. |
| MI-CLAIM | `00601` MI-CLAIM item 09 | Details on the models that were evaluated and the code developed to select the best model are provided. |
| MI-CLAIM | `00611` MI-CLAIM item 19 | Reproducibility: choose appropriate tier of transparency. |
| REFINE | `00511` REFINE item 3.1 | Generation parameters. |
| REFINE | `00529` REFINE item 5.6 | Output stochasticity and reproducibility constraints. |

### limitations (`03621`)
*Describes concerns specific to the use of the AI model.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00318` STARD-AI item 33 | Study limitations, including sources of potential bias, statistical uncertainty, and generalisability. |
| CONSORT-AI | `00364` CONSORT-AI item 20 | Trial limitations, addressing sources of potential bias, imprecision, and, if relevant, multiplicity of ana… |
| CONSORT-AI | `00365` CONSORT-AI item 21 | Generalizability (external validity, applicability) of the trial findings. |
| TRIPOD+AI | `00468` TRIPOD+AI item 26 | Discuss any limitations of the study (such as a non-representative sample, sample size, overfitting, missin… |
| DECIDE-AI | `00590` DECIDE-AI item IX - Strengths and limitations | Discuss the strengths and limitations of the study. |
| MI-CLAIM | `00610` MI-CLAIM item 18 | A discussion of the reliability and robustness of the model as the underlying data distribution shifts is i… |
| REFINE | `00500` REFINE item 1.4 | Modality support details (input and output) and limitations. |
| REFINE | `00537` REFINE item 6.4 | Model limitations, explicit clinical non-use cases, and potential misuse considerations. |

### known bias or failure mode (`03629`)
*Known circumstances where the device input will not align with the data used in development and validation.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00307` STARD-AI item 23 | Details of any performance error analysis, and algorithmic bias and fairness assessments if undertaken. |
| CONSORT-AI | `00363` CONSORT-AI item 19 | All important harms or unintended effects in each group (for specific guidance see CONSORT for harms). Desc… |
| SPIRIT-AI | `00405` SPIRIT-AI item 22 | Adverse events handling. AI performance errors analysis. |
| DECIDE-AI | `00586` DECIDE-AI item 13 - Safety and errors | a) List any significant errors/malfunctions related to: AI system recommendations, supporting software/hard… |
| DECIDE-AI | `00589` DECIDE-AI item 16 - Safety and errors | Discuss what the results indicate about the safety profile of the AI system. Discuss any observed errors/ma… |
| DECIDE-AI | `00575` DECIDE-AI item 6 - Safety and errors | a) Provide a description of how significant errors/malfunctions were defined and identified. |
| MI-CLAIM | `00610` MI-CLAIM item 18 | A discussion of the reliability and robustness of the model as the underlying data distribution shifts is i… |
| REFINE | `00527` REFINE item 5.4 | Subgroup performance and output bias assessment. |
| REFINE | `00528` REFINE item 5.5 | Failure analysis and error metrics. |
| REFINE | `00538` REFINE item 6.5 | Safety testing and monitoring protocols. |

### known data-characterization gap (`03630`)
*Known gaps in the data characterization, such as patient populations that are not well represented in development (e.g., training) or testing datasets, and ther*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00313` STARD-AI item 28 | Whether the datasets represent the distribution of the target condition that one would expect from the inte… |
| STARD-AI | `00314` STARD-AI item 29 | For external evaluation on an independent dataset, an assessment of how this differs from the training, val… |
| TRIPOD+AI | `00424` TRIPOD+AI item 03c | Describe any known health inequalities between sociodemographic groups. |
| TRIPOD+AI | `00459` TRIPOD+AI item 20c | For model evaluation, show a comparison with the development data of the distribution of important predicto… |
| MINIMAR | `00542` MINIMAR item 1.1 - Population | Population from which study sample was drawn. |
| MI-CLAIM | `00596` MI-CLAIM item 04 | The cohorts (training and test sets) are shown to be representative of real-world clinical settings. |
| PROBAST+AI dev | `00616` PROBAST+AI model development item 1.3 | Did the in- and exclusions of study participants result in a representative dataset? |
| PROBAST+AI eval | `00638` PROBAST+AI model evaluation item 1.3 | Did the in- and exclusions of study participants result in a representative dataset? |
| REFINE | `00519` REFINE item 4.6 | Sample characteristics and representational bias analysis. |

### annotation level (`00051`)
*Defines the level at which annotations were made, such as per patient, per image, etc.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00290` STARD-AI item 12 | Who undertook the annotations for the dataset (including experience levels and background) and how (within … |
| STARD-AI | `00297` STARD-AI item 16a | Reference standard, in sufficient detail to allow replication. |
| TRIPOD+AI | `00432` TRIPOD+AI item 08a | Clearly define the outcome that is being predicted and the time horizon, including how and when assessed, t… |
| MINIMAR | `00556` MINIMAR item 3.4 - Gold standard | Labeled data used to train and test the model. |
| PROBAST+AI dev | `00621` PROBAST+AI model development item 3.1 | Were outcomes defined and assessed appropriately? |
| PROBAST+AI dev | `00622` PROBAST+AI model development item 3.2 | Were outcomes defined and assessed in a similar way for all participants? |
| PROBAST+AI eval | `00643` PROBAST+AI model evaluation item 3.1 | Were outcomes defined and assessed appropriately? |
| PROBAST+AI eval | `00644` PROBAST+AI model evaluation item 3.2 | Were outcomes defined and assessed in a similar way for all participants? |
| REFINE | `00520` REFINE item 4.7 | Reference standard and annotator qualifications. |

### motivation (`03383`)
*Describes the specific purpose for which the dataset was created.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00281` STARD-AI item 03 | Scientific and clinical background, including the intended use of the index test, whether it is novel or an… |
| STARD-AI | `00282` STARD-AI item 04 | Study objectives and hypotheses. |
| CONSORT-AI | `00335` CONSORT-AI item 2b | Specific objectives or hypotheses. |
| SPIRIT-AI | `00378` SPIRIT-AI item 6a | Research question and justification. Explain intended AI use in clinical pathway. Describe pre-existing evi… |
| SPIRIT-AI | `00380` SPIRIT-AI item 7 | Objectives or hypotheses. |
| TRIPOD+AI | `00422` TRIPOD+AI item 03a | Explain the healthcare context (including whether diagnostic or prognostic) and rationale for developing or… |
| TRIPOD+AI | `00425` TRIPOD+AI item 04 | Specify the study objectives, including whether the study describes the development or validation of a pred… |
| DECIDE-AI | `00569` DECIDE-AI item II - Objectives | State the study objectives. |
| MI-CLAIM | `00594` MI-CLAIM item 02 | The research question is clearly stated. |

### sampling (`03396`)
*Describes how the data that form the dataset were selected.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00285` STARD-AI item 07 | Eligibility criteria: listing separate inclusion and exclusion criteria in the order that they are applied … |
| STARD-AI | `00286` STARD-AI item 08 | On what basis potentially eligible participants were identified (such as symptoms, results from previous te… |
| STARD-AI | `00287` STARD-AI item 09 | Where and when potentially eligible participants were identified (setting, location, and dates). |
| STARD-AI | `00289` STARD-AI item 11 | Source of the data and whether it has been routinely collected, specifically collected for the purpose of t… |
| STARD-AI | `00306` STARD-AI item 22 | Intended sample size and how it was determined. |
| CONSORT-AI | `00338` CONSORT-AI item 4a | Eligibility criteria for participants. State the inclusion and exclusion criteria at the level of participa… |
| SPIRIT-AI | `00383` SPIRIT-AI item 10 | Inclusion/exclusion criteria. Participant-level criteria. Input data criteria. |
| TRIPOD+AI | `00426` TRIPOD+AI item 05a | Describe the sources of data separately for the development and evaluation datasets (e.g., randomised trial… |
| TRIPOD+AI | `00429` TRIPOD+AI item 06b | Describe the eligibility criteria for study participants. |
| TRIPOD+AI | `00438` TRIPOD+AI item 10 | Explain how the study size was arrived at (separately for development and evaluation), and justify that the… |
| DECIDE-AI | `00571` DECIDE-AI item 3 - Participants | a) Describe how patients were recruited, stating the inclusion and exclusion criteria at both patient and d… |
| MINIMAR | `00544` MINIMAR item 1.3 - Data source | The source from which data were collected. |
| MINIMAR | `00545` MINIMAR item 1.4 - Cohort selection | Exclusion/inclusion criteria. |
| MI-CLAIM | `00595` MI-CLAIM item 03 | The characteristics of the cohorts (training and test sets) are detailed in the text. |
| PROBAST+AI dev | `00614` PROBAST+AI model development item 1.1 | Were appropriate data sources used? |
| PROBAST+AI dev | `00616` PROBAST+AI model development item 1.3 | Did the in- and exclusions of study participants result in a representative dataset? |
| PROBAST+AI dev | `00625` PROBAST+AI model development item 4.1 | Was there evidence that the sample size was reasonable? |
| PROBAST+AI eval | `00636` PROBAST+AI model evaluation item 1.1 | Were appropriate data sources used? |
| PROBAST+AI eval | `00638` PROBAST+AI model evaluation item 1.3 | Did the in- and exclusions of study participants result in a representative dataset? |
| PROBAST+AI eval | `00648` PROBAST+AI model evaluation item 4.2 | Was there evidence that the sample size was reasonable? |
| REFINE | `00515` REFINE item 4.2 | Dataset origin. |
| REFINE | `00518` REFINE item 4.5 | Dataset composition and data synthesis details. |

### sampling strategy (`03397`)
*Describes the sampling strategy: e.g., deterministic, probabilistic with specific sampling probabilities, etc.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00288` STARD-AI item 10 | Whether participants formed a consecutive, random, or convenience series. |
| TRIPOD+AI | `00426` TRIPOD+AI item 05a | Describe the sources of data separately for the development and evaluation datasets (e.g., randomised trial… |
| PROBAST+AI dev | `00615` PROBAST+AI model development item 1.2 | Was an appropriate study design used? |
| PROBAST+AI eval | `00637` PROBAST+AI model evaluation item 1.2 | Was an appropriate study design used? |

### population (`03401`)
*Describes the population (universe) from which the dataset was drawn.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00309` STARD-AI item 25 | Baseline demographic, clinical and technical characteristics of training, validation and test set, if appli… |
| STARD-AI | `00313` STARD-AI item 28 | Whether the datasets represent the distribution of the target condition that one would expect from the inte… |
| TRIPOD+AI | `00458` TRIPOD+AI item 20b | Report the characteristics overall and, where applicable, for each data source or setting, including the ke… |
| DECIDE-AI | `00580` DECIDE-AI item 9 - Participants | a) Describe the baseline characteristics of the patients included in the study, and report on input data mi… |
| MINIMAR | `00542` MINIMAR item 1.1 - Population | Population from which study sample was drawn. |
| MINIMAR | `00543` MINIMAR item 1.2 - Study setting | The setting in which the study was conducted (eg, academic medical left, community healthcare system, rural… |
| MINIMAR | `00547` MINIMAR item 2.1 - Age | Age of patients included in the study. |
| MINIMAR | `00548` MINIMAR item 2.2 - Sex | Sex breakdown of study cohort. |
| MINIMAR | `00549` MINIMAR item 2.3 - Race | Race characteristics of patients included in the study. |
| MINIMAR | `00550` MINIMAR item 2.4 - Ethnicity | Ethnicity breakdown of patients included in the study. |
| MINIMAR | `00551` MINIMAR item 2.5 - Socioeconomic status | A measure or proxy measure of the socioeconomic status of patients included in the study. |
| MI-CLAIM | `00595` MI-CLAIM item 03 | The characteristics of the cohorts (training and test sets) are detailed in the text. |
| MI-CLAIM | `00596` MI-CLAIM item 04 | The cohorts (training and test sets) are shown to be representative of real-world clinical settings. |
| REFINE | `00519` REFINE item 4.6 | Sample characteristics and representational bias analysis. |

### missing information (`03408`)
*Describes what information, if any, is missing from the dataset and explains why it is missing (for example, because it was unavailable).*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00303` STARD-AI item 19 | How indeterminate index test or reference standard results were handled. |
| STARD-AI | `00304` STARD-AI item 20 | How missing data on the index test and reference standard were handled. |
| CONSORT-AI | `00340` CONSORT-AI item 05 | The interventions for each group with sufficient details to allow replication, including how and when they … |
| SPIRIT-AI | `00402` SPIRIT-AI item 20c | Missing data handling. |
| TRIPOD+AI | `00439` TRIPOD+AI item 11 | Describe how missing data were handled. Provide reasons for omitting any data. |
| TRIPOD+AI | `00469` TRIPOD+AI item 27a | Describe how poor quality or unavailable input data (e.g., predictor values) should be assessed and handled… |
| DECIDE-AI | `00580` DECIDE-AI item 9 - Participants | a) Describe the baseline characteristics of the patients included in the study, and report on input data mi… |
| MINIMAR | `00560` MINIMAR item 3.8 - Missingness | How missingness was addressed: reported, imputed, or corrected. |
| PROBAST+AI dev | `00627` PROBAST+AI model development item 4.3 | Were participants with missing or censored data handled appropriately in the analysis? |
| PROBAST+AI eval | `00649` PROBAST+AI model evaluation item 4.3 | Were participants with missing or censored data handled appropriately in the analysis? |
| REFINE | `00522` REFINE item 4.9 | Missing data extent, mechanism, and handling. |

### relationships between instances (`03409`)
*Describes if and how any relationships between individual data items are made explicit.*

| Guideline | Item | Item text |
|---|---|---|
| TRIPOD+AI | `00440` TRIPOD+AI item 12a | Describe how the data were used (e.g., for development and evaluation of model performance) in the analysis… |
| TRIPOD+AI | `00443` TRIPOD+AI item 12d | Describe if and how any heterogeneity in estimates of model parameter values and model performance was hand… |
| MI-CLAIM | `00600` MI-CLAIM item 08 | The independence between training and test sets has been proven in the paper. |
| PROBAST+AI eval | `00651` PROBAST+AI model evaluation item 4.5 | If data splitting was done to create training and test datasets, was there evidence that data leakage was a… |
| REFINE | `00523` REFINE item 4.10 | Separation of training, fine-tuning, internal testing, and external testing datasets. |
| REFINE | `00521` REFINE item 4.8 | Preprocessing and data pairing/registration. |

### partitioning scheme (`03410`)
*Describes how a dataset was partitioned for training, optimization (\"validation\"), and testing.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00294` STARD-AI item 15b | How the index test was developed, including any training, validation, testing and external evaluation, deta… |
| STARD-AI | `00309` STARD-AI item 25 | Baseline demographic, clinical and technical characteristics of training, validation and test set, if appli… |
| TRIPOD+AI | `00440` TRIPOD+AI item 12a | Describe how the data were used (e.g., for development and evaluation of model performance) in the analysis… |
| TRIPOD+AI | `00442` TRIPOD+AI item 12c | Specify the type of model, rationale2, all model-building steps, including any hyperparameter tuning, and m… |
| MINIMAR | `00555` MINIMAR item 3.3 - Data splitting | How data were split for training, testing, and validation. |
| MINIMAR | `00563` MINIMAR item 4.2 - Internal model validation | Study internal validation. |
| MINIMAR | `00564` MINIMAR item 4.3 - External model validation | External validation using data from another setting. |
| MI-CLAIM | `00600` MI-CLAIM item 08 | The independence between training and test sets has been proven in the paper. |
| PROBAST+AI dev | `00635` PROBAST+AI model development item 4.5 | Were methods used to address potential model overfitting? |
| PROBAST+AI eval | `00647` PROBAST+AI model evaluation item 4.1 | Was model evaluation based on only apparent performance avoided? |
| PROBAST+AI eval | `00651` PROBAST+AI model evaluation item 4.5 | If data splitting was done to create training and test datasets, was there evidence that data leakage was a… |
| PROBAST+AI eval | `00652` PROBAST+AI model evaluation item 4.6 | If resampling methods were used to evaluate model performance, were all model development steps replicated … |
| REFINE | `00523` REFINE item 4.10 | Separation of training, fine-tuning, internal testing, and external testing datasets. |

### noise (`03411`)
*Describes any errors, sources of noise, or redundancies in the dataset.*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00318` STARD-AI item 33 | Study limitations, including sources of potential bias, statistical uncertainty, and generalisability. |
| TRIPOD+AI | `00431` TRIPOD+AI item 07 | Describe any data pre-processing and quality checking, including whether this was similar across relevant s… |
| PROBAST+AI dev | `00618` PROBAST+AI model development item 2.2 | Was any pre-processing of predictors similar for all participants? |
| PROBAST+AI eval | `00640` PROBAST+AI model evaluation item 2.2 | Was any pre-processing of predictors similar for all participants? |
| REFINE | `00521` REFINE item 4.8 | Preprocessing and data pairing/registration. |

### external data (`03412`)
*Describes any external resources such as web sites, social-media posts or other datasets. Include information about their permanence, archival versions, and any*

| Guideline | Item | Item text |
|---|---|---|
| STARD-AI | `00289` STARD-AI item 11 | Source of the data and whether it has been routinely collected, specifically collected for the purpose of t… |
| STARD-AI | `00314` STARD-AI item 29 | For external evaluation on an independent dataset, an assessment of how this differs from the training, val… |
| TRIPOD+AI | `00450` TRIPOD+AI item 16 | Identify any differences between the development and evaluation data in healthcare setting, eligibility cri… |
| MINIMAR | `00544` MINIMAR item 1.3 - Data source | The source from which data were collected. |
| MINIMAR | `00564` MINIMAR item 4.3 - External model validation | External validation using data from another setting. |
| MI-CLAIM | `00598` MI-CLAIM item 06 | The origin of the data is described and the original format is detailed in the paper. |
| PROBAST+AI dev | `00614` PROBAST+AI model development item 1.1 | Were appropriate data sources used? |
| PROBAST+AI eval | `00636` PROBAST+AI model evaluation item 1.1 | Were appropriate data sources used? |
| REFINE | `00515` REFINE item 4.2 | Dataset origin. |
| REFINE | `00517` REFINE item 4.4 | Prior dataset usage and publication date. |

### confidentiality (`03413`)
*Describes any data that might be confidential, such as those protected by law or doctor-patient confidentiality.*

| Guideline | Item | Item text |
|---|---|---|
| SPIRIT-AI | `00399` SPIRIT-AI item 19 | Data entry and storage. |
| SPIRIT-AI | `00411` SPIRIT-AI item 27 | Participant data protection. |
| REFINE | `00516` REFINE item 4.3 | Ethics and consent statements. |
| REFINE | `00539` REFINE item 6.6 | Data security and privacy safeguards. |

### risk of re-identification (`03415`)
*Describes if and how it is possible to identify individual persons, either directly or indirectly, from the dataset.*

| Guideline | Item | Item text |
|---|---|---|
| SPIRIT-AI | `00411` SPIRIT-AI item 27 | Participant data protection. |
| REFINE | `00516` REFINE item 4.3 | Ethics and consent statements. |
| REFINE | `00539` REFINE item 6.6 | Data security and privacy safeguards. |

### sensitive data (`03416`)
*Describes any data that might be considered sensitive.*

| Guideline | Item | Item text |
|---|---|---|
| SPIRIT-AI | `00411` SPIRIT-AI item 27 | Participant data protection. |
| REFINE | `00516` REFINE item 4.3 | Ethics and consent statements. |
| REFINE | `00539` REFINE item 6.6 | Data security and privacy safeguards. |

## Coverage and residual gaps

Item counts reached by the proposal (items with >=1 metadata element mapped to them):

| Guideline | Items reached | Total items |
|---|---|---|
| STARD-AI | 28 | 48 |
| CONSORT-AI | 14 | 37 |
| SPIRIT-AI | 19 | 51 |
| TRIPOD+AI | 31 | 52 |
| DECIDE-AI | 19 | 27 |
| MINIMAR | 20 | 21 |
| MI-CLAIM | 11 | 19 |
| PROBAST+AI dev | 12 | 16 |
| PROBAST+AI eval | 13 | 18 |
| REFINE | 34 | 44 |

The unreached items fall into three groups, and the reason matters for the ontology, not just for the mapping:

1. **Trial-conduct items** (CONSORT-AI randomisation/blinding/analysis, SPIRIT-AI protocol governance, STARD-AI flow diagrams). These describe the *study*, not the *AI resource*. No metadata element should map to them; they are correctly out of scope for `AI resource metadata`.
2. **Performance-reporting items** (REFINE 5.1/5.3/5.10, MI-CLAIM 11/13, TRIPOD+AI 12e/23a, PROBAST+AI eval 4.7, DECIDE-AI VII). ROADMAP models performance through `metric` (03642) and `performance criterion` (04043), which sit under `evaluation entity` (00659) — **outside** the declared domain of `:supports` (`guideline item` ∪ `AI resource metadata`). To connect these, either widen the `:supports` domain to include evaluation entities, or add a `performance report` metadata class under 03788.
3. **Metadata elements that do not yet exist.** Notably: data pre-processing / transformation (MI-CLAIM 07, TRIPOD+AI 07, REFINE 4.8, PROBAST+AI 2.2 — `pre-processing` 00126 exists but under `image characteristic`, outside 03788); prompt/interaction parameters (REFINE 2.4, 3.2, 3.3); human-factors and usability evaluation (DECIDE-AI 7/14); patient and public involvement (TRIPOD+AI 19, DECIDE-AI VI); and language capability (REFINE 1.5).

Also worth noting: `carbon footprint calculation` (03380) and `comments` (00070) have no plausible target in any of the ten guidelines, and `regulatory information` (03602) reaches only REFINE 6.7 — regulatory status is essentially unreported by the academic guidelines, which is itself a finding.
