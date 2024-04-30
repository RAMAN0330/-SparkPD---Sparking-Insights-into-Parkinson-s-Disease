# SparkPD--Sparking-Insights-into-Parkinson's-Disease

## Abstract

**The Oxford Parkinson's Disease Telemonitoring Dataset encompasses a collection of biomedical voice measurements obtained from 42 individuals diagnosed with early-stage Parkinson's disease participating in a six-month trial of a telemonitoring device for remote symptom progression monitoring. Compiled by Athanasios Tsanas and Max Little of the University of Oxford in collaboration with medical centers in the US and Intel Corporation, this dataset facilitates the prediction of motor and total Unified Parkinson's Disease Rating Scale (UPDRS) scores from 16 voice measures. With 5,875 instances and 26 attributes including subject demographics, UPDRS scores, and various voice features, the dataset serves as a valuable resource for regression tasks aimed at accurately estimating Parkinson's disease symptom severity using non-invasive speech tests. Researchers and practitioners can utilize this dataset to develop and evaluate algorithms for telemonitoring Parkinson's disease progression, ultimately contributing to improved patient care and management. To ensure proper attribution, users are encouraged to cite the relevant paper when utilizing this dataset in their research endeavors.**

---

## Data Set Characteristics

- **Type:** Multivariate
- **Attribute Characteristics:** Integer, Real
- **Associated Tasks:** Regression
- **Number of Instances:** 5875
- **Number of Attributes:** 26
- **Area:** Life
- **Date Donated:** 2009-10-29

---

## Source

The dataset was created by Athanasios Tsanas (tsanasthanasis '@' gmail.com) and Max Little (littlem '@' physics.ox.ac.uk) of the University of Oxford, in collaboration with 10 medical centers in the US and Intel Corporation who developed the telemonitoring device to record the speech signals. The original study used a range of linear and nonlinear regression methods to predict the clinician's Parkinson's disease symptom score on the UPDRS scale.

---

## Data Set Information

This dataset comprises a range of biomedical voice measurements from 42 people with early-stage Parkinson's disease recruited to a six-month trial of a telemonitoring device for remote symptom progression monitoring. The recordings were automatically captured in the patients' homes.

Columns in the table contain subject number, subject age, subject gender, time interval from baseline recruitment date, motor UPDRS, total UPDRS, and 16 biomedical voice measures. Each row corresponds to one of 5,875 voice recordings from these individuals. The main aim of the data is to predict the motor and total UPDRS scores ('motor_UPDRS' and 'total_UPDRS') from the 16 voice measures.

The data is in ASCII CSV format. Each row of the CSV file contains an instance corresponding to one voice recording. On average, there are around 200 recordings per patient, with the subject number of the patient identified in the first column. For further information or to provide comments, please contact Athanasios Tsanas (tsanasthanasis '@' gmail.com) or Max Little (littlem '@' physics.ox.ac.uk).

Further details are contained in the following reference: Athanasios Tsanas, Max A. Little, Patrick E. McSharry, Lorraine O. Ramig (2009), 'Accurate telemonitoring of Parkinson's disease progression by non-invasive speech tests', IEEE Transactions on Biomedical Engineering.

---

## Attribute Information

The dataset includes the following attributes:

- `subject#`: Integer that uniquely identifies each subject
- `age`: Subject age
- `sex`: Subject gender ('0' for male, '1' for female)
- `test_time`: Time since recruitment into the trial. The integer part is the number of days since recruitment.
- `motor_UPDRS`: Clinician's motor UPDRS score, linearly interpolated
- `total_UPDRS`: Clinician's total UPDRS score, linearly interpolated
- `Jitter(%)`, `Jitter(Abs)`, `Jitter:RAP`, `Jitter:PPQ5`, `Jitter:DDP`: Several measures of variation in fundamental frequency
- `Shimmer`, `Shimmer(dB)`, `Shimmer:APQ3`, `Shimmer:APQ5`, `Shimmer:APQ11`, `Shimmer:DDA`: Several measures of variation in amplitude
- `NHR`, `HNR`: Two measures of ratio of noise to tonal components in the voice
- `RPDE`: A nonlinear dynamical complexity measure
- `DFA`: Signal fractal scaling exponent
- `PPE`: A nonlinear measure of fundamental frequency variation

---

## Relevant Papers

- Little MA, McSharry PE, Hunter EJ, Ramig LO (2009), 'Suitability of dysphonia measurements for telemonitoring of Parkinson's disease', IEEE Transactions on Biomedical Engineering, 56(4):1015-1022
- Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. 'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)

---

## Citation Request

If you use this dataset, please cite the following paper: A Tsanas, MA Little, PE McSharry, LO Ramig (2009) 'Accurate telemonitoring of Parkinson.s disease progression by non-invasive speech tests', IEEE Transactions on Biomedical Engineering.


