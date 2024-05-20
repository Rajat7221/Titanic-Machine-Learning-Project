# Titanic Survival Prediction
## Description
This project uses the Titanic dataset from Kaggle to predict whether or not a passenger survived based on attributes such as their age, sex, passenger class, and where they embarked. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and model training using Support Vector Classifier (SVC) and RandomForest Classifier.
## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Rajat7221/Titanic-Machine-Learning-Project.git
   cd Titanic-Machine-Learning-Project
2. python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. pip install -r requirements.txt

## Usage
```markdown
## Usage
1. Ensure you have installed all the dependencies.
2. Navigate to the project directory on your local machine.
2. Run the Jupyter notebook to see the analysis and results:
   ```bash
   jupyter notebook notebooks\predicting_passenger_survival_in_titanic_shipwreck_474.ipynb
3. Replace the "TITANIC_PATH" with the data sources in the notebook.


#### Project Structure
```markdown
## Project Structure
- `Data/`: Contains the dataset files.
  - `train.csv`
  - `test.csv`
- `notebooks/`: Contains the Jupyter notebook with the analysis and model training.
  - `predicting_passenger_survival_in_titanic_shipwreck_474.ipynb`
- `README.md`: Project overview and instructions.
- `requirements.txt`: List of dependencies required to run the project.

## Results
The project uses two machine learning models: Support Vector Classifier (SVC) and RandomForest Classifier. Below are the accuracy results:
- SVC Accuracy: 73.29%
- RandomForest Accuracy: 81.26%




   
   

