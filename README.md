## Reading list for statisticians working on modeling verbal autopsy data

This is a reading list for those interested in analyzing verbal autopsy (VA) data. It is by no means a complete collection of work in the VA community, but only a subset of papers that are potentially useful for statisticians. The list is is intended for new researchers starting to work with [the openVA team](https://openva.net/) to catch up on background literature.

The list also includes papers from related research areas where similar methodological problems exist, as well as papers on general modeling/computation topics that VA algorithms could potentially benefit from. This page is continuously updated to add new VA work and related areas.

Table of contents
* [Verbal autopsy literature](#verbal-autopsy)
  * [Cause-of-death assignment methods](#cause-of-death-assignment-methods)
  * [Data, findings, and background](#data-and-background)
* [Related areas](#related-areas)
  * [Disease modeling](#disease-modeling) 
  * [Text classification]($text-classification)
  * [Psychometrics](#psychometrics)
* [General modeling and computation](#general-modeling-and-computation)

### Verbal autopsy

#### Cause-of-death assignment methods
+ From Narratives to Numbers: Valid Inference Using Language Model Predictions from Verbal Autopsy Narratives [Preprint, 2024](https://arxiv.org/abs/2404.02438)
+ Tree-informed Bayesian multi-source domain adaptation: cross-population probabilistic cause-of-death assignment using verbal autopsy. [Biosstatistics, 2024](https://arxiv.org/abs/2112.10978)
+ Bayesian nested latent class models for cause-of-death assignment using verbal autopsies across multiple domains. [AOAS, 2024](https://arxiv.org/abs/2112.12186)
+ Bayesian Active Questionnaire Design for Cause-of-Death Assignment Using Verbal Autopsies [CHIL, 2023](https://arxiv.org/abs/2302.08099)
+ Correcting for verbal autopsy misclassification bias in cause-specific mortality estimates. [AJTMH](https://pmc.ncbi.nlm.nih.gov/articles/PMC10160858/)
+ Generalized bayes quantification learning under dataset shift. [JASA, 2021](https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1909599)
+ Regularized Bayesian transfer learning for population-level etiological distributions, [Biostatistics, 2021](https://academic.oup.com/biostatistics/article/22/4/836/5732874?login=true)
+ Bayesian hierarchical factor regression models to infer cause of death from verbal autopsy data. [JRSSC, 2021](https://doi.org/10.1111/rssc.12468)
+ Bayesian factor models for probabilistic cause of death assessment with verbal autopsies. [AOAS, 2020](https://projecteuclid.org/euclid.aoas/1587002673)
+ Using Bayesian latent Gaussian graphical models to infer symptom associations in verbal autopsies. [Bayesian Analysis, 2019](https://projecteuclid.org/euclid.ba/1569290444)
+ Multi-task learning for interpretable cause of death classification using key phrase prediction. [BioNLP, 2018](https://aclanthology.org/W18-2302/)
+ An integrated approach to processing WHO-2016 verbal autopsy data: the InterVA-5 model. [BMC Medicine, 2019](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-019-1333-6)
+ Probabilistic cause-of-death assignment using verbal autopsies. [JASA, 2016](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.2016.1152191)
+ Naive Bayes classifiers for verbal autopsies: comparison to physician-based classification for 21,000 child and adult deaths. [BMC Medicine, 2015](https://link.springer.com/article/10.1186/s12916-015-0521-2)
+ Improving performance of the Tariff Method for assigning causes of death to verbal autopsies. [BMC Medicine, 2015](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-015-0527-9)
+ Strengthening standardised interpretation of verbal autopsy data: the new InterVA-4 tool. [Glocal Health Action, 2012](https://www.tandfonline.com/doi/full/10.3402/gha.v5i0.19281)
+ Verbal autopsy methods with multiple causes of death. [Statistical Science, 2008](https://projecteuclid.org/journals/statistical-science/volume-23/issue-1/Verbal-Autopsy-Methods-with-Multiple-Causes-of-Death/10.1214/07-STS247.full)

#### Data and background
+ Verbal Autopsy Interview Standardization Study: A report from the field. [Book chapter, 2020](https://oxford.universitypressscholarship.com/view/10.1093/oso/9780198862437.001.0001/oso-9780198862437-chapter-11)
+ The WHO 2016 verbal autopsy instrument: An international standard suitable for automated analysis by InterVA, InSilicoVA, and Tariff 2.0. [PLOS Medicine, 2018](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002486)
+ Population Health Metrics Research Consortium gold standard verbal autopsy validation study: design, implementation, and development of analysis datasets. [Population Health Metrics, 2011](https://pophealthmetrics.biomedcentral.com/articles/10.1186/1478-7954-9-27)
+ Verbal Autopsy: methods in transition. [Epidemiologic Reviews, 2010](https://academic.oup.com/epirev/article/32/1/38/493908?login=false)


### Related areas

#### Latent Class Models
+ A Blockwise Mixed Membership Model for Multivariate Longitudinal Data: Discovering Clinical Heterogeneity and Identifying Parkinson’s Disease Subtypes [Preprint, 2024](https://arxiv.org/pdf/2410.01235?)
+ Degree-heterogeneous Latent Class Analysis for High-dimensional Discrete Data [Preprint, 2024](https://arxiv.org/pdf/2402.18745)
+ A tensor-EM method for large-scale latent class analysis with binary responses [Psychometrika, 2024](https://link.springer.com/article/10.1007/s11336-022-09887-1)
+ Bayesian Pyramids: Identifiable Multilayer Discrete Latent Structure Models for Discrete Data [JRSSB, 2023](https://arxiv.org/pdf/2101.10373)
+ Integrating Sample Similarities into Latent Class Analysis: A Tree-Structured Shrinkage Approach. [Biometrics, 2021](https://onlinelibrary.wiley.com/doi/10.1111/biom.13580)
+ Probabilistic Cause-of-disease Assignment using Case-control Diagnostic Tests: A Hierarchcial Bayesian Latent Variable Regression Approach. [Statistics in Medicine, 2020](https://onlinelibrary.wiley.com/doi/10.1002/sim.8804)
+ A Bayesian Approach to Restricted Latent Class Models for Scientifically-Structured Clustering of Multivariate Binary Outcomes. [Biometrics, 2020](https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13388)


#### Algorithmic Dementia Classification 
+ Performance of probable dementia classification in a European multi‑country survey [Sci Report, 2024](https://www.nature.com/articles/s41598-024-56734-7.pdf)
+ Invited Commentary: Algorithmic Dementia Classification—Promises and Challenges [AJE, 2023](https://doi.org/10.1093/aje/kwad003)
+ Comparison of Methods for Algorithmic Classification of Dementia Status in the Health and Retirement Study [Epidemiology, 2019](https://pmc.ncbi.nlm.nih.gov/articles/PMC6369894/)
+ Learning From Clinical Consensus Diagnosis in India to Facilitate Automatic Classification of Dementia: Machine Learning Study [JMIR Mental Health, 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8145077/)
+ Factor structure of the Harmonized Cognitive Assessment Protocol neuropsychological battery in the Health and Retirement Study [2024](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/8910F8A75C953C1F42747AEC06659E0C/S135561772300019Xa.pdf/factor-structure-of-the-harmonized-cognitive-assessment-protocol-neuropsychological-battery-in-the-health-and-retirement-study.pdf)
+ [More from HCAP website](https://hcap.isr.umich.edu/publications/)

#### Gabage code redistribution
+ Ill-defined causes of death in Brazil: a redistribution method based on the investigation of such causes. [2014](https://pmc.ncbi.nlm.nih.gov/articles/PMC4181094/)
+ Application of a modified garbage code algorithm to estimate cause-specific mortality and years of life lost in Korea. [2016](https://pubmed.ncbi.nlm.nih.gov/27775249/).
+ Assessment of a regression method to reclassify deaths attributable to heart failure.[2017](https://www.cpc.unc.edu/resources/publications/bib/9685/)
+ Improving the use of mortality data in public health: a comparison of garbage code redistribution models. [AJPH, 2020](https://pubmed.ncbi.nlm.nih.gov/31855478/).
+ Redistribution of garbage codes to underlying causes of death: a systematic analysis on italy and a comparison with most populous western european countries based on the global burden of disease study 2019. [European Journal of Public Health, 2022](https://pubmed.ncbi.nlm.nih.gov/35061890/).
+ Improving the usefulness of US mortality data: new methods for reclassification of underlying cause of death [PHM, 2016](https://pophealthmetrics.biomedcentral.com/articles/10.1186/s12963-016-0082-4)


#### Text classification
+ Dynamic Topic Models. [ICML, 2006](https://mimno.infosci.cornell.edu/info6150/readings/dynamic_topic_models.pdf)
+ Correlated Topic Models. [NeurIPS, 2005](https://proceedings.neurips.cc/paper/2005/file/9e82757e9a1c12cb710ad680db11f6f1-Paper.pdf)
+ Latent Dirichlet Allocation. [JMLR, 2003](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

#### Psychometrics
+ Regularized Latent Class Analysis with Application in Cognitive Diagnosis. [Psychometrika, 2016](https://link.springer.com/article/10.1007/s11336-016-9545-6)
+ Latent Variable Selection for Multidimensional Item Response Theory Models via L1 Regularization. [Psychometrika, 2016](https://link.springer.com/article/10.1007/s11336-016-9529-6)

### General modeling and computation
+ Using Stacking to Average Bayesian Predictive Distributions. [Baysian Analysis, 2018](https://projecteuclid.org/journals/bayesian-analysis/volume-13/issue-3/Using-Stacking-to-Average-Bayesian-Predictive-Distributions-with-Discussion/10.1214/17-BA1091.full)
+ Bayesian conditional tensor factorizations for high-dimensional classification. [JASA, 2016](https://www.tandfonline.com/doi/abs/10.1080/01621459.2015.1029129?journalCode=uasa20)
+ Bayesian Factorizations of Big Sparse Tensors. [JASA, 2015](https://www.tandfonline.com/doi/abs/10.1080/01621459.2014.983233?journalCode=uasa20)
+ Bayesian estimation of discrete multivariate latent structure models with structural zeros. [JASA, 2014](https://www.tandfonline.com/doi/abs/10.1080/10618600.2013.844700)
+ Sentiment Analysis of Online Media [Book Chapter, 2013](https://link.springer.com/chapter/10.1007/978-3-319-00035-0_13)
+ Nonparametric Bayes modeling of multivariate categorical data. [JASA, 2009](https://www.tandfonline.com/doi/abs/10.1198/jasa.2009.tm08439) 
+ Bayesian non-negative matrix factorization. [ICA, 2009](https://link.springer.com/chapter/10.1007/978-3-642-00599-2_68)
