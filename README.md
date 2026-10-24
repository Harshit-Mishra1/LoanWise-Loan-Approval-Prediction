# LoanWise – Loan Approval Prediction

A Python/Jupyter Notebook project exploring loan approval prediction with exploratory data analysis, missing-value handling, categorical encoding, feature scaling, feature engineering, and classification models.

## Models explored
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Tech stack
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project files

```text
LoanWise-Loan-Approval-Prediction/
├── loan_approval_data.csv
├── loan_Wise.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## Run locally

1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. (Recommended) create and activate a virtual environment.

### Windows PowerShell

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook
```

4. Open `loan_Wise.ipynb` in Jupyter, or open the notebook in VS Code and select the environment's Python kernel.
5. Run cells from top to bottom.

The notebook loads the CSV with a relative path, so keep `loan_approval_data.csv` beside `loan_Wise.ipynb` unless you update the path in the notebook.

## Dataset
The provided dataset file is `loan_approval_data.csv`. Add the original dataset source and license here if it came from a public source. Before publishing, confirm that you have permission to share the data and that it contains no real applicants' private or sensitive information.

## Notes
This repository is for learning and demonstration. It is not a validated lending system and should not be used as the sole basis for real-world credit decisions.

Before using results in a resume, verify that the notebook runs end-to-end and report only metrics actually produced by the analysis.
