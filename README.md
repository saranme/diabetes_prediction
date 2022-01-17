# Diabetes prediction
### Description:
A population of women who were at least 21 years old, of Pima Indian heritage and living near Phoenix, Arizona, was tested for diabetes according to World Health Organization criteria. The data were collected by the US National Institute of Diabetes and Digestive and Kidney Diseases. We used the 532 complete records after dropping the (mainly missing) data on serum insulin.

### Format:
These data frames contains the following columns: 
- number of pregnancies. 
- plasma glucose concentration in an oral glucose tolerance test. 
- diastolic blood pressure (mm Hg). 
- triceps skin fold thickness (mm). 
- body mass index (weight in kg/(height in m)2 ).
- diabetes pedigree function.
- age in years. 
- Yes or No, for diabetic according to WHO criteria

### Details:
The training set Pima.tr contains a randomly selected set of 200 subjects, and Pima.te contains the remaining 332 subjects. Pima.tr2 contains Pima.tr plus 100 subjects with missing values in the explanatory variables.

### Goal:
**Develop a model based on the kNN algorithm to determine the value of the "type" variable (Yes: diabetic patient, No: patient without diabetes).**
