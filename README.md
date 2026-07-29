# ✈️ Flight Price EDA & Data Preprocessing

A data preprocessing project that prepares flight price data for machine learning by performing data cleaning, feature engineering, and categorical feature encoding.

---

## 📌 Project Overview

This project focuses on transforming raw flight booking data into a clean and structured dataset suitable for machine learning models.

The preprocessing pipeline includes:

- Data cleaning
- Missing value handling
- Feature engineering
- Date and time extraction
- Duration transformation
- Categorical feature encoding
- Removal of irrelevant features

---

## 📂 Dataset

The dataset contains information about flight bookings, including:

- Airline
- Source
- Destination
- Date of Journey
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Ticket Price

---

## ⚙️ Data Preprocessing Steps

### 1. Data Cleaning
- Removed missing values
- Checked data types
- Removed unnecessary columns

### 2. Feature Engineering
- Extracted journey day and month
- Extracted departure hour and minute
- Extracted arrival hour and minute
- Converted flight duration into numerical values

### 3. Categorical Encoding
Applied One-Hot Encoding to categorical variables such as:
- Airline
- Source
- Destination

### 4. Final Dataset
Generated a clean dataset ready for machine learning model training.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Flight-Price-EDA/
│
├── data/
│   ├── flight_price.xlsx
│   └── flight_price_processed.csv
│
├── notebooks/
│   └── flight_price_eda_preprocessing.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/Flight-Price-EDA.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📈 Future Improvements

- Train Machine Learning models
- Compare regression algorithms
- Hyperparameter tuning
- Model evaluation
- Deploy the model as a web application

---

## 👤 Author

**Pranav VVS**

Civil Engineering Undergraduate at NIT Warangal

Learning Data Analytics and Machine Learning.