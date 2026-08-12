# `:00198 supports` — audit tables

Generated from the current ROADMAP ontology. `:00198` is **not** transitive and has no property chain, so nothing here is inferred: every link shown is asserted.

| Code | Principle | Framework |
|---|---|---|
| F | findability | FAIR |
| A | accessibility | FAIR |
| I | interoperability | FAIR |
| R | reusability | FAIR |
| Un | universality | FUTURE-AI |
| Tr | traceability | FUTURE-AI |
| Ex | explainability | FUTURE-AI |
| Us | usability | FUTURE-AI |
| Ro | robustness | FUTURE-AI |
| Fa | fairness | FUTURE-AI |

---

## Table 1 — Metadata elements with a *direct* `supports` link to a principle

| ID | Metadata element | Principles | Also supports *n* guideline items |
|---|---|---|---|
| `:03788` | AI resource metadata | Tr | 0 |
| `:00051` | annotation level | Ro | 13 |
| `:00069` | contact information | A R Us | 3 |
| `:03351` | decision threshold | Ex Ro | 5 |
| `:03614` | degree of automation | Us | 6 |
| `:00068` | license | A R Us | 10 |
| `:03723` | link | F A | 11 |
| `:03598` | model architecture | I R | 11 |
| `:03373` | model availability | A R Us | 10 |
| `:03481` | model input | I | 19 |
| `:03482` | model output | I | 10 |
| `:03808` | model performance | Ro | 16 |
| `:00011` | model use | Us | 13 |
| `:00036` | model user | Us | 9 |
| `:03597` | name | F | 1 |
| `:03411` | noise | Ro | 6 |
| `:00067` | reference | R | 6 |
| `:03602` | regulatory information | Ro | 1 |
| `:03620` | reproducibility | Ro | 7 |
| `:03396` | sampling | Un | 27 |
| `:00167` | summary | F R Ex Us | 5 |
| `:00066` | version | F R Ro | 7 |

**22** metadata classes carry **36** direct principle links. The remaining 172 metadata classes reach principles only indirectly, through guideline items, or not at all.

---

## Table 2 — Guideline items appearing as subject or object of `supports`

Column 3 lists metadata elements that support the item. Column 4 lists principles the item supports.

