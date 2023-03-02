# Challenge-12
Credit risk anaylzer
# history 50 > terminal_history.txt

# Credit risk analyzer
Analyzes the creditworthiness of borrowers, by looking into key information points such as debt-to-income, loan size, and total 
  debt.
## Technologies

import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
---

## Installation Guide
run program using jupyterlab/google collab

---

## Usage
This analysis identifies the creditworthiness of borrowers, by using various techniques to train and   
  evaluate models with imbalanced classes.


* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data 

*Logisticregression vs Randomsampler*
![Logistic regression score](https://github.com/MxP05/Challenge-12/blob/main/Resources/image/logisticregression%20score.png?raw=true)
![Random resampler score](https://github.com/MxP05/Challenge-12/blob/main/Resources/image/Resampled%20score.png?raw=true)
---

## Contributors

MxP05

---

## License
Use to analyze the company's financial and user data.