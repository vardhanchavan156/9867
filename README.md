<h1 align="center"> Term Deposit Prediction Project</h1>

<div align="center">
 <img src="https://github.com/user-attachments/assets/2c7165fd-2e40-499d-bbec-c3f134f170e9" width="300">

</div>

## Introduction

Term Deposit Prediction is an important use case in the banking industry. Term deposits represent a significant source of income for banks, and efficient targeting of potential customers for term deposits is vital to optimize marketing efforts. This project focuses on utilizing data from direct marketing campaigns to predict whether a client will subscribe to a term deposit, enabling the bank to target the right audience and reduce costs associated with telephonic marketing campaigns.

## Key Features

- Analyze bank marketing campaign data to identify patterns and insights.
- Use predictive modeling techniques to forecast customer behavior.
- Optimize targeting strategies for telephonic marketing campaigns.
- Improve marketing efficiency and reduce unnecessary expenses.

## Dataset

The dataset is derived from the direct marketing campaigns of a Portuguese banking institution. The data includes client details, campaign information, and the final outcome (whether the client subscribed to a term deposit).

### **Dataset Files**

- **train.csv**: Contains 40,000 rows and 17 columns, including the target variable `y`.
- **test.csv**: Contains 5,211 rows and 16 columns, excluding the target variable `y`.

### **Column Descriptions**

#### **Bank Client Data:**
1. **age**: Age of the client (numeric).
2. **job**: Type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services").
3. **marital**: Marital status (categorical: "married", "divorced", "single").
4. **Education**: Level of education (categorical: "unknown", "secondary", "primary", "tertiary").
5. **default**: Has credit in default? (binary: "yes", "no").
6. **balance**: Average yearly balance in euros (numeric).
7. **housing**: Has housing loan? (binary: "yes", "no").
8. **loan**: Has personal loan? (binary: "yes", "no").

#### **Related to the Last Contact of the Current Campaign:**
9. **contact**: Contact communication type (categorical: "unknown", "telephone", "cellular").
10. **day**: Last contact day of the month (numeric).
11. **month**: Last contact month of the year (categorical: "jan", "feb", "mar", ..., "nov", "dec").
12. **duration**: Last contact duration in seconds (numeric).

#### **Other Attributes:**
13. **campaign**: Number of contacts performed during this campaign (numeric).
14. **pdays**: Days since last contact from a previous campaign (numeric, -1 means no previous contact).
15. **previous**: Number of contacts performed before this campaign (numeric).
16. **poutcome**: Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success").

#### **Target Variable:**
17. **y**: Indicates if the client subscribed to a term deposit (binary: "yes", "no").

## File Structure

```
project-directory/
├── train.csv
├── test.csv
├── Train_data_EDA.ipynb
├── Test_data_EDA.ipynb
├── model_training.ipynb
├── requirements.txt
├── README.md
└── outputs/
    ├── predictions.csv
    └── presentation.pptx
```

## Technology Stack

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization Tools**: Power BI, Excel
- **Deployment Platform**: Streamlit
- **Version Control**: Git/GitHub

## Screenshots
# Distribution of Numerical Columns in Subplots
![image](https://github.com/user-attachments/assets/c60285af-ea5a-440a-b2b2-2d2b3c2993e8)
# Visualization for Categorical Columns
![image](https://github.com/user-attachments/assets/a04ba202-805e-4950-bd0e-1bba7b0c0a3c)
# Count the values for the job column
![image](https://github.com/user-attachments/assets/2927128a-cfe6-4c1d-b1d6-1344f8a33d0a)
# PowerBI Dashboard
![image](https://github.com/vardhanchavan156/9867/blob/cf662c32fd559ccf7560632ab3e9b1423696167e/Power%20BI%20Dashboard%20Home%20Page.png)

![image](https://github.com/vardhanchavan156/9867/blob/922af45a57b74d84e594763910c36656d203d081/Power%20BI%20Dashboard%20Overview%20Page.png)

# Hackathon Presentation
[Link Text](https://drive.google.com/file/d/1PAcdZzQTfvoAkApopQKouyTdMkMB7kFl/view?usp=drive_link)

## 📋 Authors
👷Contributors :
- Vardhan Chavan
- Ashish Dabas
- Tejas Patil


## Feedback and Acknowledgments

We thank the mentors and peers who provided valuable feedback during the development of this project. Special thanks to the dataset contributors and the platform hosting this project.

## Future Enhancements

1. Incorporate more advanced machine learning algorithms for improved predictions.
2. Add a feature for real-time prediction using live customer data.
3. Expand the dataset to include additional customer demographic and behavioral attributes.
4. Develop an API for seamless integration with the bank’s CRM system.

