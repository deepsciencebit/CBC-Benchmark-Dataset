# CBC Benchmark Dataset for Anemia Classification and Severity Assessment

## Overview
This repository contains a de-identified benchmark dataset derived from clinical and laboratory investigations of pregnant women for anemia classification, severity assessment, hematological analysis, and machine learning research.

## Dataset Summary
- Total Samples: 473
- Total Attributes: 37
- Target Variable: Severity of anemia (on the basis of Hb)
- Missing Value Handling: MICE + ExtraTreesRegressor
- Format: CSV

## Features
Clinical, hematological, biochemical, blood pressure, and anemia severity attributes selected based on clinical relevance and relatively low missingness.

## Data Preprocessing
- Feature selection
- De-identification
- Data integration from multiple files
- Missing value standardization
- Blood pressure splitting into SBP and DBP
- MICE-based imputation using ExtraTreesRegressor
- Data validation and consistency checks

## License
Dataset: CC BY 4.0
Code: MIT License

## Citation
See CITATION.cff for citation information.

## Contributors
- Archana Kumari
- Pushpanjali Ojha
- Partha Sarathi Bishnu
- V. Bhattacharjee
- Ahmed
- Deepanshu

## Future Releases
Additional numerical datasets, image datasets, benchmark protocols, and baseline machine learning models may be added in future releases.
