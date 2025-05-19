# Currency Exchange Rate Tracker & Converter

This project fetches real-time currency exchange rates using the ExchangeRate-API and allows for conversion between currencies.

## Features
- Fetches the latest exchange rates for a specified base currency (default USD).
- Displays rates for common currency pairs.
- Converts a user-specified amount from one currency to another using live rates.
- The historical data plotting feature is currently commented out in the script.

## Technologies Used
- Python
- `requests` library (for API calls)
- `json` library (for parsing API response)
- `pandas` (if historical data is uncommented)
- `matplotlib` (if historical data is uncommented)
- `numpy` (if historical data is uncommented)


## Setup
1.  **Get an API Key:** Sign up for a free API key at [https://www.exchangerate-api.com/](https://www.exchangerate-api.com/).
2.  **Update API Key in Script:** Open the `currency_converter.py` script and replace the placeholder for `API_KEY` at the top of the script with your actual API key.
    ```python
    API_KEY = 'YOUR_ACTUAL_API_KEY_HERE' # Replace with your key
    ```
3.  **Install Libraries:**
    ```bash
    pip install requests pandas matplotlib numpy
    ```

## How to Run
1.  Ensure you have completed the setup steps.
2.  Run the Python script:
    ```bash
    python currency_converter.py
    ```
    (Or execute the cells if you are using a Jupyter Notebook).
3.  The script will output the latest rates and example conversions to the console.

## API Used
- [ExchangeRate-API](https://www.exchangerate-api.com/) - Provides currency conversion data.
