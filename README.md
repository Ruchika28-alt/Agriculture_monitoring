# 🌾 Weather Prediction Model – ML for Agriculture 🚜🌤️

A powerful **machine learning system** tailored for **agricultural weather forecasting**, delivering accurate predictions for **temperature 🌡️** and **humidity 💧**—with **precision metrics** and **confidence ranges** to support smarter farming decisions.

---

## 📌 Overview  
This project utilizes **historical weather data** to train and evaluate a variety of ML models aimed at **predicting key weather parameters**. It's designed to empower **farmers and agritech developers** with:

- 🌡️ **Temperature Forecasts**  
- 💧 **Humidity Predictions**  
- 📊 **Performance & Precision Metrics**  
- 🎯 **Confidence Intervals for Better Decisions**

---

## ✨ Features

- 🛠️ Data preprocessing & feature engineering  
- 🤖 Model comparison across multiple algorithms  
- 🔧 Hyperparameter tuning for best performance  
- 📏 Precision-based evaluation metrics  
- 📈 Visualization of predictions & model performance  
- 🔍 Feature importance analysis  
- 🔮 Future weather prediction with confidence intervals  

---

## 🧰 Requirements

Make sure you have Python 3.6+ and the following libraries:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```
## Installation

```bash
git clone https://github.com/your-username/Agricultural_Monitoring_usnig_ML.git
cd CapstoneProject
pip install -r requirements.txt
```

## Usage

### Basic Usage

```python
python AgriculturalMonitoring.py --file finaldataset.xlsx --output results
```

### Parameters

- `--file`: Path to your Excel weather data file
- `--output`: Directory to save output visualizations and models (optional)

### Input Data Format

The script expects an Excel file with the following columns:
- Date
- Temperature (Max, Avg, Min)
- Dew Point (Max, Avg, Min)
- Humidity (Max, Avg, Min)
- Wind Speed (Max, Avg, Min)
- Pressure (Max, Avg, Min)
- Precipitation Total

## Example Output

The script generates:
1. Model performance visualizations
2. Feature importance plots
3. Prediction vs actual comparisons
4. Saved ML models for temperature and humidity prediction

## Agricultural Applications

- Irrigation scheduling with confidence intervals
- Frost protection planning
- Optimal crop spraying timing
- Disease prevention based on humidity forecasts
- Risk assessment for planting and harvesting

## License

[MIT License](LICENSE)
