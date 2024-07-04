
# Titanic Survival Prediction

![Titanic Survival](https://github.com/Soumyabk3/CODSOFT_Titanic_Survival_Prediction_Task1/blob/main/Titanic%20Survival.png?raw=true)

## Overview

This project predicts the survival of passengers on the Titanic using logistic regression. The dataset used is the Titanic Dataset, which includes features such as passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and port of embarkation.

## Dependencies

To run this project, you need to install the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- IPython

## Installation

Install the necessary dependencies.

## For Example
## Installation

To install the specified packages (numpy, pandas, matplotlib, seaborn, scikit-learn, and ipython) and generate a requirements.txt file, follow these steps:


1. *Set up a Virtual Environment*:

```bash
    python -m venv venv
```
 


2. *Activate the Virtual Environment*:
- On Windows:
        

```bash
venv\Scripts\activate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

    
3. *Install the Required Packages*:

```bash
 pip install numpy pandas matplotlib seaborn scikit-learn ipython 
```  

 

4. *Generate the requirements.txt File**:

```bash
   pip freeze > requirements.txt
```   
  
 ---  

## Combined Script

Here is the combined script for all steps:


### Step 1: Set up a virtual environment


```bash
  python -m venv venv
```



### Step 2: Activate the virtual environment
#### For Windows:

```bash
  venv\Scripts\activate
```

### For macOS/Linux:
### source venv/bin/activate

#### Step 3: Install the required packages

```bash
  pip install numpy pandas matplotlib seaborn scikit-learn ipython
```

```bash
  pip install numpy pandas matplotlib seaborn scikit-learn ipython
```

### Step 4: Generate the requirements.txt file
```bash
  pip freeze > requirements.txt
```



###### Resulting requirements.txt

### After running the above commands, your requirements.txt file will include entries similar to these (exact versions may vary):

```bash
 txt
ipython==8.4.0
matplotlib==3.5.2
numpy==1.22.4
pandas==1.4.2
scikit-learn==1.1.1
seaborn==0.11.2
```



This file ensures that the same versions of these packages can be installed in any environment by running:


```bash
pip install -r requirements.txt
```




## Summary
- Here we loaded Dependencies

- Data Collection and Preprocessing
- Data Loading the dataset from a CSV file:

- Get the shape and basic information of the dataset:


- Check and handle missing values:

- Data Analysis

- Data Visualization

- Encoding the Categorical Columns
- Replace categorical values with numerical values:

- Feature Selection

- Splitting the Data:    Split the data into training and test sets:

- Model Training:
   Train the logistic regression model


- Model Evaluation:
  Calculate the accuracy score:

- Prediction

## Conclusion
This project demonstrates a step-by-step approach to building a machine learning model for predicting Titanic survival. It covers data loading, preprocessing, visualization, and model training and evaluation using logistic regression.
## Authors

- [@Soumyabk3](https://github.com/Soumyabk3)

