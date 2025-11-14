# 🏠 Redfin Housing Market Price Predictor

**End-to-end machine learning pipeline to predict median sale prices of U.S. residential properties**

## 📋 Project Overview

This project implements a complete machine learning pipeline that processes **50,000+ property records** to predict housing prices. The system uses data cleaning, feature engineering, and multiple ML algorithms to deliver accurate price predictions.

**Key Highlights:**
- 📊 Processes 50K+ property records with comprehensive data cleaning
- 🔧 Feature engineering from property types and market metrics
- 🤖 Compares Linear Regression and Random Forest models
- 📈 Achieves MAE < $20,000 on validation set
- 📉 Evaluates using MAE, RMSE, R², and accuracy metrics
- 📊 Visualizes results with matplotlib and seaborn

---
## 🚀 Quick Start

### Prerequisites

```bash
# Install required packages
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Project

1. **Clone the repository**
```bash
git clone https://github.com/kanishkay/housing-price-predictor.git
cd housing-price-predictor
```

2. **Add your data files**
   - Place `train.csv` and `test.csv` in the project directory

3. **Run the pipeline**
```bash
python housing_predictor.py
```

4. **View results**
   - Predictions saved to `housing_predictions.csv`
   - Visualizations displayed during execution

---

## 📁 Project Structure

```
housing-price-predictor/
│
├── housing_predictor.py          # Main pipeline script
├── train.csv                     # Training data (with prices)
├── test.csv                      # Test data (without prices)
├── housing_predictions.csv       # Output predictions
├── REA
