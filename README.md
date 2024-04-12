# Healthcare- Analysis
# Dashboard Requirements:

# View 1: Diabetic/Non-diabetic using Shapes
Use Shapes to show the distribution between diabetic/non-diabetic patients.
Using the “Outcome” field, write a calculated field by classifying 1 as Diabetic patients and 0 as Non-diabetic patients.
Show the percent distribution as shown in the expected view.
Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.
Tooltip should display patient count.
You can use shapes of your choice or use the below one.
Format as per your choice.
Enable Action filters.

# View 2: Patient summary by Blood Pressure category
Use any shape of your choice to show patient summary by blood pressure category.
Show the Patient count and BP category type on the labels.
Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.
Format as per your choice.
Enable Action filters.

# View 3: Create a Histogram to show Body Mass Index (BMI) by Age Groups.
Since we need to build a Histogram, using the Age field, let’s create bins using size 5.
In a Histogram, you will have bins 20, 25, 30, etc. So, the bin size 20 will include age groups between 20-24, and size 25 will include 25-29. So, to be clear let’s edit the aliases of the age groups as it might confuse the users. So, let’s use aliases as shown below or you can create a calculated field for the Age groups.

# View 4: Single Bar showing percent distribution of patients by BMI type
Create a calculated field to classify Patients by BMI types.
[BMI]<18.5= 'Underweight'
[BMI]>=18.5 and [BMI]<25 ='Healthy Weight'
[BMI]>=25 and [BMI]<30 = 'Overweight'
[BMI]>=30 ='Obese'
Enable Action filters.

# View 5: Bar Chart showing Patient break down by Blood Pressure and Diabetes
Create a calculated field to only highlight Diabetic patients with High and Low blood pressures.

# View 6: Build a HEAT MAP showing several health factors by Age group
