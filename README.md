# Credit Risk Default Prediction

**MSc Data Science Project**

This project investigates whether customer repayment history and financial behaviour can be used to predict credit risk default using a machine learning approach.

The objective is to build a clear and explainable model that can detect customers at risk of default.

---

## Dataset

The analysis uses the **Default of Credit Card Clients** dataset from the **UCI Machine Learning Repository**.

It contains data for 30,000 customers, including:

* Credit limit
* Repayment status over six months
* Bill statement amounts
* Previous payment amounts
* Demographic information
* Target: default payment next month

---

## How to Run the Project (Google Colab)

**1. Download the notebook (.ipynb)**
Save it on your computer.

**2. Open Google Colab**
[https://colab.research.google.com/](https://colab.research.google.com/)

**3. Upload the notebook**
Click **Upload** and select the notebook file.

**4. Upload the dataset (Excel file)**
Download `default of credit card clients.xls` from UCI.
In Colab, click the folder icon → Upload the file into `/sample_data`.

**5. Install required libraries**

```python
!pip install shap lime imbalanced-learn
```

**6. Load the dataset**

```python
import pandas as pd
df = pd.read_excel("default of credit card clients.xls", header=1)
```

**7. Run the code**

Click **Runtime → Run all**

