# Synthetic Clinical Diaries

This repository contains a collection of synthetic clinical diaries developed for the development and evaluation of an LLM-based clinical information summarisation system.

The dataset was created as part of a master's dissertation focused on the use of Large Language Models (LLMs) to extract, structure, and summarise longitudinal clinical information from unstructured free-text clinical diaries.

## Overview

Clinical information in healthcare environments is frequently recorded as unstructured free text. The longitudinal analysis of these records can be time-consuming for clinicians, particularly in emergency care, where rapid access to relevant patient information is important.

To support the development of the proposed system, a synthetic dataset of clinical diaries was created. The diaries were designed to reproduce characteristics of unstructured clinical documentation and to provide a controlled environment for the iterative development and evaluation of the LLM-based processing pipeline.

## Dataset

The dataset contains clinical diaries for **15 synthetic patients**. Each patient has a variable number of diary entries representing different clinical encounters and points in time.

The diaries are written in **Portuguese** to reflect the language and characteristics of clinical documentation in a Portuguese hospital setting.

The dataset is organised by patient:

```text
patients/
├── patient_01/
│   ├── diary_01.txt
│   ├── diary_02.txt
│   └── ...
├── patient_02/
│   ├── diary_01.txt
│   └── ...
├── patient_03/
│   └── ...
├── ...
└── patient_15/
    ├── diary_01.txt
    └── ...
```

Each `.txt` file represents an individual synthetic clinical diary entry. The number of diary entries varies between patients in order to represent different longitudinal clinical histories.

## Synthetic Data

All clinical information contained in this repository is synthetic and was created for research and development purposes.

The dataset does **not** contain real patient records or personally identifiable information. The synthetic patients do not correspond to real individuals, and the information contained in the diaries should not be interpreted as real clinical documentation.

The dataset should therefore be considered a research resource for the development and evaluation of clinical information processing methods rather than a representation of actual patient records.

## Purpose

The synthetic clinical diaries were developed primarily to support the development phase of an LLM-based clinical information summarisation system.

They were used to support:

* Development and refinement of LLM prompts;
* Evaluation of clinical information extraction;
* Structuring of information according to a Clinical Information Model;
* Development of longitudinal patient summarisation;
* Development of clinical information interpretation;
* Testing of the overall processing pipeline in a controlled environment.

The use of synthetic data during development allowed the system to be iteratively refined before evaluation using real clinical data.

## Language and Clinical Context

The diaries are written in **Portuguese** and were designed to reflect the characteristics of clinical documentation from a Portuguese healthcare context.

The synthetic records reproduce aspects of unstructured clinical narratives, including information related to:

* Diagnoses and medical history;
* Medication;
* Allergies;
* Symptoms and clinical signs;
* Examinations and results;
* Therapeutic interventions and clinical plans;
* Temporal evolution of the patient's clinical history.

The records are intentionally presented as free-text clinical narratives rather than as structured datasets.

## Data Format

The clinical diaries are provided as plain-text (`.txt`) files.

Each file corresponds to one diary entry and contains unstructured clinical information in Portuguese.

The dataset does not impose a fixed number of diary entries per patient. Instead, each patient folder contains the number of synthetic diary entries associated with that patient's longitudinal history.

## Relationship to the Research

The synthetic dataset corresponds to the **development phase** of the research described in the associated master's dissertation.

The subsequent production-phase evaluation was performed using real clinical data obtained under the applicable institutional, ethical, and data protection requirements.

**Real clinical data used during the production phase are not included in this repository.**

## Intended Use

This dataset is intended to support research and development in areas including:

* Clinical Natural Language Processing;
* Large Language Models;
* Clinical information extraction;
* Clinical text summarisation;
* Longitudinal patient modelling;
* Clinical decision-support research;
* Evaluation of LLM-based healthcare applications.

Researchers may use the dataset to investigate approaches for processing and summarising unstructured clinical narratives.

## Limitations

The dataset is synthetic and therefore does not fully reproduce the complexity, variability, or distribution of real-world clinical documentation.

Although the diaries were designed to reflect characteristics of clinical records from a Portuguese healthcare setting, they should not be considered representative of the complete range of documentation practices found in Portuguese hospitals.

Results obtained using this dataset should therefore be interpreted in the context of its synthetic nature.

## Disclaimer

The information contained in this repository is entirely synthetic and is provided exclusively for research and development purposes.

The clinical information presented in the diaries does not represent real patients and should not be used for clinical decision-making or considered medical advice.

## Related Work

This dataset was developed as part of a master's dissertation investigating the application of Large Language Models to longitudinal clinical information summarisation in emergency care.

Further information about the methodology, system architecture, evaluation, and results can be found in the associated dissertation.
