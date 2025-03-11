# ml-01

## Introduction
The California housing dataset, derived from the 1990 U.S. Census, provides valuable insights into the state's real estate market by incorporating key economic and demographic variables. Collected through surveys and interviews, census data serves as a crucial resource for analyzing housing trends, though it is subject to limitations such as sampling errors and undercounting, particularly in diverse and densely populated areas like California. By examining factors such as median home values, income levels, and household sizes, this dataset enables predictive modeling to assess affordability, regional disparities, and broader socioeconomic influences. However, challenges such as income inequality, housing shortages, and gentrification may be hidden within the data, requiring careful interpretation to uncover the full scope of California’s housing market dynamics. <br>

## Overview
Businesses and organizations often need to understand the relationships between different factors to make better decisions.
For example, a company may want to predict the fuel efficiency of a car based on its weight and engine size or estimate home prices based on square footage and location.
Regression analysis helps identify and quantify these relationships between numerical features, providing insights that can be used for forecasting and decision-making. <br>

This project demonstrates your ability to apply regression modeling techniques to a real-world dataset. You will:
- Load and explore a dataset.
- Choose and justify features for predicting a target variable.
- Train a regression model and evaluate performance.
- Compare multiple regression approaches.
- Document your work in a structured Jupyter Notebook.

## Dataset 
Housing Prices Dataset (Predict home values based on features like square footage and location)  
- We use the built-in dataset from scikit-learn:  
   - `from sklearn.datasets import fetch_california_housing`  
- Additional dataset available on Kaggle:  
   - [Kaggle Housing Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  

## Python Library for Machine Learning: scikit-learn
We use scikit-learn, built on NumPy, SciPy, and matplotlib
   - Read more at <https://scikit-learn.org/>
   - Scikit-learn supports classification, regression, and clustering.
   - This project applies regression.

**Important:** Use a 2-step installation to avoid timeouts and partial installs:  
1. **First Install:** Install from `requirements.txt` with `scikit-learn` commented out.  
2. **Second Install:** Uncomment `scikit-learn` and rerun the install command.

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

Start your notebook professionally with:
- a single top-level title
- your name (or alias)
- the date
- a brief introduction that describes the problem and the dataset.
- Import the external Python libraries used (e.g., pandas, numpy, matplotlib, seaborn, sklearn, etc.)

Present your work in clearly numbered second-level and third-level headings

### Section 1. Load and Explore the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

Analysis: What do you notice about the dataset? Are there any data issues?

### Section 2. Visualize Feature Distributions
- 2.1 Create histograms, boxplots, and scatterplots.
- 2.2 Identify patterns or anomalies in feature distributions.

Analysis: What patterns or anomalies do you see? Do any features stand out?

### Section 3. Feature Selection and Justification
- 3.1 Choose two input features for predicting the target.
- 3.2 Justify your selection with reasoning.

Analysis: Why did you choose these features? How might they impact predictions?

### Section 4. Train a Linear Regression Model
- 4.1 Define X (features) and y (target).
- 4.2 Train a Linear Regression model using Scikit-Learn.
- 4.3 Report R^2, MAE, RMSE.

Analysis: How well did the model perform? Any surprises in the results?

See [EXAMPLE_ANALYSIS](./docs/EXAMPLE_ANALYSIS.md) for more.

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

- [ ] Useful .gitignore (that keeps .venv out of GitHub)
- [ ] Professional Jupyter Notebook with numbered sections   
- [ ] Useful README.md
- [ ] Useful requirements.txt

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

## Version History
- L1 - S2.1 <br>
- L1 - S1.1 <br>
- L1 0 Initial 0.0 - 0.5 Setup of Framework <br>
## Test History  
- Test 1 <br>