# Fingertips Project 8: Hotel Cancellations - Random Forest Classifier

for model in lis:
model=model()
print(f"Model name:{model}")
model.fit(x,y)
score=cross_val_score(model,x,y,cv=kf).mean()
print(f"score:->{score}")

## Overview

This project explores hotel booking cancellations using a machine learning classification approach.
It uses the Random Forest algorithm to predict whether a booking will be canceled or not, based on customer and booking features.

## Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature selection
- Model building using Random Forest Classifier
- Model evaluation using metrics like accuracy, confusion matrix, etc.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/jayant1345/Hotel_cancellation_predict_randomforest_classification
cd Hotel_cancellation_predict_randomforest_classification
```

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:

```bash
jupyter notebook fingertips_project8_hotel_can_randomforest.ipynb
```

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Dataset

The dataset used for this project typically includes customer demographics, booking information, and other features relevant to hotel reservations. It may be sourced from public datasets such as Kaggle or similar repositories.

## License

This project is licensed under the MIT License.

---

_Auto-generated from project notebook. Customize as needed._
