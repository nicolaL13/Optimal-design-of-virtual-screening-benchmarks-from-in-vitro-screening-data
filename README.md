# Optimal-design-of-virtual-screening-benchmarks-from-in-vitro-screening-data
This project shows a novel pipeline for benchmark dataset curation using PubChem data. with multiple steps of filtering and processing bioactivity data. 
# Structure
- Step1-TargetExtraction: a method of predicting an assay's target from its AID
- Step-2-Grouping: filtering data and grouping records based on PubChem Source and Target
- Step3-DoseResponse: method of labelling Assay data whether it includes a dose-response curve.
- target_types: tagging assays by target type using keyword categorisation
- disease_type: tagging assays by disease type using keyword categorisation
# Setup 
libraries required:
- Pandas 
- Beautiful Soup 
- requests
- ast
- csv
- collections 

all can be installed using pip 

