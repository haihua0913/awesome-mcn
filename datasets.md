# A comprehensive list of existing datasets for medical concept normalization (MCN)

## Overview of the datasets

| Index | Dataset                          | Domain             | Data Source                          | Language                                               | URL                                                               |
|-------|----------------------------------|--------------------|--------------------------------------|--------------------------------------------------------|-------|
| 1     | NCBI disease corpus              | Biomedical corpora | PubMed abstract                      | English                                                | [Link](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/)   |
| 2     | The QUAERO French Medical Corpus | Biomedical corpora | Biomedical research papers           | French                                                 | [Link](https://huggingface.co/datasets/DrBenchmark/QUAERO)        |
| 3     | Mantra GSC                       | Biomedical corpora | MEDLINE titles, drug labels, patents | Multilingual (English, German, French, Spanish, Dutch) | [Link](https://files.ifi.uzh.ch/cl/mantra/gsc/GSC-v1.1.zip)       |
| 4     | BC5CDR                           | Biomedical corpora | PubMed articles                      | English                                                | [Link](https://paperswithcode.com/dataset/bc5cdr)                  |
| 5     | TAC 2017                         | Biomedical corpora | Drug-safety labels                   | English                                                | [Link](https://tac.nist.gov/2017/index.html)                      |
| 6     | SPL-ADR-200db                    | Biomedical corpora | DailyMed drug labels                 | English                                                | [Link](https://bionlp.nlm.nih.gov/tac2017adversereactions/)       |
| 7     | MedMentions                      | Biomedical corpora | PubMed abstracts                     | English                                                | [Link](https://github.com/chanzuckerberg/MedMentions)             |
| 8     | DrugProt                         | Biomedical corpora | PubMed abstracts                     | English                                                | [Link](https://zenodo.org/records/4955411)                        |
| 9     | NEREL-BIO                        | Biomedical corpora | PubMed abstracts                     | Russian                                                | [Link](https://github.com/nerel-ds/NEREL-BIO)                     |
| 10    | WikiMed-DE                       | Biomedical corpora | Wikipedia articles                   | German                                                 | [Link](https://zenodo.org/records/8188966)                        |
| 11    | BioWiC                           | Biomedical corpora | Aggregated biomedical corpora        | English                                                | [Link](https://github.com/hrouhizadeh/BioWiC)                     |
| 12    | WALVIS                           | Biomedical corpora | Wikipedia sentences                  | Dutch                                                  | [Link](https://github.com/fonshartendorp/dutch_biomedical_entity_linking) |
| 13    | i2b2/VA           | Clinical corpora | Patient health records                   | English    | [Link](https://www.i2b2.org/NLP/DataSets/Main.php)         |
| 14    | ShARe/CLEF        | Clinical corpora | Diagnosis documents                      | English    | [Link](https://physionet.org/content/shareclefehealth2013/1.0/) |
| 15    | SemEval-2015 T14  | Clinical corpora | ShARe corpus                             | English    | [Link](https://alt.qcri.org/semeval2015/task14/)           |
| 16    | MIMIC-III         | Clinical corpora | Clinical reports                         | English    | [Link](https://mimic.mit.edu/docs/iii/)                    |
| 17    | MADE              | Clinical corpora | Cancer clinical notes                    | English    | [Link](https://bio-nlp.org/index.php/announcements)        |
| 18    | MCN               | Clinical corpora | Discharge summaries                      | English    |                                                            |
| 19    | Cantemist         | Clinical corpora | Oncological case reports                 | Spanish    | [Link](https://zenodo.org/records/3978041)                 |
| 20    | CMeIE             | Clinical corpora | Medical textbooks and clinical practices | Chinese    | [Link](https://huggingface.co/datasets/Aunderline/CMeIE/tree/main) |
| 21    | CHIP-CDN          | Clinical corpora | Clinical diagnoses                       | Chinese    | [Link](https://tianchi.aliyun.com/dataset/95414)           |
| 22    | nc2c              | Clinical corpora | Clinical notes                           | English    | [Link](https://n2c2.dbmi.hms.harvard.edu/2022-track-1)     |
| 23    | RuCCoN            | Clinical corpora | Medical histories                        | Russian    | [Link](https://github.com/AIRI-Institute/RuCCoN)           |
| 24    | SemClinBr         | Clinical corpora | Clinical notes                           | Portuguese | [Link](https://github.com/HAILab-PUCPR/SemClinBr)          |
| 25    | FRASIMED          | Clinical corpora | Synthetic clinical cases                 | French     | [Link](https://zenodo.org/record/8355629)                  |
| 26    | MedNERF           | Clinical corpora | Typewritten prescriptions                | French     | [Link](https://huggingface.co/datasets/Posos/MedNERF)      |
| 27    | DisTEMIST-linking | Clinical corpora | Clinical cases                           | Spanish    | [Link](https://temu.bsc.es/distemist/)                     |
| 28    | MIMIC-IV          | Clinical corpora | Clinical reports                         | English    | [Link](https://mimic.mit.edu/)                             |
| 29    | SympTEMIST        | Clinical corpora | Clinical reports                         | Spanish    | [Link](https://temu.bsc.es/symptemist)                     |
| 30    | TCMNER            | Clinical corpora | Traditional Chinese medicine diagnoses   | Chinese    | [Link](https://github.com/cshan-github/TCM_NER_datasets)   |
| 31    | RuCCoD            | Clinical corpora | Patient health records                   | Russian    |                                        
| 32    | Cadec        | Social media corpora | AskAPatient posts               | English      | [Link](https://data.csiro.au/collection/17190)                                                  |
| 33    | TwADR-S      | Social media corpora | Twitter posts                   | English      |                                                                                                 |
| 34    | TwADR-L      | Social media corpora | Twitter posts                   | English      | [Link](https://zenodo.org/records/55013)                                                        |
| 35    | AskAPatient  | Social media corpora | ADR blog posts                  | English      | [Link](https://huggingface.co/datasets/bigbio/ask_a_patient)                                   |
| 36    | SMM4H-2017   | Social media corpora | Twitter posts                   | English      | [Link](https://data.mendeley.com/datasets/rxwfb3tysd/2)                                         |
| 37    | TwiMed       | Social media corpora | Twitter, PubMed sentences       | Crosslingual | [Link](https://github.com/nestoralvaro/TwiMed)                                                  |
| 38    | PsyTAR       | Social media corpora | Psychiatric drug reviews        | English      | [Link](https://www.askapatient.com/research/pharmacovigilance/corpus-ades-psychiatric-medications.asp) |
| 39    | HMC2019      | Social media corpora | Twitter posts                   | English      | [Link](https://github.com/biddle-r/HMC2019)                                                     |
| 40    | MedNorm      | Social media corpora | Aggregated social-media corpora | English      | [Link](https://github.com/mbelousov/MedNorm-corpus)                                             |
| 41    | COMETA       | Social media corpora | Reddit posts                    | English      | [Link](https://github.com/cambridgeltl/cometa)                                                  |
| 42    | MedRed       | Social media corpora | Reddit posts                    | English      | [Link](https://goodcitylife.org/Humane-AI/)                                                     |
| 43    | RHMD         | Social media corpora | Reddit posts                    | English      | [Link](https://github.com/usmaann/RHMD-Health-Mention-Dataset)                                 |
| 44    | SocialDisNER | Social media corpora | Twitter posts                   | Spanish      | [Link](https://zenodo.org/records/6803567)                                                      |


## Brief introduction of each dataset

- **TwADR-L dataset** focuses on Twitter messages related to medication and negative drug reactions (NDR). It comprises 1,436 Twitter phrases mapped to one or more of the 2,220 medical concepts. This mapping process results in a dataset containing 50,730 records, with each record including both the informal language and its corresponding normalized medical concept.

- **AskAPatient** is derived from blog posts on the [AskaPatient website](https://www.askapatient.com/), which contains patient-reported experiences with prescription medications. By extracting non-clinical medical terms from social media and mapping them to clinical ontologies like SNOMED-CT and AMT, AskAPatient offers valuable research resources. 

- **The BC5CDR dataset** includes chemical-disease relationships from 1,500 PubMed abstracts. It includes 4,409 chemicals, 5,818 diseases, and 3,116 chemical-disease interactions, making it valuable for training and evaluating machine learning models in biomedical relation extraction.

- **MIMIC-III** is a large, publicly accessible dataset of de-identified electronic health records (EHRs) from over 40,000 critically ill patients (2001-2012) at Beth Israel Deaconess Medical Center. 

- **The SMM4H-2017 dataset** consists of health-related information extracted from tweets, including data on diseases, symptoms, treatments, and sentiment, with annotations derived from social media posts.

- **PsyTAR**, Psychiatric Treatment Adverse Reactions dataset, contains patient reviews about the efficacy and side effects of psychotropic drugs. The initial phase includes 891 drug reviews from visit.askapatient.com, each with demographic information, treatment duration, and detailed patient assessments. The second phase classifies sentences into 6,009 labels across categories like Adverse Drug Reaction (ADR), Withdrawal Symptoms (WDs), and others.

- **MADE corpus** contains 1,089 EHR notes, with 876 for training and 213 for testing, annotated for medication, indication, and adverse drug events. These annotations map to MedDRA and SNOMED-CT terms from the UMLS Metathesaurus, with the training set containing 35,000 mentions and the test set 8,000 mentions.

- **MCN dataset** is instrumental in clinical text normalization. It was developed for the Fourth i2b2/VA Shared Task and includes 100 discharge summaries containing 3,792 concepts with a total of 10,919 mentions from two controlled vocabularies.

- **MedMentions** is a dataset designed for named entity recognition (NER) in biomedical scientific papers. It includes titles and abstracts from 4,392 papers published on PubMed in 2016, covering a range of medical entities such as diseases, chemicals, and genes. This dataset is commonly used for training and evaluating machine learning models and NLP systems in biomedical contexts.

- **MedRed dataset** analyzed 1,980 Reddit posts from 18 subreddits, selecting 110 posts from each. It uses expert-annotated CADEC data for quality control. 
