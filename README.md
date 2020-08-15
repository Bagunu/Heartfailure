https://public.tableau.com/profile/bright3057#!/vizhome/FinalProject_15969138457430/Dashboard1?publish=yes



# Heart Disease UCI-Diagnosis & Prediction <br>
Every day, the average human heart beats around 100,000 times, pumping 2,000 gallons of blood through the body. Inside your body there are 60,000 miles of blood vessels.  Men experience typical symptoms of heart attack, such as chest pain , discomfort, and stress. They may also experience pain in other areas, such as arms, neck , back, and jaw, and shortness of breath, sweating, and discomfort that mimics heartburn.<br>
This work shows the important features that have direct impact in heart disease, and how good we can predict the heart failure.
## Data-set description<br>
Context
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date.<br>
Dataset columns:<br>
age: The person’s age in years<br>
sex: The person’s sex (1 = male, 0 = female)<br>
cp: chest pain type<br>
— Value 0: asymptomatic<br>
— Value 1: atypical angina<br>
— Value 2: non-anginal pain<br>
— Value 3: typical angina<br>
trestbps: The person’s resting blood pressure (mm Hg on admission to the hospital)<br>
chol: The person’s cholesterol measurement in mg/dl<br>
fbs: The person’s fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)<br>
restecg: resting electrocardiographic results<br>
— Value 0: showing probable or definite left ventricular hypertrophy by Estes’ criteria<br>
— Value 1: normal<br>
— Value 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)<br>
thalach: The person’s maximum heart rate achieved<br>
exang: Exercise induced angina (1 = yes; 0 = no)<br>
oldpeak: ST depression induced by exercise relative to rest (‘ST’ relates to positions on the ECG plot. See more here)<br>
slope: the slope of the peak exercise ST segment — 0: downsloping; 1: flat; 2: upsloping
0: downsloping; 1: flat; 2: upsloping<br>
ca: The number of major vessels (0–3)<br>
thal: A blood disorder called thalassemia Value 0: NULL (dropped from the dataset previously<br>
Value 1: fixed defect (no blood flow in some part of the heart)<br>
Value 2: normal blood flow<br>
Value 3: reversible defect (a blood flow is observed but it is not normal)<br>
target: Heart disease (1 = no, 0= yes)<br>
## Data cleaning and visualization<br>
Before running any model, we first check and analyze the data to see if any correctness should be made. <br>
Checking for multicollinearity with correlation plots.<br>
Some visualization with important features to get deep understanding.
## Running models with default paramaters<br>
We run models, which algorithm gives the best results we will continue with optimizing hyperparameters of the selected model.

## Acknowledgements<br>
Creators:<br>

Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.<br>
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.<br>
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.<br>
V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.<br>
Donor:<br>
David W. Aha (aha '@' ics.uci.edu) (714) 856-8779<br>
