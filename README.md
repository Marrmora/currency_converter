# Currency Converter (Python + API)
### About the Project

This is a simple command-line Currency Converter built in Python.
It uses a free currency exchange API to fetch real-time exchange rates and convert between any two currencies.
The goal of the project is to practice API requests, JSON handling, and input validation.

### 🔍 Features

- Converts between any two world currencies
- Fetches live exchange rates from an external API
- Validates user input (non-numeric or negative values)
- Displays clear conversion results or error messages

### 💭 What I Learned

- How to make API calls using the requests library
- How to work with JSON responses
- How to handle user input and errors gracefully
- Basics of structuring a small Python script

### ⚙️ How to Run

Clone the repository:
```bash
git clone https://github.com/marrmora/currency-converter.git
cd currency-converter
```

Install dependencies (if needed):
```bash
pip install requests
```

Run the program:
```bash
python main.py
```

Enter the initial currency, target currency, and amount.

### 💱 Example
```pgsql
Enter the initial currency: USD
Enter the target currency: EUR
Enter the amount: 50
Conversion Result: 46.82
```
### 💻 Tech Stack

- Python 3
- Requests library
- External Exchange Rate API

### 📈 Next Steps

- Add currency symbols and rounding
- Add historical data tracking
- Build a simple Streamlit or Tkinter UI
