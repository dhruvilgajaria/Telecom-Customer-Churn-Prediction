# Telecom Customer Churn Prediction
This project uses a dataset from the UCI Machine Learning Repository to build a customer churn prediction model using an artificial neural network (ANN). The dataset contains information on a telecom company's customers over a 12-month period, including call failures, frequency of SMS, number of complaints, subscription length, age group, charge amount, type of service, seconds of use, status, frequency of use, and customer value.

The project's Python code uses Keras, a high-level neural networks API, to build and train a deep learning model to predict customer churn. The model's performance is evaluated using precision, recall, and accuracy metrics, as well as a confusion matrix and classification report.

## Dataset Information
The dataset contains 3150 rows of data, each representing a customer, with 13 columns of attributes. All attributes except for the churn attribute are aggregated data from the first nine months, with churn labels representing the state of customers at the end of 12 months. The planning gap is three months.

The dataset was randomly collected from an Iranian telecom company's database, with attribution to Ruholla Jafari-Marandi of the Industrial and Manufacturing Engineering Department at Cal Poly, San Luis Obispo, CA, USA.

## Requirements
To run the Python code in this project, you will need to have the following packages installed:

pandas, numpy, sklearn, keras, matplotlib, tensorflow, seaborn

## Usage
You can run the code in 'churn_prediction.ipnyb' to train the ANN model and generate predictions on the dataset. You can also modify the code to experiment with different hyperparameters and model architectures.

## Conclusion
Overall, this project demonstrates the use of an artificial neural network to predict customer churn in a telecom company's customer base. The code and documentation in this repo can be used as a starting point for similar churn prediction projects.
