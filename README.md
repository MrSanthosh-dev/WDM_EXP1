### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### NAME : SANTHOSH S
### REGISTER NUMBER : 212222100047
### DATE: 10.02.2024
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
EMPLOYEE DATA:
![1a](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/f07d3de3-e213-4373-bb77-1f903c12f17a)
WEATHER DATA:
![1bb](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/729a9527-4617-48d0-8e0f-a1620fb832d2)

### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
EMPLOYEE DATA:
![1d(i)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/db2357be-1e24-403f-a01c-db41b8de78cf)
WEATHER DATA:
![1c(i)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/5bd1fc56-2026-4052-8943-d50734b0b0ec)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
EMPLOYEE DATA:
![1d(ii)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/48b5772c-99cf-45cc-b779-b2a1c847b5db)
WEATHER DATA:
![1c(ii)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/a95ec296-d820-4414-b15e-02a273f71aec)

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
EMPLOYEE DATA:
![1d(iii)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/bb176702-2705-4c97-8ecc-abc0ae3143f0)
WEATHER DATA:
![1c(iii)](https://github.com/MrSanthosh-dev/WDM_EXP1/assets/117916573/7d18a87f-0678-4f50-9d19-fbd7e7a523e3)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
