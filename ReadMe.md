# Personal Finance Dashboard (Streamlit)

An interactive web app to visualize your bank transactions, analyze spending, track budgets, and get alerts — all from a CSV file!

https://finance-urw3ybwvqfdm39rappp658a.streamlit.app/
---

## Features

- Upload your bank CSV
- View key financial metrics (Income, Expense, Savings)
- Filter by category or timeframe
- Set monthly budgets using sliders
- Get visual budget alerts
- Trend plots by category over time

---

## Sample Input CSV

Your file should look like:

| Type   | Component | Date       | Value | Year |
|--------|-----------|------------|-------|------|
| Income | Salary    | 2018-01-01 | 30000 | 2018 |
| Expense| Grocery   | 2018-01-03 | 150   | 2018 |

---

## Run Locally

```bash
git clone https://github.com/yourusername/personal-finance-dashboard.git
cd personal-finance-dashboard
pip install -r requirements.txt
streamlit run app.py