| Guideline item | Definition | Metadata elements | Principles |
|---|---|---|---|
| **CLAIM item 01**<br>`:00203` | Identification as a study of AI methodology, specifying the category of technology used (e.g., deep learning). | model architecture | F |
| **CLAIM item 02**<br>`:00204` | Summary of study design, methods, results, and conclusions. | — | F Us |
| **CLAIM item 03**<br>`:00205` | Scientific and/or clinical background, including the intended use and role of the AI approach. | annotation level, annotator, clinical benefit, clinical workflow phase, indication for use, instructions for use, model use, model user, summary | R Un Ex Us |
| **CLAIM item 04**<br>`:00206` | Study aims, objectives, and hypotheses. | motivation | F Un Us |
| **CLAIM item 05**<br>`:00207` | Prospective or retrospective study. | — | Un Ro |
| **CLAIM item 06**<br>`:00208` | Study goal. | motivation | Un Us Ro |
| **CLAIM item 07**<br>`:00209` | Data sources. | model input, sampling | F A I R Un |
| **CLAIM item 08**<br>`:00210` | Inclusion and exclusion criteria. | sampling | R Un Ro Fa |
| **CLAIM item 09**<br>`:00211` | Data pre-processing. | pre-processing | I R Ro |
| **CLAIM item 10**<br>`:00212` | Selection of data subsets | partitioning scheme, sampling, subset criterion | R Ro Fa |
| **CLAIM item 11**<br>`:00213` | De-identification methods. | Protected Health Information, confidentiality, risk of re-identification, sensitive data | R Ro |
| **CLAIM item 12**<br>`:00214` | How missing data were handled. | missing information | R Un Ro |
| **CLAIM item 13**<br>`:00215` | Image acquisition protocol. | image characteristic, image file format | I R Un Ro |
| **CLAIM item 14**<br>`:00216` | Definition of method(s) used to obtain reference standard. | annotation level, annotator | I R Ex Ro |
| **CLAIM item 15**<br>`:00217` | Rationale for choosing the reference standard. | — | R Ex Ro |
| **CLAIM item 16**<br>`:00218` | Source of reference standard annotations. | annotation level, annotator | I R Ex Ro |
| **CLAIM item 17**<br>`:00219` | Annotation of test set. | annotation level, annotator | R Ro |
| **CLAIM item 18**<br>`:00221` | Measures of inter- and intra-rater variability of features described by the annotators. | annotator | Ex Ro |
| **CLAIM item 19**<br>`:00220` | How data were assigned to partitions. | partitioning scheme, relationships between instances | R Ro |
| **CLAIM item 20**<br>`:00223` | Level at which partitions are disjoint. | partitioning scheme, relationships between instances | R Ro |
| **CLAIM item 21**<br>`:00224` | Intended sample size. | count, sampling | Ro |
| **CLAIM item 22**<br>`:00225` | Detailed description of model. | decision threshold, degree of automation, model architecture, model input, model output | I R Ex Us Ro |
| **CLAIM item 23**<br>`:00226` | Software libraries, frameworks, and packages. | — | I R Us Ro |
| **CLAIM item 24**<br>`:00227` | Initialization of model parameters. | — | Ro |
| **CLAIM item 25**<br>`:00228` | Details of training approach. | missing information, model input | R Ex Ro |
| **CLAIM item 26**<br>`:00229` | Method of selecting the final model. | — | Un Ex Ro |
| **CLAIM item 27**<br>`:00230` | Ensembling techniques. | — | Ro |
| **CLAIM item 28**<br>`:00231` | Metrics of model performance. | model performance | Un Ex Us Ro Fa |
| **CLAIM item 29**<br>`:00232` | Statistical measures of significance and uncertainty. | model performance, uncertainty | Ro |
| **CLAIM item 30**<br>`:00233` | Robustness or sensitivity analysis. | noise, reproducibility | Un Ex Ro |
| **CLAIM item 31**<br>`:00234` | Methods for explainability or interpretability. | instructions for use, model architecture, model output | Ex Us |
| **CLAIM item 32**<br>`:00235` | Evaluation on internal data. | internal testing | Ro |
| **CLAIM item 33**<br>`:00236` | Testing on external data. | external testing | Un Ro |
| **CLAIM item 34**<br>`:00237` | Clinical trial registration. | — | F R |
| **CLAIM item 35**<br>`:00238` | Numbers of patients or examinations included and excluded. | count, sampling | R Un Fa |
| **CLAIM item 36**<br>`:00239` | Demographic and clinical characteristics of cases in each partition. | count, partitioning scheme, relationships between instances | I R Un |
| **CLAIM item 37**<br>`:00240` | Performance metrics and measures of statistical uncertainty. | model performance, uncertainty | Ex Us Ro Fa |
| **CLAIM item 38**<br>`:00241` | Estimates of diagnostic performance and their precision. | model performance, uncertainty | Ex Ro |
| **CLAIM item 39**<br>`:00242` | Failure analysis of incorrect results. | limitations, model output | Ex Ro Fa |
| **CLAIM item 40**<br>`:00243` | Study limitations. | limitations | Un Ex Ro |
| **CLAIM item 41**<br>`:00244` | Implications for practice, including intended use and/or clinical role. | clinical benefit, clinical workflow phase, decision threshold, indication for use, instructions for use, model use, model user, recommendation | R Un Ex Us Ro |
| **CLAIM item 42**<br>`:00245` | Provide a reference to the full study protocol or to additional technical details. | reference | F A R Un Us |
| **CLAIM item 43**<br>`:00246` | Statement about the availability of software, trained model, and/or data. | license, model availability, reference | F A R Us Ro |
| **CLAIM item 44**<br>`:00247` | Sources of funding and other support; role of funders. | funding | — |
| **CONSORT-AI item 01a**<br>`:00332` | Identification as a randomized trial in the title. Indicate that the intervention involves artificial intelligence/machine learning in the title and/or abstract and specify the type of model. State the intended use of the AI intervention within the trial in the title and/or abstract. | model architecture, model use | F |
| **CONSORT-AI item 01b**<br>`:00333` | Structured summary of trial design, methods, results, and conclusions (for specific guidance see CONSORT for abstracts). Indicate that the intervention involves artificial intelligence/machine learning in the title and/or abstract and specify the type of model. State the intended use of the AI intervention within the trial in the title and/or abstract. | summary | F |
| **CONSORT-AI item 02a**<br>`:00334` | Scientific background and explanation of rationale. Explain the intended use of the AI intervention in the context of the clinical pathway, including its purpose and its intended users (for example, healthcare professionals, patients, public). | model use, model user | R Ex Us |
| **CONSORT-AI item 02b**<br>`:00335` | Specific objectives or hypotheses. | motivation | F |
| **CONSORT-AI item 03a**<br>`:00336` | Description of trial design (such as parallel, factorial) including allocation ratio. | — | Ro |
| **CONSORT-AI item 04a**<br>`:00338` | Eligibility criteria for participants. State the inclusion and exclusion criteria at the level of participants. State the inclusion and exclusion criteria at the level of the input data. | model input, sampling | R Ro Fa |
| **CONSORT-AI item 04b**<br>`:00339` | Settings and locations where the data were collected. Describe how the AI intervention was integrated into the trial setting, including any onsite or offsite requirements. | clinical workflow phase | Un Us |
| **CONSORT-AI item 05**<br>`:00340` | The interventions for each group with sufficient details to allow replication, including how and when they were actually administered. State which version of the AI algorithm was used.Describe how the input data were acquired and selected for the AI intervention.Describe how poor quality or unavailable input data were assessed and handled.Specify whether there was human–AI interaction in the handling of the input data, and what level of expertise was required of users.Specify the output of the AI interventionExplain how the AI intervention’s outputs contributed to decision-making or other elements of clinical practice. | degree of automation, instructions for use, missing information, model input, model output, model user, version | I R Ex |
| **CONSORT-AI item 06a**<br>`:00341` | Completely defined pre-specified primary and secondary outcome measures, including how and when they were assessed. | — | Ro |
| **CONSORT-AI item 07a**<br>`:00343` | How sample size was determined. | — | Ro |
| **CONSORT-AI item 07b**<br>`:00344` | When applicable, explanation of any interim analyses and stopping guidelines. | — | Ro |
| **CONSORT-AI item 08a**<br>`:00346` | Method used to generate the random allocation sequence. | — | Ro |
| **CONSORT-AI item 08b**<br>`:00347` | Type of randomization; details of any restriction (such as blocking and block size). | — | Ro |
| **CONSORT-AI item 09**<br>`:00348` | Mechanism used to implement the random allocation sequence (such as sequentially numbered containers), describing any steps taken to conceal the sequence until interventions were assigned. | — | Ro |
| **CONSORT-AI item 11a**<br>`:00350` | If done, who was blinded after assignment to interventions (for example, participants, care providers, those assessing outcomes) and how. | — | Ro |
| **CONSORT-AI item 11b**<br>`:00351` | If relevant, description of the similarity of interventions. | — | Ro |
| **CONSORT-AI item 12a**<br>`:00352` | Statistical methods used to compare groups for primary and secondary outcomes. | — | Ro |
| **CONSORT-AI item 12b**<br>`:00353` | Methods for additional analyses, such as subgroup analyses and adjusted analyses. | — | Ex Fa |
| **CONSORT-AI item 13b**<br>`:00355` | For each group, losses and exclusions after randomization, together with reasons. | — | Fa |
| **CONSORT-AI item 14b**<br>`:00357` | Why the trial ended or was stopped. | — | Ex |
| **CONSORT-AI item 15**<br>`:00358` | A table showing baseline demographic and clinical characteristics for each group. | — | R Un Fa |
| **CONSORT-AI item 17a**<br>`:00360` | For each primary and secondary outcome, results for each group, and the estimated effect size and its precision (such as 95% confidence interval). | model performance | Ex Ro |
| **CONSORT-AI item 17b**<br>`:00361` | For binary outcomes, presentation of both absolute and relative effect sizes is recommended. | — | Ex |
| **CONSORT-AI item 18**<br>`:00362` | Results of any other analyses performed, including subgroup analyses and adjusted analyses, distinguishing pre-specified from exploratory. | — | Ex Fa |
| **CONSORT-AI item 19**<br>`:00363` | All important harms or unintended effects in each group (for specific guidance see CONSORT for harms). Describe results of any analysis of performance errors and how errors were identified, where applicable. If no such analysis was planned or done, justify why not. | known bias or failure mode | Ro Fa |
| **CONSORT-AI item 20**<br>`:00364` | Trial limitations, addressing sources of potential bias, imprecision, and, if relevant, multiplicity of analyses. | limitations | Un Ex |
| **CONSORT-AI item 21**<br>`:00365` | Generalizability (external validity, applicability) of the trial findings. | limitations | Un Ro |
| **CONSORT-AI item 22**<br>`:00366` | Interpretation consistent with results, balancing benefits and harms, and considering other relevant evidence. | clinical benefit | Ex Us |
| **CONSORT-AI item 23**<br>`:00367` | Registration number and name of trial registry. | clinical trial number | F |
| **CONSORT-AI item 24**<br>`:00368` | Where the full trial protocol can be accessed, if available. | reference | F A |
| **CONSORT-AI item 25**<br>`:00369` | Sources of funding and other support (such as supply of drugs), role of funders. State whether and how the AI intervention and/or its code can be accessed, including any restrictions to access or re-use. | funding, license, link, model availability | A |
| **DECIDE-AI item 1 - Title**<br>`:00566` | Identify the study as early clinical evaluation of a decision support system based on AI or machine learning, specifying the problem addressed. | — | F |
| **DECIDE-AI item 10 - Implementation**<br>`:00581` | a) Report on the user exposure to the AI system, on the number of instances the AI system was used, and on the users’ adherence to the intended implementation. | instructions for use | Us Ro |
| **DECIDE-AI item 11 - Modifications**<br>`:00584` | Report any changes made to the AI system or its hardware platform during the study. Report the timing of these modifications, the rationale for each, and any changes in outcomes observed after each of them. | update date | Ro |
| **DECIDE-AI item 12 - Human-computer agreement**<br>`:00585` | Report on the user agreement with the AI system. Describe any instances of and reasons for user variation from the AI system’s recommendations and, if applicable, users changing their mind based on the AI system’s recommendations. | degree of automation | Ex Us |
| **DECIDE-AI item 13 - Safety and errors**<br>`:00586` | a) List any significant errors/malfunctions related to: AI system recommendations, supporting software/hardware, or users. Include details of: (i) rate of occurrence, (ii) apparent causes, (iii) whether they could be corrected, and (iv) any significant potential impacts on patient care. | known bias or failure mode | Ex Ro Fa |
| **DECIDE-AI item 14 - Human factors**<br>`:00587` | a) Report on the usability evaluation, according to recognised standards or frameworks. | — | Ex Us |
| **DECIDE-AI item 15 - Support for intended use**<br>`:00588` | Discuss whether the results obtained support the intended use of the AI system in clinical settings. | clinical benefit, model use, recommendation | Ex Us |
| **DECIDE-AI item 16 - Safety and errors**<br>`:00589` | Discuss what the results indicate about the safety profile of the AI system. Discuss any observed errors/malfunctions and instances of harm, their implications for patient care, and whether/how they can be mitigated. | known bias or failure mode | Un Ex |
| **DECIDE-AI item 17 - Data availability**<br>`:00591` | Disclose if and how data and relevant code are available. | license, link, model availability | F A R |
| **DECIDE-AI item 2 - Intended use**<br>`:00568` | a) Describe the targeted medical condition(s) and problem(s), including the current standard practice, and the intended patient population(s). b) Describe the intended users of the AI system, its planned integration in the care pathway, and the potential impact, including patient outcomes, it is intended to have. | clinical benefit, clinical workflow phase, indication for use, model use, model user | R Ex Us |
| **DECIDE-AI item 3 - Participants**<br>`:00571` | a) Describe how patients were recruited, stating the inclusion and exclusion criteria at both patient and data level, and how the number of recruited patients was decided. | sampling | R Ro Fa |
| **DECIDE-AI item 4 - AI system**<br>`:00572` | a) Briefly describe the AI system, specifying its version and type of underlying algorithm used. Describe, or provide a direct reference to, the characteristics of the patient population on which the algorithm was trained and its performance in preclinical development/validation studies. | model architecture, published results identifier, version | I R Ex |
| **DECIDE-AI item 5 - Implementation**<br>`:00573` | a) Describe the settings in which the AI system was evaluated. | clinical workflow phase | Un Us |
| **DECIDE-AI item 6 - Safety and errors**<br>`:00575` | a) Provide a description of how significant errors/malfunctions were defined and identified. | known bias or failure mode | Ro Fa |
| **DECIDE-AI item 7 - Human factors**<br>`:00576` | Describe the human factors tools, methods or frameworks used, the use cases considered, and the users involved. | — | Ex Us |
| **DECIDE-AI item 8 - Ethics**<br>`:00578` | Describe whether specific methodologies were utilised to fulfil an ethics-related goal (such as algorithmic fairness) and their rationale. | ethical consideration | Fa |
| **DECIDE-AI item 9 - Participants**<br>`:00580` | a) Describe the baseline characteristics of the patients included in the study, and report on input data missingness. | missing information, population | R Un Fa |
| **DECIDE-AI item I - Abstract**<br>`:00567` | Provide a structured summary of the study. Consider including: intended use of the AI system, type of underlying algorithm, study setting, number of patients and users included, primary and secondary outcomes, key safety endpoints, human factors evaluated, main results, conclusions. | summary | F Us |
| **DECIDE-AI item II - Objectives**<br>`:00569` | State the study objectives. | motivation | F |
| **DECIDE-AI item III - Research governance**<br>`:00570` | Provide a reference to any study protocol, study registration number, and ethics approval. | clinical trial number, ethical review, reference | — |
| **DECIDE-AI item IV - Outcomes**<br>`:00574` | Specify the primary and secondary outcomes measured. | — | Ro |
| **DECIDE-AI item IX - Strengths and limitations**<br>`:00590` | Discuss the strengths and limitations of the study. | limitations | Un Ex |
| **DECIDE-AI item V - Analysis**<br>`:00577` | Describe the statistical methods by which the primary and secondary outcomes were analysed, as well as any prespecified additional analyses, including subgroup analyses and their rationale. | — | Ro |
| **DECIDE-AI item VI - Patient involvement**<br>`:00579` | State how patients were involved in any aspect of: the development of the research question, the study design, and the conduct of the study. | — | Us Fa |
| **DECIDE-AI item VII - Main results**<br>`:00582` | Report on the prespecified outcomes, including outcomes for any comparison group if applicable. | model performance | Ex Ro |
| **DECIDE-AI item VIII - Subgroups analysis**<br>`:00583` | Report on the differences in the main outcomes according to the prespecified subgroups. | — | Ex Fa |
| **DECIDE-AI item X - Conflicts of interest**<br>`:00592` | Disclose any relevant conflicts of interest, including the source of funding for the study, the role of funders, any other roles played by commercial companies, and personal conflicts of interest for each author. | funding | — |
| **MI-CLAIM item 01**<br>`:00593` | The clinical problem in which the model will be employed is clearly detailed in the paper. | indication for use, model use | R Ex Us |
| **MI-CLAIM item 02**<br>`:00594` | The research question is clearly stated. | motivation | F |
| **MI-CLAIM item 03**<br>`:00595` | The characteristics of the cohorts (training and test sets) are detailed in the text. | population, sampling | R Fa |
| **MI-CLAIM item 04**<br>`:00596` | The cohorts (training and test sets) are shown to be representative of real-world clinical settings. | known data-characterization gap, population | Un Ro Fa |
| **MI-CLAIM item 05**<br>`:00597` | The state-of-the-art solution used as a baseline for comparison has been identified and detailed. | — | R |
| **MI-CLAIM item 06**<br>`:00598` | The origin of the data is described and the original format is detailed in the paper. | external data | F A R |
| **MI-CLAIM item 07**<br>`:00599` | Transformations of the data before it is applied to the proposed model are described. | — | I R |
| **MI-CLAIM item 08**<br>`:00600` | The independence between training and test sets has been proven in the paper. | partitioning scheme, relationships between instances | Ro |
| **MI-CLAIM item 09**<br>`:00601` | Details on the models that were evaluated and the code developed to select the best model are provided. | model architecture, reproducibility | F A R Ex |
| **MI-CLAIM item 10**<br>`:00602` | Is the input data type structured or unstructured? | model input | I |
| **MI-CLAIM item 11**<br>`:00603` | The primary metric selected to evaluate algorithm performance (e.g., AUC, F-score, etc.), including the justification for selection, has been clearly stated. | model performance | Ex Ro |
| **MI-CLAIM item 12**<br>`:00604` | The primary metric selected to evaluate the clinical utility of the model (e.g., PPV, NNT, etc.), including the justification for selection, has been clearly stated. | clinical benefit | Ex Us |
| **MI-CLAIM item 13**<br>`:00605` | The performance comparison between baseline and proposed model is presented with the appropriate statistical significance. | — | Ro |
| **MI-CLAIM item 14**<br>`:00606` | Examination technique 1. Common examination approaches based on study type: for studies involving exclusively structured data, coefficients and sensitivity analysis are often appropriate; for studies involving unstructured data in the domains of image analysis or natural language processing, saliency maps (or equivalents) and sensitivity analyses are often appropriate. | — | Ex Ro |
| **MI-CLAIM item 15**<br>`:00607` | Examination technique 2. Common examination approaches based on study type: for studies involving exclusively structured data, coefficients and sensitivity analysis are often appropriate; for studies involving unstructured data in the domains of image analysis or natural language processing, saliency maps (or equivalents) and sensitivity analyses are often appropriate. | — | Ex Ro |
| **MI-CLAIM item 16**<br>`:00608` | A discussion of the relevance of the examination results with respect to model/algorithm performance is presented. | — | Ex Us |
| **MI-CLAIM item 17**<br>`:00609` | A discussion of the feasibility and significance of model interpretability at the case level if examination methods are uninterpretable is presented. | — | Ex Us |
| **MI-CLAIM item 18**<br>`:00610` | A discussion of the reliability and robustness of the model as the underlying data distribution shifts is included. | known bias or failure mode, limitations | Ex Ro |
| **MI-CLAIM item 19**<br>`:00611` | Reproducibility: choose appropriate tier of transparency. | license, model availability, reproducibility | R Ex Us |
| **MINIMAR item 1.1 - Population**<br>`:00542` | Population from which study sample was drawn. | known data-characterization gap, population | R Un Fa |
| **MINIMAR item 1.2 - Study setting**<br>`:00543` | The setting in which the study was conducted (eg, academic medical left, community healthcare system, rural healthcare clinic). | population | Un |
| **MINIMAR item 1.3 - Data source**<br>`:00544` | The source from which data were collected. | external data, sampling | F A R |
| **MINIMAR item 1.4 - Cohort selection**<br>`:00545` | Exclusion/inclusion criteria. | sampling | R Ro Fa |
| **MINIMAR item 2.1 - Age**<br>`:00547` | Age of patients included in the study. | population | Un Fa |
| **MINIMAR item 2.2 - Sex**<br>`:00548` | Sex breakdown of study cohort. | population | Un Fa |
| **MINIMAR item 2.3 - Race**<br>`:00549` | Race characteristics of patients included in the study. | population | Un Fa |
| **MINIMAR item 2.4 - Ethnicity**<br>`:00550` | Ethnicity breakdown of patients included in the study. | population | Un Fa |
| **MINIMAR item 2.5 - Socioeconomic status**<br>`:00551` | A measure or proxy measure of the socioeconomic status of patients included in the study. | population | Un Fa |
| **MINIMAR item 3.1 - Model output**<br>`:00553` | The computed result of the model. | model output | Ex Us |
| **MINIMAR item 3.2 - Target user**<br>`:00554` | The indented user of the model output (eg, clinician, hospital management team, insurance company). | model user | Ex Us |
| **MINIMAR item 3.3 - Data splitting**<br>`:00555` | How data were split for training, testing, and validation. | partitioning scheme | R Ro |
| **MINIMAR item 3.4 - Gold standard**<br>`:00556` | Labeled data used to train and test the model. | annotation level | R Ex |
| **MINIMAR item 3.5 - Model task**<br>`:00557` | Classification or prediction. | model output | Ex |
| **MINIMAR item 3.6 - Model architecture**<br>`:00558` | Algorithm type (eg, machine learning, deep learning, etc.). | model architecture | I Ex |
| **MINIMAR item 3.7 - Features**<br>`:00559` | List of variables used in the model and how they were used in the model in terms of categories or transformation. | model input | I R Ex |
| **MINIMAR item 3.8 - Missingness**<br>`:00560` | How missingness was addressed: reported, imputed, or corrected. | missing information | Ro |
| **MINIMAR item 4.1 - Optimization**<br>`:00562` | Model or parameter tuning applied. | — | Ex Ro |
| **MINIMAR item 4.2 - Internal model validation**<br>`:00563` | Study internal validation. | partitioning scheme | Ex Ro |
| **MINIMAR item 4.3 - External model validation**<br>`:00564` | External validation using data from another setting. | partitioning scheme | Un Ro |
| **MINIMAR item 4.4 - Transparency**<br>`:00565` | How code and data are shared with the community.. | license, link, model availability, reproducibility | F A R |
| **PROBAST+AI model development item 1.1**<br>`:00614` | Were appropriate data sources used? | external data, sampling | F A R |
| **PROBAST+AI model development item 1.2**<br>`:00615` | Was an appropriate study design used? | sampling strategy | Ro |
| **PROBAST+AI model development item 1.3**<br>`:00616` | Did the in- and exclusions of study participants result in a representative dataset? | known data-characterization gap, sampling | Un Ro Fa |
| **PROBAST+AI model development item 2.1**<br>`:00617` | Were predictors defined and assessed in a similar way for all participants? | model input | I R Ro |
| **PROBAST+AI model development item 2.2**<br>`:00618` | Was any pre-processing of predictors similar for all participants? | noise | I Ro |
| **PROBAST+AI model development item 2.3**<br>`:00619` | Were predictor assessments made without knowledge of outcome data? | — | Ro |
| **PROBAST+AI model development item 2.4**<br>`:00620` | Were the predictors included in the model available at the time the model was intended to be used? | model input | Us Ro |
| **PROBAST+AI model development item 3.1**<br>`:00621` | Were outcomes defined and assessed appropriately? | annotation level | Ex Ro |
| **PROBAST+AI model development item 3.2**<br>`:00622` | Were outcomes defined and assessed in a similar way for all participants? | annotation level | Ro Fa |
| **PROBAST+AI model development item 3.3**<br>`:00623` | Were outcome assessments made without use or knowledge of predictor data? | — | Ro |
| **PROBAST+AI model development item 3.4**<br>`:00624` | Was the time interval between predictor assessment and outcome assessment appropriate? | — | Ro |
| **PROBAST+AI model development item 4.1**<br>`:00625` | Was there evidence that the sample size was reasonable? | sampling | Ro |
| **PROBAST+AI model development item 4.2**<br>`:00626` | Were continuous and categorical predictors handled appropriately? | model input | Ro |
| **PROBAST+AI model development item 4.3**<br>`:00627` | Were participants with missing or censored data handled appropriately in the analysis? | missing information | Ro |
| **PROBAST+AI model development item 4.4**<br>`:00628` | If methods to address class imbalance were used, was the model or the model predictions recalibrated?* | — | Ro Fa |
| **PROBAST+AI model development item 4.5**<br>`:00635` | Were methods used to address potential model overfitting? | partitioning scheme | Ex Ro |
| **PROBAST+AI model evaluation item 1.1**<br>`:00636` | Were appropriate data sources used? | external data, sampling | F A R |
| **PROBAST+AI model evaluation item 1.2**<br>`:00637` | Was an appropriate study design used? | sampling strategy | Ro |
| **PROBAST+AI model evaluation item 1.3**<br>`:00638` | Did the in- and exclusions of study participants result in a representative dataset? | known data-characterization gap, sampling | Un Ro Fa |
| **PROBAST+AI model evaluation item 2.1**<br>`:00639` | Were predictors defined and assessed in a similar way for all participants? | model input | I R Ro |
| **PROBAST+AI model evaluation item 2.2**<br>`:00640` | Was any pre-processing of predictors similar for all participants? | noise | I Ro |
| **PROBAST+AI model evaluation item 2.3**<br>`:00641` | Were predictor assessments made without knowledge of outcome data? | — | Ro |
| **PROBAST+AI model evaluation item 2.4**<br>`:00642` | Were the predictors included in the model available at the time the model was intended to be used? | model input | Us Ro |
| **PROBAST+AI model evaluation item 3.1**<br>`:00643` | Were outcomes defined and assessed appropriately? | annotation level | Ex Ro |
| **PROBAST+AI model evaluation item 3.2**<br>`:00644` | Were outcomes defined and assessed in a similar way for all participants? | annotation level | Ro Fa |
| **PROBAST+AI model evaluation item 3.3**<br>`:00645` | Were outcome assessments made without use or knowledge of predictor data? | — | Ro |
| **PROBAST+AI model evaluation item 3.4**<br>`:00646` | Was the time interval between predictor assessment and outcome assessment appropriate? | — | Ro |
| **PROBAST+AI model evaluation item 4.1**<br>`:00647` | Was model evaluation based on only apparent performance avoided? | partitioning scheme | Ex Ro |
| **PROBAST+AI model evaluation item 4.2**<br>`:00648` | Was there evidence that the sample size was reasonable? | sampling | Ro |
| **PROBAST+AI model evaluation item 4.3**<br>`:00649` | Were participants with missing or censored data handled appropriately in the analysis? | missing information | Ro |
| **PROBAST+AI model evaluation item 4.4**<br>`:00650` | If methods to address class imbalance were used, was the evaluation done in a dataset without imbalance correction?* | — | Ro Fa |
| **PROBAST+AI model evaluation item 4.5**<br>`:00651` | If data splitting was done to create training and test datasets, was there evidence that data leakage was avoided?* | partitioning scheme, relationships between instances | Ro |
| **PROBAST+AI model evaluation item 4.6**<br>`:00652` | If resampling methods were used to evaluate model performance, were all model development steps replicated in the resampling process?* | partitioning scheme | R Ro |
| **PROBAST+AI model evaluation item 4.7**<br>`:00653` | Was the predictive performance of the model evaluated appropriately, e.g., calibration, discrimination, and net benefit? | model performance | Ex Ro |
| **REFINE item 1.1**<br>`:00497` | Model name, vendor/developer, version/identifier, release date, and training/knowledge cutoff date. | date, name, version | F |
| **REFINE item 1.2**<br>`:00498` | Model architecture and key characteristics. | model architecture | I Ex |
| **REFINE item 1.3**<br>`:00499` | Model pretraining, post-training, and inference-time adaptation strategy. | model architecture | Ex Ro |
| **REFINE item 1.4**<br>`:00500` | Modality support details (input and output) and limitations. | limitations, model input, model output | I Ex Us |
| **REFINE item 1.5**<br>`:00501` | Language capabilities. | — | I Un Us |
| **REFINE item 1.6**<br>`:00502` | Model access. | link, model availability | A |
| **REFINE item 1.7**<br>`:00503` | Sharing of code, data, and model artifacts. | license, link, model availability | F A R |
| **REFINE item 1.8**<br>`:00504` | Computational requirements. | required processors, sustainability, time to evaluate single input, time to train model | Ro |
| **REFINE item 2.1**<br>`:00505` | Prompt engineering protocol with versioning. | instructions for use | Ro |
| **REFINE item 2.2**<br>`:00506` | Prompting strategy, format, and length. | instructions for use | I Ex |
| **REFINE item 2.3**<br>`:00507` | Prompt modality, language, technical input specification, and full content. | model input | I R |
| **REFINE item 2.4**<br>`:00508` | Integration of relevant patient clinical context. | — | Ex Us |
| **REFINE item 2.5**<br>`:00509` | Interaction style and session memory policy. | instructions for use | Ex Us |
| **REFINE item 2.6**<br>`:00510` | Output handling. | model output | Ex Us |
| **REFINE item 3.1**<br>`:00511` | Generation parameters. | decision threshold, reproducibility | Ro |
| **REFINE item 3.2**<br>`:00512` | Prompt operator characteristics and number of prompt attempts. | — | Ro |
| **REFINE item 3.3**<br>`:00513` | Output selection. | — | Ex |
| **REFINE item 4.1**<br>`:00514` | Dataset name, version, access type, source citation, license, and compliance statement. | license, published results identifier | F A R |
| **REFINE item 4.10**<br>`:00523` | Separation of training, fine-tuning, internal testing, and external testing datasets. | partitioning scheme, relationships between instances | R Ro |
| **REFINE item 4.2**<br>`:00515` | Dataset origin. | external data, sampling | F A R |
| **REFINE item 4.3**<br>`:00516` | Ethics and consent statements. | confidentiality, ethical consideration, ethical review, risk of re-identification, sensitive data | — |
| **REFINE item 4.4**<br>`:00517` | Prior dataset usage and publication date. | external data, publication date | F |
| **REFINE item 4.5**<br>`:00518` | Dataset composition and data synthesis details. | sampling | I R |
| **REFINE item 4.6**<br>`:00519` | Sample characteristics and representational bias analysis. | known data-characterization gap, population | Un Ro Fa |
| **REFINE item 4.7**<br>`:00520` | Reference standard and annotator qualifications. | annotation level | R Ex |
| **REFINE item 4.8**<br>`:00521` | Preprocessing and data pairing/registration. | noise, relationships between instances | I R |
| **REFINE item 4.9**<br>`:00522` | Missing data extent, mechanism, and handling. | missing information | Ro |
| **REFINE item 5.1**<br>`:00524` | Output evaluation method and performance metrics. | model performance | Ex Ro |
| **REFINE item 5.10**<br>`:00533` | Comparison with clinically relevant benchmarks. | — | Ex Ro |
| **REFINE item 5.2**<br>`:00525` | Human evaluator characteristics and reliability analysis. | — | Ex Ro |
| **REFINE item 5.3**<br>`:00526` | Statistical analysis of evaluation results. | model performance | Ex Ro |
| **REFINE item 5.4**<br>`:00527` | Subgroup performance and output bias assessment. | known bias or failure mode | Ex Ro Fa |
| **REFINE item 5.5**<br>`:00528` | Failure analysis and error metrics. | known bias or failure mode | Ex Ro Fa |
| **REFINE item 5.6**<br>`:00529` | Output stochasticity and reproducibility constraints. | reproducibility | R Ex Ro |
| **REFINE item 5.7**<br>`:00530` | Performance effects of different prompt strategies and revisions. | — | Ex Ro |
| **REFINE item 5.8**<br>`:00531` | Model version comparisons and temporal performance variation. | update date, version | Ro |
| **REFINE item 5.9**<br>`:00532` | Methods for explainability and interpretability of model outputs. | — | Ex Ro |
| **REFINE item 6.1**<br>`:00534` | Declared intended application and scope of use. | indication for use, model use, recommendation | Ex Us |
| **REFINE item 6.2**<br>`:00535` | Clinical workflow integration. | clinical workflow phase, degree of automation, instructions for use | Us |
| **REFINE item 6.3**<br>`:00536` | Measured clinical utility or added value. | clinical benefit | Ex Us |
| **REFINE item 6.4**<br>`:00537` | Model limitations, explicit clinical non-use cases, and potential misuse considerations. | excluded model use, limitations, out-of-scope model use | Un Ex |
| **REFINE item 6.5**<br>`:00538` | Safety testing and monitoring protocols. | known bias or failure mode | Ro Fa |
| **REFINE item 6.6**<br>`:00539` | Data security and privacy safeguards. | confidentiality, risk of re-identification, sensitive data | — |
| **REFINE item 6.7**<br>`:00540` | Governance, auditability, and oversight. | ethical consideration, regulatory information | Ex |
| **SPIRIT-AI item 01**<br>`:00345` | Descriptive title identifying study design, population, interventions, and trial acronym. Indicate intervention involves AI/ML and specify model type. Specify intended use of AI intervention. | model architecture, model use | F |
| **SPIRIT-AI item 02a**<br>`:00370` | Trial identifier and registry name. | clinical trial number | F |
| **SPIRIT-AI item 02b**<br>`:00371` | WHO Trial Registration Dataset items. | — | F |
| **SPIRIT-AI item 03**<br>`:00372` | Date and version identifier. | date, version | F |
| **SPIRIT-AI item 04**<br>`:00373` | Sources and types of support. | funding | — |
| **SPIRIT-AI item 05a**<br>`:00374` | Names, affiliations, roles of contributors. | contact information | — |
| **SPIRIT-AI item 05b**<br>`:00375` | Trial sponsor contact info. | contact information | — |
| **SPIRIT-AI item 05c**<br>`:00376` | Role of sponsor and funders. | funding | — |
| **SPIRIT-AI item 06a**<br>`:00378` | Research question and justification. Explain intended AI use in clinical pathway. Describe pre-existing evidence. | model use, motivation | R Us |
| **SPIRIT-AI item 06b**<br>`:00379` | Explanation for comparators. | — | Ex |
| **SPIRIT-AI item 07**<br>`:00380` | Objectives or hypotheses. | motivation | — |
| **SPIRIT-AI item 08**<br>`:00381` | Trial design description. | — | Ro |
| **SPIRIT-AI item 09**<br>`:00382` | Study settings and locations. Integration requirements for AI. | clinical workflow phase | Un Us |
| **SPIRIT-AI item 10**<br>`:00383` | Inclusion/exclusion criteria. Participant-level criteria. Input data criteria. | model input, sampling | R Ro Fa |
| **SPIRIT-AI item 11a**<br>`:00384` | Intervention details. AI algorithm version. Input data acquisition. Handling poor-quality data. Human-AI interaction. Specify AI output. Use of AI output in decisions. | degree of automation, instructions for use, model input, model output, model user, version | I R Ex |
| **SPIRIT-AI item 11b**<br>`:00385` | Criteria for discontinuation. | — | Ro |
| **SPIRIT-AI item 11c**<br>`:00386` | Adherence strategies. | — | Ro |
| **SPIRIT-AI item 11d**<br>`:00387` | Concomitant care. | — | Us |
| **SPIRIT-AI item 12**<br>`:00388` | Primary and secondary outcomes. | — | Ro |
| **SPIRIT-AI item 13**<br>`:00389` | Schedule of enrollment and visits. | — | Ro |
| **SPIRIT-AI item 14**<br>`:00390` | Sample size determination. | — | Ro |
| **SPIRIT-AI item 15**<br>`:00391` | Recruitment strategies. | — | Un Fa |
| **SPIRIT-AI item 16a**<br>`:00392` | Allocation sequence generation. | — | Ro |
| **SPIRIT-AI item 16b**<br>`:00393` | Concealment mechanism. | — | Ro |
| **SPIRIT-AI item 17a**<br>`:00395` | Blinding details. | — | Ro |
| **SPIRIT-AI item 17b**<br>`:00396` | Unblinding conditions. | — | Ro |
| **SPIRIT-AI item 18a**<br>`:00397` | Outcome and baseline data collection. | — | R Ro |
| **SPIRIT-AI item 18b**<br>`:00398` | Retention and follow-up. | — | Ro |
| **SPIRIT-AI item 19**<br>`:00399` | Data entry and storage. | confidentiality | A I |
| **SPIRIT-AI item 20a**<br>`:00400` | Analysis of outcomes. | model performance | Ex Ro |
| **SPIRIT-AI item 20b**<br>`:00401` | Additional analyses. | — | Ex Fa |
| **SPIRIT-AI item 20c**<br>`:00402` | Missing data handling. | missing information | Ro |
| **SPIRIT-AI item 21b**<br>`:00404` | Interim analyses. | — | Ro |
| **SPIRIT-AI item 22**<br>`:00405` | Adverse events handling. AI performance errors analysis. | known bias or failure mode | Ex Ro Fa |
| **SPIRIT-AI item 24**<br>`:00407` | IRB approval plans. | ethical review | — |
| **SPIRIT-AI item 25**<br>`:00408` | Communication of changes. | — | Us |
| **SPIRIT-AI item 26a**<br>`:00409` | Informed consent process. | ethical review | — |
| **SPIRIT-AI item 27**<br>`:00411` | Participant data protection. | confidentiality, risk of re-identification, sensitive data | — |
| **SPIRIT-AI item 29**<br>`:00413` | Dataset access. Access to AI code. | license, link, model availability | F A R |
| **SPIRIT-AI item 30**<br>`:00414` | Post-trial care. | — | Us |
| **SPIRIT-AI item 31a**<br>`:00415` | Communication of results. | — | F |
| **SPIRIT-AI item 31c**<br>`:00417` | Public access to protocol/data. | — | F A |
| **SPIRIT-AI item 33**<br>`:00419` | Specimen handling. | — | R |
| **STARD-AI item 01**<br>`:00279` | Identification as a study reporting AI-centered diagnostic accuracy and reporting at least one measure of accuracy within title or abstract. | model performance | F |
| **STARD-AI item 02**<br>`:00280` | Structured summary of study design, methods, results and conclusions (for specific guidance, please see STARD for Abstracts). | summary | F |
| **STARD-AI item 03**<br>`:00281` | Scientific and clinical background, including the intended use of the index test, whether it is novel or an established index test, and its integration into an existing or new workflow, if applicable | clinical workflow phase, indication for use, model use, motivation | R Us |
| **STARD-AI item 04**<br>`:00282` | Study objectives and hypotheses. | motivation | F |
| **STARD-AI item 05**<br>`:00283` | Whether data collection was planned before the index test and reference standard were performed (prospective study) or after (retrospective study). | — | Ro |
| **STARD-AI item 06**<br>`:00284` | Formal approval from an ethics committee. If not required, justify why. | ethical review | — |
| **STARD-AI item 07**<br>`:00285` | Eligibility criteria: listing separate inclusion and exclusion criteria in the order that they are applied at both participant level and data level. | sampling | R Ro Fa |
| **STARD-AI item 08**<br>`:00286` | On what basis potentially eligible participants were identified (such as symptoms, results from previous tests, inclusion in registry). | sampling | R Un |
| **STARD-AI item 09**<br>`:00287` | Where and when potentially eligible participants were identified (setting, location, and dates). | sampling | R Un |
| **STARD-AI item 10**<br>`:00288` | Whether participants formed a consecutive, random, or convenience series. | sampling strategy | R Ro Fa |
| **STARD-AI item 11**<br>`:00289` | Source of the data and whether it has been routinely collected, specifically collected for the purpose of the study or acquired from an open-source repository. | external data, sampling | F A R |
| **STARD-AI item 12**<br>`:00290` | Who undertook the annotations for the dataset (including experience levels and background) and how (within the same clinical context or in a post-hoc fashion), if applicable. | annotation level | R Ex |
| **STARD-AI item 13**<br>`:00291` | Devices (manufacturer, model) that were used to capture data; software (with version number) used to engineer the index test, highlighting the intended use. | — | I Ro |
| **STARD-AI item 14**<br>`:00292` | Data acquisition protocols (e.g. contrast protocol or reconstruction method for medical images) and details of data pre-processing in sufficient detail to allow replication. | — | I R Ro |
| **STARD-AI item 15a**<br>`:00293` | Index test, in sufficient detail to allow replication. | model input | I R Ex |
| **STARD-AI item 15b**<br>`:00294` | How the index test was developed, including any training, validation, testing and external evaluation, detailing sample sizes, when applicable. | partitioning scheme | Ro |
| **STARD-AI item 15c**<br>`:00295` | Definition of and rationale for test positivity cut-offs or result categories of the index test, distinguishing pre-specified from exploratory. | decision threshold | Ex Ro |
| **STARD-AI item 15d**<br>`:00296` | The specified end user of the index test and the level of expertise required of users. | model user | Ex Us |
| **STARD-AI item 16a**<br>`:00297` | Reference standard, in sufficient detail to allow replication. | annotation level | I R |
| **STARD-AI item 16b**<br>`:00298` | Rationale for choosing the reference standard (if alternatives exist). | — | Ex |
| **STARD-AI item 16c**<br>`:00299` | Definition of and rationale for test positivity cut-offs or result categories of the reference standard, distinguishing pre-specified from exploratory. | — | Ex |
| **STARD-AI item 17a**<br>`:00300` | Whether clinical information and reference standard results were available to the performers or readers of the index test. | — | Ro |
| **STARD-AI item 17b**<br>`:00301` | Whether clinical information and index test results were available to the assessors of the reference standard. | — | Ro |
| **STARD-AI item 18**<br>`:00302` | Methods for estimating or comparing measures of diagnostic accuracy. | model performance | R Ex |
| **STARD-AI item 19**<br>`:00303` | How indeterminate index test or reference standard results were handled. | missing information | Ro |
| **STARD-AI item 20**<br>`:00304` | How missing data on the index test and reference standard were handled. | missing information | Ro |
| **STARD-AI item 21**<br>`:00305` | Any analyses of variability in diagnostic accuracy, distinguishing pre-specified from exploratory. | — | Ex Ro |
| **STARD-AI item 22**<br>`:00306` | Intended sample size and how it was determined. | sampling | Ro |
| **STARD-AI item 23**<br>`:00307` | Details of any performance error analysis, and algorithmic bias and fairness assessments if undertaken. | known bias or failure mode | Ex Ro Fa |
| **STARD-AI item 25**<br>`:00309` | Baseline demographic, clinical and technical characteristics of training, validation and test set, if applicable. | partitioning scheme, population | R Un Ro Fa |
| **STARD-AI item 26a**<br>`:00310` | Distribution of severity of disease in those with the target condition. | — | R Un Fa |
| **STARD-AI item 26b**<br>`:00311` | Distribution of alternative diagnoses in those without the target condition. | — | R Un Fa |
| **STARD-AI item 27**<br>`:00312` | Time interval and any clinical interventions between index test and reference standard. | — | Ro |
| **STARD-AI item 28**<br>`:00313` | Whether the datasets represent the distribution of the target condition that one would expect from the intended use population. | known data-characterization gap, population | Un Ro Fa |
| **STARD-AI item 29**<br>`:00314` | For external evaluation on an independent dataset, an assessment of how this differs from the training, validation and test sets. | known data-characterization gap | Un Ro |
| **STARD-AI item 30**<br>`:00315` | Cross tabulation of the index test results (or their distribution) by the results of the reference standard. | — | Ex |
| **STARD-AI item 31**<br>`:00316` | Estimates of diagnostic accuracy and their precision (such as 95% confidence intervals). | model performance | Ex Ro |
| **STARD-AI item 32**<br>`:00317` | Any adverse events from performing the index test or the reference standard. | — | Ro |
| **STARD-AI item 33**<br>`:00318` | Study limitations, including sources of potential bias, statistical uncertainty, and generalisability. | limitations, noise | Un Ex Ro |
| **STARD-AI item 34**<br>`:00319` | Implications for practice, including the intended use and clinical role of the index test. | clinical benefit, model use, recommendation | Ex Us |
| **STARD-AI item 35**<br>`:00320` | Ethical considerations and adherence to ethical standards associated with the use of the index test and issues of fairness. | ethical consideration | Fa |
| **STARD-AI item 36**<br>`:00321` | Registration number and name of registry. | clinical trial number | F |
| **STARD-AI item 37**<br>`:00322` | Where the full study protocol can be accessed. | reference | F A |
| **STARD-AI item 39**<br>`:00324` | Commercial interests, if applicable. | funding | — |
| **STARD-AI item 40a**<br>`:00325` | Availability of datasets and code; detailing any restrictions on their reuse and repurposing. | — | F A R |
| **STARD-AI item 40b**<br>`:00326` | Whether outputs are stored, auditable and available for evaluation, if necessary. | — | A Ex |
| **TRAM-AI item A1**<br>`:00180` | Dataset is hosted on a recognized, third-party repository (e.g., Zenodo, TCIA, PhysioNet), not personal websites. | link | F A |
| **TRAM-AI item A2**<br>`:00181` | Dataset is assigned a DOI or stable accession number. | link | F A |
| **TRAM-AI item A3**<br>`:00182` | Repository supports explicit versioning; specific version cited in manuscript. | version | F A R |
| **TRAM-AI item B1**<br>`:00184` | Non-proprietary formats (DICOM, nifti). Preprocessing documented or raw data stated. | image file format, pre-processing, resolution | I R |
| **TRAM-AI item B2**<br>`:00185` | Cryptographic hashes (MD5/SHA-256) provided. | — | A I Ro |
| **TRAM-AI item B3**<br>`:00186` | Folder hierarchy documented. | — | I R |
| **TRAM-AI item B4**<br>`:00187` | Archives confirmed to extract on different OS. | — | I Ro |
| **TRAM-AI item C1**<br>`:00189` | Machine-readable file links Image identifiers to Subject identifiers. | — | I R |
| **TRAM-AI item C2**<br>`:00190` | Training, validation, and test split IDs provided as static lists. | — | R Ro |
| **TRAM-AI item C3**<br>`:00192` | Labels and reference standard source defined. | — | R Fa |
| **TRAM-AI item C4**<br>`:00193` | Excluded IDs and reasons provided. | — | R Fa |
| **TRAM-AI item D1**<br>`:00195` | Standard license (CC-BY, CC0, ODbL, ODC-BY) applied. | license | A R |
| **TRAM-AI item D2**<br>`:00196` | PHI removal from headers and pixel data confirmed. | confidentiality, risk of re-identification, sensitive data | — |
| **TRAM-AI item D3**<br>`:00197` | Contact for error reporting; deprecation process established. | contact information | A R Us |
| **TRIPOD+AI item 01**<br>`:00420` | Identify the study as developing or evaluating the performance of a multivariable prediction model, the target population, and the outcome to be predicted. | — | F |
| **TRIPOD+AI item 02**<br>`:00421` | See TRIPOD+AI for Abstracts checklist. | summary | F |
| **TRIPOD+AI item 03a**<br>`:00422` | Explain the healthcare context (including whether diagnostic or prognostic) and rationale for developing or evaluating the prediction model, including references to existing models. | indication for use, motivation | R Ex Us |
| **TRIPOD+AI item 03b**<br>`:00423` | Describe the target population and the intended purpose of the prediction model in the context of the care pathway, including its intended users (e.g., healthcare professionals, patients, public). | clinical workflow phase, model use | R Us |
| **TRIPOD+AI item 03c**<br>`:00424` | Describe any known health inequalities between sociodemographic groups. | known data-characterization gap | Un Fa |
| **TRIPOD+AI item 04**<br>`:00425` | Specify the study objectives, including whether the study describes the development or validation of a prediction model (or both). | motivation | F |
| **TRIPOD+AI item 05a**<br>`:00426` | Describe the sources of data separately for the development and evaluation datasets (e.g., randomised trial, cohort, routine care or registry data), the rationale for using these data, and representativeness of the data. | sampling, sampling strategy | F A R |
| **TRIPOD+AI item 06a**<br>`:00428` | Specify key elements of the study setting (e.g., primary care, secondary care, general population) including the number and location of centres. | — | Un |
| **TRIPOD+AI item 06b**<br>`:00429` | Describe the eligibility criteria for study participants. | sampling | R Ro Fa |
| **TRIPOD+AI item 06c**<br>`:00430` | Give details of any treatments received, and how they were handled during model development or evaluation, if relevant. | — | R |
| **TRIPOD+AI item 07**<br>`:00431` | Describe any data pre-processing and quality checking, including whether this was similar across relevant sociodemographic groups. | noise | I R Ro |
| **TRIPOD+AI item 08a**<br>`:00432` | Clearly define the outcome that is being predicted and the time horizon, including how and when assessed, the rationale for choosing this outcome, and whether the method of outcome assessment is consistent across sociodemographic groups. | annotation level | Ex Ro |
| **TRIPOD+AI item 08b**<br>`:00433` | If outcome assessment requires subjective interpretation, describe the qualifications and demographic characteristics of the outcome assessors. | — | R Ex |
| **TRIPOD+AI item 08c**<br>`:00434` | Report any actions to blind assessment of the outcome to be predicted. | — | Ro |
| **TRIPOD+AI item 09a**<br>`:00435` | Describe the choice of initial predictors (e.g., literature, previous models, all available predictors) and any pre-selection of predictors before model building. | — | R Ex |
| **TRIPOD+AI item 09b**<br>`:00436` | Clearly define all predictors, including how and when they were measured (and any actions to blind assessment of predictors for the outcome and other predictors). | model input | I R |
| **TRIPOD+AI item 09c**<br>`:00437` | If predictor measurement requires subjective interpretation, describe the qualifications and demographic characteristics of the predictor assessors. | — | R |
| **TRIPOD+AI item 10**<br>`:00438` | Explain how the study size was arrived at (separately for development and evaluation), and justify that the study size was sufficient to answer the research question. Include details of any sample size calculation. | sampling | Ro |
| **TRIPOD+AI item 11**<br>`:00439` | Describe how missing data were handled. Provide reasons for omitting any data. | missing information | Ro |
| **TRIPOD+AI item 12a**<br>`:00440` | Describe how the data were used (e.g., for development and evaluation of model performance) in the analysis, including whether the data were partitioned, considering any sample size requirements. | partitioning scheme, relationships between instances | Ro |
| **TRIPOD+AI item 12b**<br>`:00441` | Depending on the type of model, describe how predictors were handled in the analyses (functional form, rescaling, transformation, or any standardisation). | — | I Ex |
| **TRIPOD+AI item 12c**<br>`:00442` | Specify the type of model, rationale2, all model-building steps, including any hyperparameter tuning, and method for internal validation. | model architecture, partitioning scheme | I Ex Ro |
| **TRIPOD+AI item 12d**<br>`:00443` | Describe if and how any heterogeneity in estimates of model parameter values and model performance was handled and quantified across clusters (e.g., hospitals, countries). See TRIPOD-Cluster for additional considerations. | relationships between instances | Ex Ro |
| **TRIPOD+AI item 12e**<br>`:00444` | Specify all measures and plots used (and their rationale) to evaluate model performance (e.g., discrimination, calibration, clinical utility) and, if relevant, to compare multiple models. | model performance | Ex Ro |
| **TRIPOD+AI item 12f**<br>`:00445` | Describe any model updating (e.g., recalibration) arising from the model evaluation, either overall or for particular sociodemographic groups or settings. | — | Ex |
| **TRIPOD+AI item 12g**<br>`:00446` | For model evaluation, describe how the model predictions were calculated (e.g., formula, code, object, application programming interface). | — | I Ex |
| **TRIPOD+AI item 13**<br>`:00447` | If class imbalance methods were used, state why and how this was done, and any subsequent methods to recalibrate the model or the model predictions. | — | Ro Fa |
| **TRIPOD+AI item 14**<br>`:00448` | Describe any approaches that were used to address model fairness and their rationale. | ethical consideration | Ex Ro Fa |
| **TRIPOD+AI item 15**<br>`:00449` | Specify the output of the prediction model (e.g., probabilities, classification). Provide details and rationale for any classification and how the thresholds were identified. | decision threshold, model output | I R Ex |
| **TRIPOD+AI item 16**<br>`:00450` | Identify any differences between the development and evaluation data in healthcare setting, eligibility criteria, outcome, and predictors. | known data-characterization gap | Un Ro |
| **TRIPOD+AI item 17**<br>`:00451` | Name the institutional research board or ethics committee that approved the study and describe the participant-informed consent or the ethics committee waiver of informed consent. | ethical review | — |
| **TRIPOD+AI item 18a**<br>`:00462` | Give the source of funding and the role of the funders for the present study. | funding | — |
| **TRIPOD+AI item 18b**<br>`:00452` | Declare any conflicts of interest and financial disclosures for all authors. | funding | — |
| **TRIPOD+AI item 18c**<br>`:00453` | Indicate where the study protocol can be accessed or state that a protocol was not prepared. | reference | F A |
| **TRIPOD+AI item 18d**<br>`:00454` | Provide registration information for the study, including register name and registration number, or state that the study was not registered. | clinical trial number | F |
| **TRIPOD+AI item 18e**<br>`:00455` | Provide details of the availability of the study data. | link | F A R |
| **TRIPOD+AI item 18f**<br>`:00456` | Provide details of the availability of the analytical code7. | link, model availability, reproducibility | F A R |
| **TRIPOD+AI item 19**<br>`:00457` | Provide details of any patient and public involvement during the design, conduct, reporting, interpretation, or dissemination of the study or state no involvement. | — | Us Fa |
| **TRIPOD+AI item 20b**<br>`:00458` | Report the characteristics overall and, where applicable, for each data source or setting, including the key dates, key predictors (including demographics), treatments received, sample size, number of outcome events, follow-up time, and amount of missing data. A table may be helpful. Report any differences across key demographic groups. | population | R Un Fa |
| **TRIPOD+AI item 20c**<br>`:00459` | For model evaluation, show a comparison with the development data of the distribution of important predictors (demographics, predictors, and outcome).. | known data-characterization gap | Un Ro Fa |
| **TRIPOD+AI item 21**<br>`:00460` | Specify the number of participants and outcome events in each analysis (e.g., for model development, hyperparameter tuning, model evaluation). | — | Ro |
| **TRIPOD+AI item 22**<br>`:00461` | Provide details of the full prediction model (e.g., formula, code, object, API) to allow predictions in new individuals and to enable third-party evaluation and implementation, including any restrictions to access or re-use (e.g., freely available, proprietary)8. | license, link, model availability | A I R Ex |
| **TRIPOD+AI item 23a**<br>`:00464` | Report model performance estimates with confidence intervals, including for any key subgroups (e.g., sociodemographic). Consider plots to aid presentation. | model performance | Ex Ro Fa |
| **TRIPOD+AI item 23b**<br>`:00465` | If examined, report results of any heterogeneity in model performance across clusters. See TRIPOD Cluster for additional details. | — | Ro Fa |
| **TRIPOD+AI item 24**<br>`:00466` | Report the results from any model updating, including the updated model and subsequent performance. | — | Ex |
| **TRIPOD+AI item 25**<br>`:00467` | Give an overall interpretation of the main results, including issues of fairness in the context of the objectives and previous studies. | — | Ex Us Fa |
| **TRIPOD+AI item 26**<br>`:00468` | Discuss any limitations of the study (such as a non-representative sample, sample size, overfitting, missing data) and their effects on any biases, statistical uncertainty, and generalizability. | limitations | Un Ro Fa |
| **TRIPOD+AI item 27a**<br>`:00469` | Describe how poor quality or unavailable input data (e.g., predictor values) should be assessed and handled when implementing the prediction model. | instructions for use, missing information, model input | Us Ro |
| **TRIPOD+AI item 27b**<br>`:00470` | Discuss whether users will be required to interact in the handling of the input data or use of the model, and what level of expertise is required of users. | degree of automation, instructions for use, model user | Ex Us |
| **TRIPOD+AI item 27c**<br>`:00471` | Discuss any next steps for future research, with a specific view to applicability and generalizability of the model. | — | Un Ex Ro |
| **guideline item**<br>`:00177` | An item of an AI reporting guideline, such as CLAIM or TRAM-AI. Note that these guideline items generally apply to scientific manuscripts (journal articles), rather than the descriptions of the AI models or datasets themselves. | — | Tr |

---

## Audit counts

| | Count |
|---|---|
| Guideline items in the table | 374 |
| — support a principle **and** are supported by metadata | 237 |
| — support a principle but **no metadata** points to them | 118 |
| — supported by metadata but support **no principle** | 19 |
| Metadata to guideline-item links | 415 |
| Guideline-item to principle links | 709 |
| Metadata to principle links (direct) | 36 |
