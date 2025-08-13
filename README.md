### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 13/08/2025
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
### a) Employee dataset:
<img width="1248" height="928" alt="image" src="https://github.com/user-attachments/assets/199cead4-8c3e-4e0e-a561-55be9bbe5058" />

### b) Weather dataset:
<img width="1342" height="953" alt="image" src="https://github.com/user-attachments/assets/6800bb6f-5254-4799-bf12-ddeaf9a6763f" />


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
### a) Employee dataset:
<img width="1421" height="955" alt="Screenshot 2025-08-08 105914" src="https://github.com/user-attachments/assets/ad098301-b1a4-4348-9c10-d5d05c2dd231" />

### b) Weather dataset:
<img width="1376" height="932" alt="Screenshot 2025-08-08 111235" src="https://github.com/user-attachments/assets/c49fb528-2d25-4138-a2f2-dffe45141da6" />


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
### a) Employee dataset:
<img width="1412" height="972" alt="Screenshot 2025-08-08 105954" src="https://github.com/user-attachments/assets/06fbf2c1-4983-4b8e-9b90-87c1b7f7b720" />

### b) Weather dataset:
<img width="1266" height="949" alt="Screenshot 2025-08-08 111328" src="https://github.com/user-attachments/assets/a762902f-ce1a-45f1-a5b2-c96d3c94eb55" />

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
### a) Employee dataset:
<img width="1397" height="958" alt="Screenshot 2025-08-08 110112" src="https://github.com/user-attachments/assets/6c71784b-6427-4b30-bdee-bc5f5f17b5bd" />

### b) Weather dataset:
<img width="1357" height="966" alt="Screenshot 2025-08-08 111401" src="https://github.com/user-attachments/assets/0566b9f1-de39-4ccd-b269-0e5298fdac39" />
### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
