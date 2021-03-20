# mimic_extract_project

MIMIC-III is an openly available dataset developed by the MIT Lab for Computational Physiology, comprising deidentified health data associated with ~60,000 intensive care unit admissions. It includes demographics, vital signs, laboratory tests, medications, and more.

In this project, I follow MIMIC-Extract's data preprocessing method to standardize unit conversion, detect outliers, aggregate semantically equivalent features and preserve the time series nature of the clinical data. 

I follow their open-source pipeline to transform the raw electronic health
record (EHR) data of critical care patients and host it on a personal Postgres database for use in my master's thesis.


## Links
- MIMIC-III Data https://mimic.physionet.org/
- MIMIC-Extract paper https://arxiv.org/abs/1907.08322
