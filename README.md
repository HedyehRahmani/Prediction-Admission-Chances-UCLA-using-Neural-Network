
# Predicting Admission Chances at UCLA with Neural Networks

This repository provides a deep learning solution to predict admission chances at the University of California, Los Angeles (UCLA). The model uses a neural network to analyze various features related to a student's academic and extracurricular profile.

## Project Description

With the increasing number of students applying for higher education, universities are looking for ways to streamline their admission processes. This project leverages a neural network classification model to predict the likelihood of a student's admission based on their GRE score, TOEFL score, undergraduate GPA, and other relevant factors.

### Objective

The primary goal of this project is to accurately predict a student's chance of being admitted to UCLA, with a target accuracy of 90% or higher. This can help students understand their admission prospects and guide them in selecting appropriate universities.

### Role and Tasks

You are tasked with developing a neural network model to classify students based on their admission chances. The dataset includes several predictors like test scores, university ratings, and research experience, which you will use to train the model.

### Key Components

1. **Data Preparation:** Loading the dataset, handling missing values, and scaling features.
2. **Model Development:** Building and training a neural network using a suitable architecture.
3. **Evaluation:** Assessing model performance using accuracy, confusion matrix, and other metrics.

## Installation Instructions

To get started with this project, clone the repository and install the required packages:

```bash
git clone https://github.com/HedyehRahmani/Prediction-Admission-Chances-UCLA-using-Neural-Network.git
pip install -r requirements.txt
```

## Running the Model

After setting up the environment, you can execute the model by running:

```bash
python app.py
```

This script will preprocess the data, train the neural network, and output the prediction results along with the model's accuracy.

## Detailed Overview

### Neural Network Model

The neural network in this project is designed to process inputs like GRE scores, TOEFL scores, and other academic factors to predict a binary outcome—whether a student will be admitted or not. The model architecture and parameters are tuned to achieve optimal performance.

### Data Insights

The dataset includes variables such as:

- **GRE_Score:** Graduate Record Examination score
- **TOEFL_Score:** Test of English as a Foreign Language score
- **University_Rating:** Rating of the university where the undergraduate degree was earned
- **SOP:** Strength of Statement of Purpose
- **LOR:** Strength of Letters of Recommendation
- **CGPA:** Cumulative Grade Point Average
- **Research:** Whether the student has research experience
- **Admit_Chance:** The likelihood of admission (target variable)

## Contributions

If you wish to contribute to this project, please fork the repository and submit a pull request with your enhancements.
