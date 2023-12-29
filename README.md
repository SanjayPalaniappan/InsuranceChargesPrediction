A client’s requirement is, he wants to predict the insurance charges based on the several parameters-Age, Sex, BMI, Children, Smoker. The Client has provided the dataset of the same

**Description:**
With given parameters such as person’s age, sex, number of children, BMI, smoking habits, we need to find the insurance charge/premium that he need to pay. That is, we need to predict the insurance premium amount of
a person provided, when the mentioned parameters are available

Stage 1: Domain selection - Machine Learning
Stage 2: Learning Selection - Supervised Learning
Stage 3: Algorithm - Regression

**Basic Information about the dataset:**
Input Columns
Age (type: numerical), Sex (type: categorical-nominal), BMI (type: numerical), Children (type: numerical), Smoker (type: categorical-nominal)
Output Columns
Charges (type: numerical)

Total number of rows present: 1338
Total number of columns present: 6

**Pre-processing method:**
One Hot Encoding
There are 2 categorical(nominal) columns namely sex and smoker in dataset. So, in order to apply regression algorithms, we convert those categorical columns into numerical columns using One Hot Encoding technique
Standardization
Age column values contains 2 digits, charges column values contain 5 digits and above, sex and smoker columns contain single digit value after apply one hot encoding. So, to make all columns into same scale, we apply Standardization technique.
