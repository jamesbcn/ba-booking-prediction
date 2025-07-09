## 🧠 British Airways Booking Completion Prediction

This repository contains a machine learning pipeline to predict whether a flight booking will be completed or not, based on customer and booking characteristics.

The project addresses significant class imbalance (85% incomplete vs. 15% complete bookings) and applies advanced modeling techniques (XGBoost, Random Forest, SMOTE) alongside preprocessing and feature engineering.

---

## 📁 Project Structure

```
ba-booking-prediction/
├── data/ # Raw and preprocessed datasets
├── ba_bookings.ipynb # Main notebook with EDA, preprocessing, modeling
├── requirements.txt # Project dependencies
└── README.md # Project overview and instructions
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/jamesbcn/ba-booking-prediction.git
cd ba-booking-prediction
```

### 2. Create and activate a virtual environment (optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open the Jupyter notebook `ba_bookings.ipynb` to explore the EDA, preprocessing, and modeling steps.

---

## 📌 Future Work

* Improve binning strategy for `flight_duration`
* Explore additional feature engineering
* Evaluate alternative resampling techniques beyond SMOTE
* Integrate statistical validation for synthetic data impact