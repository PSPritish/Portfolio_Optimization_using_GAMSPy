

---

# Portfolio Optimization using Financial Data

This repository contains code for optimizing a portfolio of S&P 500 companies based on historical financial data.

## Requirements

- Python 3
- Pywikibot
- Yahoo Finance (yfinance)
- Pyomo
- numpy

Install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/portfolio-optimization.git
   cd portfolio-optimization
   ```

2. Set up Pywikibot for fetching S&P 500 company data from Wikipedia. You will need credentials for Pywikibot.

3. Ensure Yahoo Finance API access is configured for downloading historical stock prices.

## Usage

### 1. Fetch S&P 500 Company Symbols

Run the following Python script to fetch S&P 500 company symbols from Wikipedia:

```python
python fetch_symbols.py
```

### 2. Calculate Monthly Stock Increases

Calculate monthly stock increases for each S&P 500 company:

```python
python calculate_increases.py
```

### 3. Portfolio Optimization

Optimize the portfolio using a financial model:

```python
python optimize_portfolio.py
```

Adjust the parameters and constraints in `optimize_portfolio.py` as needed.

## Files

- `fetch_symbols.py`: Python script to fetch S&P 500 company symbols from Wikipedia.
- `calculate_increases.py`: Python script to calculate monthly stock increases.
- `optimize_portfolio.py`: Python script to optimize the portfolio using a financial model.
- `requirements.txt`: List of Python dependencies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Data sourced from Wikipedia and Yahoo Finance.
- Built with Pywikibot, Yahoo Finance API, Pyomo, and numpy.


---

Feel free to adjust the sections and content according to your specific project details and preferences. Make sure to update the links, descriptions, and instructions to match your actual project setup and usage.
