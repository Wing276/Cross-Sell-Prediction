# Cross-Sell-Prediction
## 1. Background
- This data comes from clients of an insurance company. These clients have already bought the medical insurance. The company now wants to launch a new transportation insurance and find those who will be interested in this insurance.
## 2. Data Set Information
- The data is related to an insurance selling problem. The clients' information is about clients' basic information and their vehicle's situations.
#### This data set contains two files:
1. insurance-train.csv
	- The training set with 11 input attributes and 1 output attribute (i.e. class attribute)
2. insurance-test.csv
	- The testing set with 11 input attributes. You need to identify the class of each item. 

#### Other files:
1. evaluate_1.exe:
	- This is a command line tool to evaluate your result. F1-measure is used to measure your result.
	- Usage: Press "command + r" and then type in "cmd" in the dialog box to launch a terminal. Then type in the command:
```bash
evaluate_1.exe submission_1_method.csv
```

2. submission_1_dtree:
	- prediction result from a decision tree classifier
    
3. submission_1_ada: 
	- prediction result from a adaboost classifier
    
4. insurance.ipynb: 
	- The file contains all the classifiers that I have tried, adaboost performs the best
	- If, by any chance, you can not view my notebook on github (*Sorry, something went wrong. Reload?* pops up), one way is to place the github.com url of the notebook into https://nbviewer.jupyter.org/ 

## 3. Goal

- The classification goal is to predict if the client will buy the transportation insurance (i.e. identify the value of feature 'Response', 1 for yes and 0 otherwise).

## 4. Attribute Information
#### a) Input variables
**clients' basic information**
1. ID: Unique ID of clients (numeric)
2. Gender: Gender of clients (categorical: 'Male', 'Female')
3. Age: Age of clients (numeric)
4. Driving_License: whether the clients have a driving license (categorical: '0', '1')
5. Region_Code: Unique code for the region of the clients (numeric)
6. Previously_Insured: whether the clients already have a transportation insurance (categorical: '0', '1')

**clients' vehicle situations**
1. Vehicle_Age: Age of the Vehicle (string)
2. Vehicle_Damage: whether the vehicle has been damaged (categorical: 'No', 'Yes')

**other attributes**
1. Annual_Premium: The amount customer needs to pay as premium in the year (numeric)
2. Policy_Sales_Channel: Anonymised Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc. Here, using unique numbers to represent different channel (numeric)
3. Vintage: Number of Days that Customer has been associated with the company (numeric)

#### b) Output variable
1. Response: whether the client is interested in it (categorical: '0', '1')

Remark: This is my school projects modified from a (completed) competition on Kaggle. You may download the dataset and play around my code :)
