# Support Ticket Classification Using Logistic Regression

## Project Overview

This project focuses on automatically classifying customer support tickets into predefined categories using Natural Language Processing (NLP) and Machine Learning techniques. The model helps support teams organize incoming tickets efficiently and reduce manual effort.


## Objective

To build a machine learning model that can analyze customer support ticket text and classify it into the appropriate category automatically.


## Tools & Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Matplotlib
- Jupyter Notebook


## Dataset

The dataset contains customer support tickets with the following columns:

- **Document** – Support ticket text
- **Topic_group** – Ticket category label


## Project Workflow

1. Load and explore the dataset
2. Select input and target columns
3. Split data into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train a Logistic Regression model
6. Evaluate model performance
7. Predict categories for new support tickets
8. Save the trained model


## Text Preprocessing

The ticket text is converted into numerical form using TF-IDF (Term Frequency–Inverse Document Frequency), which helps the machine learning model understand textual data.


## Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification tasks. It was trained on TF-IDF features extracted from the support ticket text.

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score

### Accuracy

**Model Accuracy: 85%** 


## Sample Prediction

### Input

Payment deducted but order not placed

### Output


Predicted Category: Billing


## Project Structure

Customer_Support_Ticket_Sales.ipynb
support_tickets.csv
ticket_classifier.pkl
vectorizer.pkl
README.md
requirements.txt


## Results

The Logistic Regression model successfully classified support tickets into their respective categories with good accuracy. The system can be used to automate ticket routing and improve customer support efficiency.


## Future Improvements

- Implement priority prediction (High/Medium/Low)
- Use advanced NLP techniques
- Deploy as a web application using Flask or Streamlit
- Experiment with other machine learning models


## Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be applied to automate customer support ticket classification. By using TF-IDF and Logistic Regression, the model effectively categorizes support tickets and assists support teams in handling customer requests more efficiently.