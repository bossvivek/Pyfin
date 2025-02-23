# Pynance

Pynance is a Streamlit application that allows users to fetch and analyze stock and cryptocurrency data. It includes functionalities for user authentication, fetching live and historical data, displaying stock news, and plotting data trends.

## Features

- User authentication (Log In and Sign Up)
- Fetch live stock data using Yahoo Finance
- Fetch historical stock data using Yahoo Finance
- Fetch historical cryptocurrency data using CoinGecko API
- Display stock news using Finnhub API
- Plot closing prices for stocks and cryptocurrencies

## Installation

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/pynance.git
   cd pynance
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Create a file named `requirements.txt` with the following content:
   ```plaintext
   streamlit
   yfinance
   pandas
   plotly
   pycoingecko
   finnhub-python
   openpyxl
   ```

## Usage

1. Navigate to the project directory:
   ```sh
   cd /c:/Users/prata/Desktop/Python learning
   ```

2. Run the Streamlit application:
   ```sh
   streamlit run pyfin.py
   ```

3. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).

## Project Structure

```
/c:/Users/prata/Desktop/Python learning
│
├── pyfin.py          # Main application file
├── users.xlsx        # Excel file for storing user credentials (created automatically)
└── README.md         # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
