# Crop Recommendation System

This project uses a *Machine Learning model* to recommend the most suitable crop to grow based on environmental conditions like soil nutrients, temperature, humidity, pH, and rainfall.

---

## Problem Statement

Farmers often struggle to decide the best crop to grow due to lack of guidance or unpredictable environmental factors. This system assists them by suggesting the most appropriate crop using data-driven predictions.

---

## Features Used

- *N* – Nitrogen content in soil
- *P* – Phosphorus content in soil
- *K* – Potassium content in soil
- *Temperature* – in Celsius
- *Humidity* – in percentage
- *pH* – pH value of the soil
- *Rainfall* – in mm

---

##  Model Used

- *Random Forest Classifier*
- High accuracy and robust performance on tabular data
- Evaluated using *confusion matrix, **classification report, and **accuracy score*

---

##  Dataset

- Source: [Kaggle – Crop Recommendation Dataset](https://www.kaggle.com/datasets/madhuraatmarambhagat/crop-recommendation-dataset)
- Format: CSV file containing 2200+ rows with labeled crop data

---

##  How to Use

1. Clone the repository
2. Install required packages:

```bash
pip install -r requirements.txt
