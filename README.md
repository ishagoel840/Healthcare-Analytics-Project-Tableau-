# Healthcare- Analysis
###### Tools used: Tableau

## About Dataset
The Healthcare-Dataset consists of various columns, each  provideing specific information about the patient, their Age, Blood Pressure, Body Mass Index(BMI), Skin Thickness etc. Utilizing this dataset to explore the relationships between various health indicators and the likelihood of diabetes.

## Key details
###### Total Entries: The dataset contains 768 entries.
###### Columns: There are 9 columns in the dataset:
1. ID: A unique identifier for each Patient.
2. Age: Age in years.
3. Blood pressure: Diastolic blood pressure (mm Hg).
4. BMI:  Body mass index (weight in kg / height in m^2).
5. Diabetes Pedigree Function: Diabetes pedigree function, a genetic score of diabetes.
6. Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
7. Insulin: Insulin level of the patient.
8. Outcome: : Binary classification indicating the presence (1) or absence (0) of diabetes.
9. Skin Thickness: Triceps skinfold thickness (mm)..
    
## Dashboard Components:

`View 1: Diabetic/Non-diabetic using Shapes`

Displayed the percent distribution of Diabetic Vs. Non-diabetic patients.


` View 2: Patient summary by Blood Pressure category`

Created a patient summary categorized by blood pressure into four different groups.


`View 3: Histogram to show BMI by Age groups`

Create a Histogram to show Body Mass Index (BMI) by Age Groups.
In a Histogram, you will have bins 20, 25, 30, etc. So, the bin size 20 will include age groups between 20-24, and size 25 will include 25-29.

`View 4: Single Bar showing percent distribution of patients by BMI type`

Created a calculated field to classify Patients by BMI types.
[BMI]<18.5= 'Underweight'
[BMI]>=18.5 and [BMI]<25 ='Healthy Weight'
[BMI]>=25 and [BMI]<30 = 'Overweight'
[BMI]>=30 ='Obese'


`View 5: Bar Chart showing Patient break down by Blood Pressure and Diabetes`

Created a calculated field to only highlight Diabetic patients with High and Low blood pressures.

`View 6: Build a HEAT MAP showing several health factors by Age group`

Generated a Heat map that displays variour health factors according to different Age groups.

`Created a Dashboard and story for the above views.`

Throughout the project, I utilized Tableau's powerful features to create dynamic and interactive dashboards.
