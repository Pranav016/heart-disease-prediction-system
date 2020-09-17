# About repo-
This is a heart disease prediction system implemented using Logistic Regression Algorithm. Logistic regression is used to predict a binary outcome based on a set of independent variables.</br>

# Data dictionary
age - age in years
sex - (1 = male; 0 = female)
cp - chest pain type
0: Typical Angina: Chest pain related decrease blood supply to the heart 
1: Atypical Angeina: Chest pain not related to 
heart 
2: Non-anginal pain: typically esophagal spasms(non heart related) 
3: Asymptomatic: chest pain not showing signs of disease

trestbps - resting blood pressure (in mm Hg on admission to the hospital)
chol - serum cholestoral in mg/dl s erum = LDL + HDL +.2triglvcerides
above 200 is cause for concern 

fbs - (fasting blood sugar > 120 mg/dl) - (1 = true; 0 = false) '>126' mg/dL signals diabetes

restecg - resting electrocardiographic results
0: Nothing to note 
1: ST-T wave abnormality can range from mild symptoms to severe problems signals non-normal heart beat 
2: Possible or definite left ventricular hypertrophy. Enlarged heart's main pumping chamber

thalach - maximum heart rate achieved
exang exercise induced angina - (1 = yes; 0 = no)
oldpeakST - depression induced by exercise relative to rest
slope the - slope of the peak exercise ST segment
ca number of major vessels - (0-3) colored by flourosopy
thal 3 = normal; 6 = fixed defect; 7 = reversable defect
target - 1 or 0

# Plots-
* Relation between age and max heart rate achieved among all those tested positive or negative- 
[Plot1](plots/plot1.png)</br>

* Heart disease found in patients of different sex- 
[Plot2](plots/plot2.png)</br>

* Distribution of cholestrol among heart patients- 
[Plot3](plots/plot3.png)</br>

* Relation between chest pain type and heart disease- 
[Plot4](plots/plot4.png)</br>

* Who have higher cholestrol at particular ages, males or females- 
[Plot5](plots/plot5.png)</br>

* Checking if max heart was achieved by people having very high fasting blood sugar- 
[Plot6](plots/plot6.png)</br>

* Correlation matrix-
[Plot7](plots/plot7.png)</br>


# Technology used:
Python

# Packages used:
sklearn</br>
matplotlib </br>
seaborn </br>
pandas</br>
numpy</br>

# Environment Setup and Local Installation:
1. Drop a :star: on the Github Repository.

1.  Make sure to install python on your computer- https://www.python.org/downloads/ </br>

1. Download Python IDE or text editor for python code <br/>
*	[Install Anaconda for Windows](https://docs.anaconda.com/anaconda/install/windows/) <br/>
*	[Install Anaconda for MacOS](https://docs.anaconda.com/anaconda/install/mac-os/) <br/>
*	[Install Anaconda for Linux](https://docs.anaconda.com/anaconda/install/linux/) <br/>
*	[Install VS code for Windows/Mac/Linux](https://code.visualstudio.com/Download) </br>

1. Clone the Repo by going to your local Git Client and pushing this command: <br/>
	```git clone https://github.com/Pranav016/heart-disease-prediction-system.git```

1. Go to the AnacondaPrompt/CMD and use this command to install the packages: <br/>
	```pip install -r requirements.txt```

1. Open the project in the Jupyter Notebook/VS code to use it.
