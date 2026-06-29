7006SCN – Machine Learning and Big Data

NYC Yellow Taxi Tip Prediction using PySpark

Module Information

* Module: 7006SCN – Machine Learning and Big Data
* Assessment: Applied Core Assessment
* Problem Type: Binary Classification
* Framework: Apache Spark (PySpark)

⸻

Project Overview

This project develops a distributed machine learning pipeline using Apache Spark to predict whether a New York City taxi trip will receive a high tip (greater than 20% of the fare).

The project demonstrates the complete machine learning lifecycle, including:

* Big Data ingestion
* Data engineering and preprocessing
* Feature engineering
* Machine learning model development
* Distributed computing optimisation
* Model evaluation
* Tableau dashboard creation

⸻

Dataset

Dataset Name

NYC Yellow Taxi Trip Records

Source

NYC Taxi & Limousine Commission (TLC)

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Files Used

* yellow_tripdata_2023-01.parquet
* yellow_tripdata_2023-02.parquet
* yellow_tripdata_2023-03.parquet
* yellow_tripdata_2023-04.parquet

Dataset Summary

Item	Value
Format	Parquet
Raw Records	12,672,737
Features	19
Data Type	Structured Big Data
Licence	Public Domain

⸻

Project Structure

7006SCN2526MAYJUL/
README.md
Task1.ipynb
Task2.ipynb
Task3.ipynb
Task4.ipynb
Task5.ipynb
Task6.ipynb
outputs/
tableau_exports/
data/

⸻

Machine Learning Models

The following four models were implemented and evaluated:

1. Logistic Regression
2. Random Forest
3. Gradient Boosted Trees (GBT)
4. Linear Support Vector Machine (Linear SVM)

⸻

Big Data Characteristics (Five V’s)

Characteristic	Evidence
Volume	12.67 million taxi trips
Velocity	Continuous monthly taxi trip collection
Variety	Numeric, categorical, datetime and location features
Veracity	Missing values analysed and cleaned
Value	Predicting customer tipping behaviour for revenue optimisation

⸻

Visual Outputs

The repository contains:

* Confusion Matrices
* ROC Curves
* Precision-Recall Curves
* SHAP Feature Importance
* Tableau Dashboard Export Files

⸻

Software Used

* Python
* Apache Spark (PySpark)
* Pandas
* NumPy
* Scikit-learn
* SHAP
* Matplotlib
* Tableau Public
* Jupyter Notebook

⸻

Running the Project

1. Install Python dependencies

pip install pyspark pandas numpy matplotlib scikit-learn shap

2. Download the four NYC Taxi Parquet files listed above.
3. Place them inside the data/ directory.
4. Execute the notebooks in order:

* Task1.ipynb
* Task2.ipynb
* Task3.ipynb
* Task4.ipynb
* Task5.ipynb
* Task6.ipynb

⸻

Repository Contents

* Source notebooks
* Generated figures
* Tableau CSV exports

The original Parquet dataset is not included because of GitHub file size limitations.

⸻

Tableau Dashboard

Tableau Public Link:

(Add your Tableau Public URL after publishing.)

⸻

Author

Prepared as part of the 7006SCN – Machine Learning and Big Data assessment.
