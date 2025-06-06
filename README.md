# 🏡 UK Mortgage Rate Prediction

This project aims to predict the **UK variable mortgage interest rate** using historic data, including:
- Past variable interest rates
- Bank of England interest rates
- 10-year government bond yields

We use this financial time-series data to train a regression model and evaluate its accuracy over time.

---

## 📥 Getting Started

1. **Download the dataset** from Kaggle:
   [UK Mortgage Rates – Liam Healy](https://www.kaggle.com/datasets/liamhealy/uk-mortgage-rates)

2. **Unzip the downloaded file**.

3. **Update the file path** in `CallingData.py`:
   ```python
   file_path = 'ENTER YOUR FILE PATH TO CSV HERE'

4. **Run the main script**
    python main.py

**Install Dependencies**
pip install -r requirements.txt
