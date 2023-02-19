# Sampling_Assignment
## 1. Methodology

![image](https://user-images.githubusercontent.com/79744977/219941787-1f042372-b704-43ab-83ec-7cea312df128.png)
### Flow chart
![image](https://user-images.githubusercontent.com/79744977/219944196-82415170-12c1-4970-b3ba-bc654e5d863b.png)

## 2. Description

Original Size of data = 772 rows 31 columns

Size of data after removing time column = 772 rows 30 columns

Data with class 0 = 763 rows

Data with class 1 = 9 rows


Size of data after using SMOTE= 1526 rows 30 columns

Data with class 0 = 763 rows

Data with class 1 = 763 rows

### Formula's Used
n=size of sample

N=size of population

Z=z-score corresponding to desired confidence level 

p=estimated proportion of the population with certain characteristic

E=desired margin of error


Size of sample in random sampling is calculated using n=(Z^2*p*(1-p))/E^2

Size of sample in stratified sampling is calculated using n=(Z^2*p*(1-p))/(E/S)^2

Size of sample in cluster sampling is calculated using n=(Z^2*p*(1-p))/(E/C)^2

Size of sample in systematic sampling is calculated using n=N/(1+(N*E^2)

Size of sample in multistage sampling is calculated using same formula as random sampling and random sample is used in both stages.

### Best Model : Decision Tree
### Best Accuracy : 96.45%
### Sampling Technique : Stratified Sampling 

## 3. Final Result
![image](https://user-images.githubusercontent.com/79744977/219945472-a93b3f84-866e-4294-b5ef-08214a3f9c48.png)




