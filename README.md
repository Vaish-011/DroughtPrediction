# 🌍 Climate Analysis and Drought Risk Prediction

This project presents an end-to-end data science pipeline for analyzing climate trends, detecting temperature anomalies, and predicting drought risk using machine learning.

---

## 📂 Project Structure

- `climate.ipynb` → Main notebook containing full analysis and model pipeline

---

## 🚀 Features & Workflow

The notebook performs the following tasks:

1. **Data Loading**
   - Loads global temperature data (city-level)
   - Loads drought meteorological and soil data

2. **Data Preprocessing**
   - Date parsing and feature extraction (year)
   - Handling missing values
   - Selecting relevant numerical features

3. **Climate Trend Analysis**
   - Computes yearly average temperatures
   - Visualizes long-term temperature trends

4. **Anomaly Detection**
   - Uses **Isolation Forest** to detect abnormal temperature patterns

5. **Drought Prediction**
   - Builds a **Random Forest Classifier**
   - Predicts drought risk based on weather and soil features

6. **Model Evaluation**
   - Uses classification metrics:
     - Accuracy
     - Precision
     - Recall
     - F1-score

7. **Feature Importance**
   - Visualizes most important features influencing drought prediction

8. **Early Warning System**
   - Simple rule-based function to classify drought risk levels

---

## 📊 Datasets Used

### 🌍 Climate Data
- `GlobalLandTemperaturesByCity.csv`
- `GlobalTemperatures.csv`

### 🌵 Drought Data
- `train_timeseries.csv`
- `validation_timeseries.csv`
- `test_timeseries.csv`
- `soil_data.csv`

---

## 📁 Data Paths (Kaggle)

The notebook uses Kaggle input paths such as:

```

https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data
https://www.kaggle.com/datasets/cdminix/us-drought-meteorological-data

````

### ⚠️ Running Locally
If running outside Kaggle, update file paths to your local dataset directories.

---

## ⚙️ Requirements

### 🐍 Python Version
- Python 3.9+

### 📦 Libraries
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

### 🔧 Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
````

---

## ▶️ How to Run

1. Open `climate.ipynb` in Jupyter Notebook / VS Code
2. Ensure datasets are correctly linked
3. Run all cells sequentially
4. Analyze outputs:

   * Graphs
   * Anomaly detection
   * Model performance

---

---

## 🎯 Project Objective

To leverage climate and meteorological data for:

* Detecting abnormal temperature patterns
* Predicting drought conditions
* Providing early warning insights

---

## 🧠 Technologies Used

* Machine Learning (Random Forest, Isolation Forest)
* Data Analysis (Pandas, NumPy)
* Visualization (Matplotlib, Seaborn)

