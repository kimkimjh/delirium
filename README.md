## Identifying Delirium from Electronic Health Records: A Machine Learning Approach
This repository contains the Jupyter Notebook scripts for classification models: Logistic regression & Multi-layer perceptron. 

## Data preparation
Patients' demographic information, Elixhauser index (or other variables of interest), drug exposure, and diagnoses should be vectorized before used as input. Vectors were stored as Pickle files. 
- In our python script, we put demographic information (age, sex) and Elixhauser index into 'demo_records.pkl' as following format: [1, 0, 0.5, 0.4]. The first two value denotes male or female. [1,0] for male and [0,1] for female or vice versa. Age and Elixhauser index were normalized. 
- Drug exposure and diagnoses were one-hot encoded and stored as 'patient_records.pkl'. For example, [1, 0, 0, ..., 0, 1]. 
- Users should also prepare true labels as 'labels.pkl'. 

## Related article
This section will be updated after the acceptance of the manuscript. 
