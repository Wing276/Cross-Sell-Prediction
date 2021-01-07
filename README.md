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
1. samplesubmission.csv:
	- This is a sample file to show the output format. Wrong format will lead to unkown result.

2. evaluate_1.macOS:
	- This is a command line tool to evaluate your result. F1-measure is used to measure your result.
	- Usage: Press "command + space" to open spotlight search and type in "terminal", then type in the following command in the terminal. You should replace
```./submission_1_method.csv``` with your own path to the submission_1_method.csv.
```bash
./evaluate_1.macOS ./submission_1_method.csv
```

3. evaluate_1.linux:
	- Usage: Press "ctrl + alt + t" to launch a terminal and input the following command.
```bash
./evaluate_1.linux ./submission_1_method.csv
```

4. evaluate_1.exe:
	- Usage: Press "command + r" and then type in "cmd" in the dialog box to launch a terminal. Then type in the command:
```bash
./evaluate_1.exe ./submission_1_method.csv
```

5. submission_1_dtree:
	- prediction result from a decision tree classifier
    
6. submission_1_randomforest: 
	- prediction result from a random forest classifier
    
7. Compare_code.ipynb: 
	- The file contains all the classifiers that I have tried, random forest performs the best

Remark: This is my school projects modified from a (completed) competition on Kaggle. You may download the dataset and play around my code :)
