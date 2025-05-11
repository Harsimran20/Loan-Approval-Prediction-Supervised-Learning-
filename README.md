
# 🏦 Loan Approval Prediction

This project predicts whether a loan application will be approved based on applicant details using a supervised machine learning model.

## 📊 Dataset

- **Name:** Loan Prediction Dataset (Simulated)
- **Size:** 100 Records
- **Features:**
  - Gender
  - Married
  - Dependents
  - Education
  - Self_Employed
  - ApplicantIncome
  - CoapplicantIncome
  - LoanAmount
  - Loan_Amount_Term
  - Credit_History
  - Property_Area
  - Loan_Status (Target Variable)

## 🎯 Objective

To build a classification model that can predict the loan approval status (`Loan_Status`) as **Approved (Y)** or **Rejected (N)**.

---

## ⚙️ Project Structure

```bash
loan-prediction/
├── loan_prediction.ipynb     # Jupyter Notebook with full workflow
├── loan_prediction_dataset.csv  # CSV dataset file
├── README.md                 # Project documentation
```

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 🔍 Workflow Steps

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Encoding Categorical Variables
5. Splitting the Dataset
6. Model Training (Logistic Regression, Random Forest, etc.)
7. Model Evaluation
8. Prediction on Test Set

---

## 📈 Sample Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 78%     |
| Random Forest       | 84%     |

*Note: Results will vary based on preprocessing and random state.*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/loan-prediction.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook loan_prediction.ipynb
   ```

3. Run all cells to see the workflow in action.

---

## 📄 License

This project is licensed under the MIT License.
