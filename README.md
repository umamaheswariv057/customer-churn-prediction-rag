# Customer Churn Prediction and Technician RAG Workflow

## Project Overview

This project focuses on predicting customer churn using machine learning
and defining a Technician RAG (Retrieval-Augmented Generation) workflow.

The customer churn prediction system analyzes customer information and
predicts whether a customer is likely to churn.

The Technician RAG workflow retrieves relevant technical information
from a knowledge base based on customer issues.

## Objectives

- Analyze customer churn data
- Perform data cleaning and preprocessing
- Perform exploratory data analysis
- Visualize customer churn patterns
- Build a machine learning model for churn prediction
- Evaluate the model using classification metrics
- Define a Technician RAG workflow
- Retrieve relevant technical solutions from a knowledge base

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Retrieval-Augmented Generation (RAG)

## Machine Learning Model

Logistic Regression is used to predict customer churn.

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Technician RAG Workflow

The workflow follows:

Customer Issue
↓
Query Processing
↓
Knowledge Base Search
↓
Relevant Information Retrieval
↓
Technician
↓
Customer Support

## Dataset

The project uses the IBM Telco Customer Churn dataset.

## Project Structure

Customer_Churn_Prediction_Technician_RAG.ipynb
README.md

## Conclusion

The project demonstrates how machine learning can be used to predict
customer churn and how a Technician RAG workflow can help retrieve
relevant technical information for customer support.
## Day 3 – Churn Indicators and Technical Troubleshooting

### Objective

Connect customer churn indicators with relevant technical troubleshooting information to support technician decision-making.

### Work Completed

* Identified important customer churn indicators.
* Connected churn indicators with technical troubleshooting information.
* Created a technician troubleshooting knowledge mapping.
* Developed a technician recommendation function.
* Tested the workflow using sample customer technical issues.
* Defined the workflow from churn indicator identification to technician support.

### Workflow

Customer Data
↓
Churn Indicator Identification
↓
Technical Issue Detection
↓
Retrieve Relevant Troubleshooting Information
↓
Technician Recommendation
↓
Customer Support

### Technologies Used

* Python
* Pandas
* Google Colab
* Machine Learning
* Data Analysis
* Technician RAG Workflow

### Day 3 Outcome

The system connects potential churn-related signals with relevant technical troubleshooting guidance, helping technicians access appropriate information when supporting customers.

## Day 4 – Technician Knowledge Base

### Objective

Build a structured technician knowledge base containing common customer technical issues and their corresponding troubleshooting information.

### Work Completed

* Created a structured technician knowledge base.
* Added technical issue categories.
* Added common symptoms for each issue.
* Added troubleshooting steps.
* Added recommended solutions.
* Added priority levels.
* Developed a search function to retrieve relevant technical information.
* Tested the knowledge base using Wi-Fi and Internet-related queries.

### Knowledge Base Fields

* Issue
* Category
* Symptoms
* Troubleshooting
* Solution
* Priority

### Workflow

Customer Technical Issue
↓
Search Knowledge Base
↓
Identify Relevant Information
↓
Retrieve Troubleshooting Steps
↓
Provide Recommended Solution
↓
Technician Support

### Outcome

A searchable technician knowledge base was developed and can be used as the retrieval source for the Technician RAG workflow.


## Day 5 – Prompt Design for Troubleshooting and Service Analysis

### Objective

Design structured prompts for troubleshooting customer technical issues and analyzing customer service information.

### Work Completed

* Designed a troubleshooting prompt for technical issues.
* Designed a service analysis prompt using customer information.
* Included churn indicators, service type, tenure, and monthly charges.
* Connected relevant technician knowledge base information with the prompts.
* Created a combined technician prompt for troubleshooting and service analysis.
* Tested the prompts using sample customer information.

### Prompt Workflow

Customer Information
↓
Technical Issue and Symptoms
↓
Churn Indicators
↓
Knowledge Base Information
↓
Structured Technician Prompt
↓
Troubleshooting and Service Analysis
↓
Technician Recommendation

### Outcome

Structured prompts were developed to help technicians analyze customer technical issues and service-related information. The prompts can also serve as input templates for a future Technician RAG system.

