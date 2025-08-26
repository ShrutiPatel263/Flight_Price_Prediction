# Flight Price Prediction – Data Preprocessing

This repository contains preprocessing steps and feature engineering for flight price prediction, focusing on extracting and transforming key datetime features and flight durations to prepare the data for modeling.

---

##  Contents

- `Flight_Price_Prediction.ipynb` – Jupyter notebook showcasing loading data, cleaning, and feature engineering (e.g., date decomposition, duration parsing, time-based features).
- `Data_Train.xlsx` & `Test_set.xlsx` – Example datasets used for developing and validating the preprocessing pipeline.

---

##  Feature Engineering Highlights

- **Date components**: Extracted day, month, and year from departure dates.
- **Time components**: Parsed and decomposed departure and arrival times into hours and minutes.
- **Duration handling**: Split duration into hours and minutes and addressed missing or invalid values safely.
- **Cleanliness-first approach**: Ensured numeric-type consistency and handled `NaN` values properly.
- **Structured Features**: Prepared the dataset for seamless integration with downstream regression or machine learning models.

---
