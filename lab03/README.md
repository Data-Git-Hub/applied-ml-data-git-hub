# Lab03

## Introduction
The objective of the Wine dataset classification problem is to predict the origin of wines based on their chemical characteristics. By analyzing 13 different features, such as alcohol content, malic acid, ash, alkalinity of ash, magnesium content, and several others, we aim to classify a given wine into one of three possible cultivars. This classification task helps in understanding the relationship between the chemical properties and the quality or type of wine, serving as a basis for further research in oenology and machine learning. <br>

## Overview
Businesses and organizations must understand the relationships between different factors to make better decisions. <br>
For example, a company may want to predict a car's fuel efficiency based on its weight and engine size or estimate home prices based on square footage and location. <br>
Regression analysis helps identify and quantify these relationships between numerical features, providing insights that can be used for forecasting and decision-making. <br>

This project demonstrates your ability to apply regression modeling techniques to a real-world dataset. You will: <br>
- We use three common classification models in this lab. <br>

- Decision Tree Classifier (DT)

A Decision Tree splits data into smaller groups based on decision rules (like "is height greater than 150 cm?"). It’s like a flowchart, where each decision point leads to another question until a final classification is reached. <br>

Strengths: Easy to interpret and fast to train. <br>
Weaknesses: Can overfit if the tree becomes too complex. <br>

- Support Vector Machine (SVM) 

A Support Vector Machine tries to find the "best boundary" (a hyperplane) that separates data into classes. It works well with complex data and small datasets. <br>

Strengths: Effective when there is a clear margin of separation between classes. <br>
Weaknesses: Computationally expensive for large datasets. <br>

- Neural Network (NN)

A Neural Network is inspired by how human brains process information. It consists of layers of interconnected "neurons" that process input data and adjust based on feedback. <br>

Strengths: Can handle complex patterns and non-linear relationships.<br>
Weaknesses: Needs more data and tuning to avoid overfitting.<br>
When trying to classify data, using three (or more) models can help:<br>

Decision Trees illustrate how individual features contribute to classification.<br>
SVMs are good at finding complex boundaries.<br>
Neural Networks are good at learning patterns from complex data. <br>

## Dataset 
TBD. <br>.

---

## Professional Python Setup and Workflow
We follow professional Python practices. 
Full instructions are available at <https://github.com/denisecase/pro-analytics-01/>. 
A concise version is provided at [WORKFLOW_GUIDE.md](./docs/WORKFLOW_GUIDE.md)

**Important:** VS Code + Pylance may fail to recognize installed packages in Jupyter notebooks.  
See the above guides for troubleshooting and solutions.  

---

## Project Outline
Machine learning projects follow a structured approach.
We will use this approach throughout the course. 

1) Load and Explore the Data TBD.


Start your notebook professionally with:
- a single top-level title
- your name (or alias)
- the date
- a brief introduction that describes the problem and the dataset.
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.)

Present your work in clearly numbered second-level and third-level headings

### Section 1: Load and Explore the Data

### Section 2. Data Exploration and Preparation

### Section 3. Feature Selection and Justification

### Section 4. Train a Classification Model (Decision Tree)

### Section 5. Compare Alternative Models (SVC, NN)

### Section 6. Final Thoughts & Insights

### Section 7:

| Model Type           | Case   | Features Used            | Accuracy   | Precision   | Recall   | F1-Score   | Notes   |
|:---------------------|:-------|:-------------------------|:-----------|:------------|:---------|:-----------|:--------|
| Decision Tree        | Case 1 | alcohol                  | 55.56%     | 47.84%      | 50.95%   | 49.05%     | -       |
| Decision Tree        | Case 2 | color_intensity          | 63.89%     | 61.20%      | 60.95%   | 60.31%     | -       |
| Decision Tree        | Case 3 | alcohol, color_intensity | 72.22%     | 71.78%      | 70.00%   | 69.34%     | -       |
| SVM (RBF Kernel)     | Case 1 | alcohol                  | 66.67%     | 56.05%      | 62.06%   | 57.41%     | -       |
| SVM (RBF Kernel)     | Case 2 | color_intensity          | 75.00%     | 80.25%      | 72.62%   | 73.26%     | -       |
| SVM (RBF Kernel)     | Case 3 | alcohol, color_intensity | 83.33%     | 86.97%      | 80.56%   | 80.53%     | -       |
| SVM (Linear Kernel)  | Case 1 | alcohol                  | 66.67%     | 56.22%      | 62.06%   | 57.49%     | -       |
| SVM (Linear Kernel)  | Case 2 | color_intensity          | 72.22%     | 77.92%      | 69.84%   | 70.64%     | -       |
| SVM (Linear Kernel)  | Case 3 | alcohol, color_intensity | 88.89%     | 91.34%      | 87.22%   | 88.11%     | -       |
| SVM (Poly Kernel)    | Case 1 | alcohol                  | 69.44%     | 62.63%      | 65.40%   | 62.49%     | -       |
| SVM (Poly Kernel)    | Case 2 | color_intensity          | 72.22%     | 78.36%      | 69.84%   | 70.71%     | -       |
| SVM (Poly Kernel)    | Case 3 | alcohol, color_intensity | 88.89%     | 91.34%      | 87.22%   | 88.11%     | -       |
| SVM (Sigmoid Kernel) | Case 1 | alcohol                  | 38.89%     | 79.63%      | 33.33%   | 18.67%     | -       |
| SVM (Sigmoid Kernel) | Case 2 | color_intensity          | 2.78%      | 1.45%       | 2.38%    | 1.80%      | -       |
| SVM (Sigmoid Kernel) | Case 3 | alcohol, color_intensity | 38.89%     | 79.63%      | 33.33%   | 18.67%     | -       |
| Neural Network (MLP) | Case 1 | alcohol                  | 69.44%     | 62.63%      | 65.40%   | 62.49%     | -       |
| Neural Network (MLP) | Case 2 | color_intensity          | 75.00%     | 80.25%      | 72.62%   | 73.26%     | -       |
| Neural Network (MLP) | Case 3 | alcohol, color_intensity | 86.11%     | 86.92%      | 84.44%   | 85.02%     | -       |
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
- L3 Sect - 7.0
- L3 Sect - 6.0
- L3 Sect - 5.0
- L3 Sect - 4.2
- L3 Sect - 4.1
- L3 Sect - 4.0
- L3 Sect - 3.3
- L3 Sect - 3.1
- L3 Sect - 3.0
- L3 Sect - 2.0 <br>
- L3 Init - 0.1 <br> - add README.md shell
- L3 Init - 0.0 <br>
## Test History  
- <br>

