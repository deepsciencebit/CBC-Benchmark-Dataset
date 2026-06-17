# CBC Benchmark Dataset for Anemia Classification and Severity Assessment

## Overview
This repository contains a de-identified benchmark dataset derived from clinical and laboratory investigations of pregnant women for anemia classification, severity assessment, hematological analysis, and machine learning research. Data upto: 1st June 2025 to 11th June 2026.

## Dataset Summary (CBC_Datasets.csv)
- Total Samples: 473
- Total Attributes: 37
- Target Variable: Severity of anemia 
- Missing Value Handling: MICE + ExtraTreesRegressor
- Format: CSV

## Features: Features Included
_Clinical Features_
- Obs Score L
- LMP known
- USG
- POG (period of gestation or duration of pregnancy in weeks)
- History of blood transfusion during pregnancy
- Family history of hemoglobinopathy
- Dietary habits
- History of any type of allergy
- History of iron supplementation
- Pulse (bpm)
- Icterus
- Pallor
- Edema

_Hematological Features_
- TRBC (in 10^6 /microL)
- Hb (in gm/dL)
- PCV (%)
- MCV (in fL)
- MCH (in pg)
- MCHC (in gm/dL)
- RDW (%)
- Reticulocyte count (in 10^6 /microL)
- Reticulocyte %
- Serum iron (in microg/dL)
- TIBC (in microg/dL)
- Transferrin saturation (%)
- Biochemical Features
- Total bilirubin (mg/dL)
- Direct bilirubin (mg/dL)
- Indirect bilirubin (mg/dL)
- Urea (mg/dL)
- Creatinine (mg/dL)

_Blood Pressure Features_
- SBP (Systolic Blood Pressure)
- DBP (Diastolic Blood Pressure)

_Target Variable_
- Severity of anemia 

## Data Preprocessing
- Feature selection
- De-identification
- Data integration from multiple files
- Missing value standardization
- Blood pressure splitting into SBP and DBP
- MICE-based imputation using ExtraTreesRegressor
- Data validation and consistency checks

## About rawData.csv
- rawData.csv contains 473 de-identified participant records and 143 attributes collected from multiple clinical sites.
- The dataset represents the merged raw data after removal of personal and sensitive identifiers.
- The dataset has not undergone preprocessing, feature selection, or missing-value imputation.
- Missing values, incomplete entries, and original data inconsistencies are preserved as collected.
- This raw dataset serves as the source data for subsequent preprocessing, quality control, and benchmark dataset creation.

## License
Dataset: CC BY 4.0
Code: MIT License

## Citation
See CITATION.cff for citation information.

Kumari, Archana, Ojha, Pushpanjali R., Bishnu, Partha Sarathi, Bhattacharjee, Vandana, Kumar, Dewesh, Mahto, Sunil Kumar, Kumar, Amit, Tubid, Rajluxmi, Verma, Sunil Kumar, Sahu, Monalisha, Kundu, Manas Kumar, Galhotra, Abhiruchi, Chandrakar, Aditi, Jindal, Ashok, Choudhary, Laxmikant, Singh, Vandita, Hussain, Ahmed, & Baghel, Deepanshu. (2026). CBC Benchmark Dataset for Anemia Classification and Severity Assessment (Version 1.0), GitHub. https://github.com/deepsciencebit/CBC-Benchmark-Dataset, DOI: 10.5281/zenodo.20726722, https://zenodo.org/records/20726722

## Contributors
* **Dr. Archana Kumari**,
  Department of Obstetrics and Gynaecology, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

* **Dr. Pushpanjali R. Ojha**,
  Department of Pathology, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

* **Dr. Partha Sarathi Bishnu**,
  Department of Computer Science and Engineering, Birla Institute of Technology (BIT Mesra), Ranchi, Jharkhand, India

* **Dr. Vandana Bhattacharjee**,
  Department of Computer Science and Engineering, Birla Institute of Technology (BIT Mesra), Ranchi, Jharkhand, India

* **Dr. Dewesh Kumar**,
  Department of Community Medicine, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

* **Dr. Sunil Kumar Mahto**,
  Department of Pathology, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

* **Dr. Amit Kumar**,
  Department of Laboratory Medicine, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

  * **Dr. Rajluxmi Tubid**,
  Department of Obstetrics and Gynaecology, Saheed Nirmal Mahto Medical College, Dhanbad, Jharkhand, India

* **Dr. Sunil Kumar Verma**,
  Department of Biochemistry, Saheed Nirmal Mahto Medical College, Dhanbad, Jharkhand, India

* **Dr. Monalisha Sahu**,
  Department of Occupational Health, All India Institute of Hygiene and Public Health, Kolkata, West Bengal, India

* **Dr. Manas Kumar Kundu**,
  Department of Occupational Health, All India Institute of Hygiene and Public Health, Kolkata, West Bengal, India

* **Dr. Abhiruchi Galhotra**,
  Department of Community Medicine, All India Institute of Medical Sciences, Raipur, Chhattisgarh, India

* **Dr. Aditi Chandrakar**,
  Department of Community Medicine, All India Institute of Medical Sciences, Raipur, Chhattisgarh, India

* **Lt. Gen. Ashok Jindal (Retd.)**,
  Department of Community Medicine, All India Institute of Medical Sciences, Raipur, Chhattisgarh, India

* **Dr. Laxmikant Choudhary**,
  Department of Community Medicine, All India Institute of Medical Sciences, Raipur, Chhattisgarh, India

* **Dr. Vandita Singh**,
  Department of Obstetrics and Gynecology, Sadar Hospital, Ranchi, Jharkhand, India

* **Dr. Ahmed Hussain**,
  Department of Obstetrics and Gynaecology, Rajendra Institute of Medical Sciences (RIMS), Ranchi, Jharkhand, India

* **Mr. Deepanshu Baghel**,
  Department of Computer Science and Engineering, Birla Institute of Technology (BIT Mesra), Ranchi, Jharkhand, India


## Future Releases
Additional numerical datasets, image datasets, benchmark protocols, and baseline machine learning models may be added in future releases.
