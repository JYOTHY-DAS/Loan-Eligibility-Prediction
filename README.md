# Loan Eligibility Prediction

## Overview
This repository contains the implementation of the **Loan Eligibility Prediction** project, which was developed as part of an **Analytics Vidhya hackathon**. The objective of the project is to predict loan eligibility based on applicant details using machine learning techniques.

## Dataset
The dataset consists of various attributes related to loan applicants, such as:
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Marital Status
- Education Level
- Property Area
- Dependents
- Self-Employment Status

## Project Structure
```
📂 Loan_Eligibility_Prediction
│── 📂 data/                    # Contains dataset files
│   │── 📂 raw/                 # Raw dataset files
│   │── 📂 processed/           # Processed dataset files
│── 📂 notebooks/               # Jupyter notebooks for data analysis and model building
│── 📂 report/                  # Contains reports and figures
│   │── 📂 figures/             # Visualizations and plots
│── 📄 results.txt              # Score obtained in Analytics Vidhya
│── 📄 requirements.txt         # Dependencies required for the project
│── 📄 README.md                # Project documentation (this file)
```

## Approach
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering
   
2. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Identifying correlations
   
3. **Model Selection & Training**
   - Models used:
     - **Logistic Regression**
     - **Naïve Bayes (GaussianNB)**
     - **K-Nearest Neighbors (KNN)**
     - **Random Forest Classifier**
   - Features were selected after preprocessing
   - Models were trained on the dataset and evaluated
   
4. **Prediction & Output Formatting**
   - Predictions were made on test data
   - Output was converted from `1` and `0` to `Y` and `N`
   - Results were saved as a `.csv` file
   
5. **Model Evaluation & Submission**
   - Final model performance tested on validation data
   - Predictions submitted to Analytics Vidhya

## Results
The final score obtained in the **Analytics Vidhya hackathon** is documented in `results.txt`.

## Requirements
To run the project, install the necessary dependencies using:
```bash
pip install -r requirements.txt
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Loan_Eligibility_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Loan_Eligibility_Prediction
   ```
3. Run the notebook in `notebooks/` to explore the dataset and train models.

## Acknowledgments
- **Analytics Vidhya** for providing the dataset and hackathon platform.
- Open-source ML libraries such as Scikit-Learn, Pandas, and XGBoost.

## Contact
For any queries or discussions, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/Jyothy-Das) or email me at `jyothydas11@gmail.com`.

