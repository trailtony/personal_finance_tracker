
# 🧾 Personal Finance Tracker (CSV-Based)

This is a command-line Python application to help track your personal finances. It allows you to log transactions, view reports over custom date ranges, and visualize your income and expenses over time using line plots.

## 📦 Features

- Add and store transactions in a CSV file
- View transactions within a date range
- Automatic income vs. expense summary
- Line plot of income and expenses over time
- Uses `pandas` and `matplotlib` for data processing and visualization

## 🛠️ Requirements

- Python 3.7+
- `pandas`
- `matplotlib`

Install dependencies using:

```bash
pip install pandas matplotlib
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/trailtony/personal_finance_tracker.git
   cd finance-tracker
   ```

2. **Run the app**:
   ```bash
   python main.py
   ```

3. **Follow the prompts** to:
   - Add new transactions (date, amount, category, description)
   - View transactions in a date range with a summary
   - Visualize your data with a line graph

## 🗃️ CSV Format

Transactions are stored in a `finance_data.csv` file with the following columns:

- `date` (format: dd-mm-yyyy)
- `amount`
- `category` (e.g., Income, Expense)
- `description`

## 📊 Visualization

When enabled, the app will generate a plot showing income and expenses by day, using resampled and aligned daily data.

## 📝 File Structure

- `main.py` — Main CLI loop
- `data_entry.py` — Helper functions to get user input
- `finance_data.csv` — Automatically generated CSV storage

## 📄 License

MIT License — Feel free to use and modify!