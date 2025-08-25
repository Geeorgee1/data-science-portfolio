# API Data Collection Pipeline

A robust Python script to collect live cryptocurrency prices from a public API, demonstrating core data engineering skills.

## 🚀 Features

- **API Integration:** Fetches data from the CoinGecko API.
- **Error Handling:** Robust `try-except` blocks to handle network and parsing errors gracefully.
- **Data Persistence:** Saves collected data with timestamps to CSV files.
- **Scalable Design:** Uses a loop to handle multiple cryptocurrencies efficiently.

## 🛠️ Tech Stack

- `Python 3`
- `requests` (API calls)
- `pandas` (data structuring)
- `datetime` (timestamping)

## 📁 Project Structure

```
data-engineering-projects/
└── Data_Engineering_API_Data_Collection.ipynb
```

## 🏃‍♂️ How to Run

1.  Open the `.ipynb` file in Google Colab or Jupyter Notebook.
2.  Run all cells. The script will fetch prices for Bitcoin and Ethereum and save them to a timestamped CSV file.
