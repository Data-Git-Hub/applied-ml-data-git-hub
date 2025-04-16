# Lab05

[Predicting Red Wine Quality Using Ensemble Machine Learning Models](https://github.com/Data-Git-Hub/applied-ml-data-git-hub/blob/main/lab05/ensemble-data-git-hub.ipynb)

## Introduction
This project explores the application of ensemble machine learning methods to predict the quality of red wine based on its physicochemical characteristics. Ensemble models are designed to combine the strengths of multiple individual models, resulting in improved accuracy, robustness, and generalization. The analysis focuses on evaluating the performance of several ensemble techniques—including Random Forests, AdaBoost, and Voting Classifiers—using classification metrics such as accuracy, precision, recall, and F1 score. By comparing these models, the project aims to identify which methods are most effective in predicting categorical wine quality levels. <br>

## Dataset 
The dataset used in this project is the Wine Quality Dataset available from the UCI Machine Learning Repository. It contains physicochemical measurements for red wine samples, including variables such as acidity, sugar content, pH, and alcohol percentage. Each sample is rated with a quality score ranging from 0 to 10, based on sensory evaluations conducted by wine tasters. For the purposes of classification, these scores are grouped into three categories: low, medium, and high quality. <br>

The dataset was originally published by: P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis, in the article titled
Modeling wine preferences by data mining from physicochemical properties,
published in Decision Support Systems, Elsevier, 47(4), pages 547–553, 2009. <br>

#### [Wine Quality Dataset made available by the UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
---

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 


```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```
### Remove "#" TBD. from requirements.txt

```shell
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### Remove "#" TBD. from requirements.txt

```zsh
py -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

## Professional Python Setup and Workflow
We follow professional Python practices. 
Full instructions are available at <https://github.com/denisecase/pro-analytics-01/>. 
A concise version is provided at [WORKFLOW_GUIDE.md](./docs/WORKFLOW_GUIDE.md)

**Important:** VS Code + Pylance may fail to recognize installed packages in Jupyter notebooks.  
See the above guides for troubleshooting and solutions.  

---

### Introduction

### Imports

### Section 1. Load and Inspect the Data

### Section 2. Prepare the Data

### Section 3. Feature Selection and Justification

### Section 4. Split the Data into Train and Test

### Section 5. Evaluate Model Performance

### Section 6. Compare Results 

### Section 7. Conclusions and Insights

### References:

---

## README.md (Required)

Include a professional README.md. Include:
- a personalized title
- an introduction to your project
- a clickable link to your notebook file.
- Instructions on how to set up your virtual environment and run your notebook locally.
   
If starting with an assignment README, remove the parts you do not need to present your project.
---

## Repository Checklist

Verify your repository contains:

- [x] Useful .gitignore (that keeps .venv out of GitHub)
- [x] Professional Jupyter Notebook with numbered sections   
- [x] Useful README.md
- [x] Useful requirements.txt

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

## Version History
- L5 Finl - 0.0 - Modify README.md
- L5 Sect - 7.2 - Modify ensemble-data-git-hub.ipynb Section 7, Add comparisons folder, final_model_comparison.csv
- L5 Sect - 7.1 - Modify ensemble-data-git-hub.ipynb Section 7
- L5 Sect - 7.0 - Modify requirements.txt, .gitignore
- L5 Sect - 6.2 - Modify ensemble-data-git-hub.ipynb Section 6
- L5 Sect - 6.1 - Modify ensemble-data-git-hub.ipynb Section 6 additional requirements to save to data folder
- L5 Sect - 6.0 - Modify ensemble-data-git-hub.ipynb Section 6
- L5 Sect - 5.0 - Modify ensemble-data-git-hub.ipynb Section 5, requirements.txt
- L5 Sect - 4.0 - Modify ensemble-data-git-hub.ipynb Section 4
- L5 Sect - 3.0 - Modify ensemble-data-git-hub.ipynb Section 3
- L5 Sect - 2.0 - Modify ensemble-data-git-hub.ipynb Section 2
- L5 Sect - 1.0 - Modify ensemble-data-git-hub.ipynb Section 1
- L5 Init - 0.7 - Modify ensemble-data-git-hub.ipynb, README.md
- L5 Init - 0.6 - Modify ensemble-data-git-hub.ipynb
- L5 Init - 0.5 - Add data folder, winequality-red.csv, Modify ensemble-data-git-hub.ipynb, README.md
- L5 Init - 0.4 - Add requirements.txt
- L5 Init - 0.3 - Add .gitignore
- L5 Init - 0.2 - Modify README.md 
- L5 Init - 0.1 - Add README.md
- L5 Init - 0.0 - Add ensemble-data-git-hub.ipynb <br>
## Test History  
- L5 Test - 0.1 - Modify README.md <br>
