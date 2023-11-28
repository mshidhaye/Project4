# Breast Cancer Diagnosis ![ribbon](ribbon.png)
--------------------------------------
Tumor testing
### Intro
In this project, we were tasked with using Machine Learning to make predictions on a chosen dataset. Our dataset is based on tumors tested for breast cancer and measurements related to those tumors, such as the average and worse smoothness, radius, perimeter. The dataset was chosen as it advises if tumor was malignant (cancerous) or benign  (non-cancerous).

### Method
Given the systems available, our process was as follows:
- Load dataset into DataFrame using Python/Pandas
- Clean-up the dataset to a readable format
- Use Python/Pandas to train and test the Logistic Regression machine learning model
- Ensure model has appropriate accuracy score
- Use Kerastuner library to run trials and optimize the model, with hopes of increasing accuracy 
- Compare output “classification report” and accuracy scores
- Visualize data using Tableau

### Results

#### Classification Report for Worst (measures) DataFrame
![Class_report](class_report_worse.png)

** Accuracy score: Worse Measures
![acc_worse](acc_worse.png)

#### Classification Report for Mean (measures) DataFrame
![M_Class_report](class_report_mean.png)

** Accuracy score: Worse Measures
![acc_mean](acc_mean.png)