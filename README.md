# Google Trends and Data Visualization

This project explores the relationship between Google Trends search volume and various types of data such as stock prices and unemployment rates. The goal is to analyze if search popularity correlates with financial data like the price of Bitcoin or Tesla stock, or with economic indicators like the unemployment rate.

## Data Sources
- **[Unemployment Rate from FRED](https://fred.stlouisfed.org/series/UNRATE/)**: Official unemployment rate data from the Federal Reserve Economic Data (FRED).
- **[Google Trends](https://trends.google.com/trends/explore)**: Data on search volume from Google Trends.
- **[Tesla Stock Price from Yahoo Finance](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)**: Historical stock prices for Tesla.
- **[Bitcoin Price from Yahoo Finance](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)**: Historical Bitcoin prices.

## Project Structure

- `TESLA Search Trend vs Price.csv`: Dataset containing Tesla search trend and stock price data.
- `Bitcoin Search Trend.csv`: Dataset containing Bitcoin search trend data.
- `Daily Bitcoin Price.csv`: Dataset containing daily Bitcoin prices.
- `UE Benefits Search vs UE Rate 2004-19.csv`: Dataset containing unemployment benefits search data and the unemployment rate from 2004 to 2019.
- `UE Benefits Search vs UE Rate 2004-20.csv`: Extended dataset including 2020 unemployment benefits search data and the unemployment rate.

## Setup and Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Prathamesh326/Google-Trends-and-Data-Visualisation.git
    cd Google-Trends-and-Data-Visualisation
    ```

2. Install the necessary Python libraries:

    ```bash
    pip install pandas matplotlib
    ```

3. Download the datasets and place them in the same directory as your Jupyter Notebook.

## Usage

### Data Exploration

The project starts with exploring the datasets to understand the structure, check for missing values, and convert date columns into datetime objects.

### Data Visualization

The core of the project is the visualization of data:
- **Tesla Stock Price vs. Search Volume**: A dual-axis line chart that shows Tesla's stock price alongside search volume data.
- **Bitcoin Price vs. Search Volume**: A similar chart for Bitcoin, showing the relationship between price and search volume.
- **Unemployment Benefits Search vs. Unemployment Rate**: Visualization of search interest in unemployment benefits compared to the actual unemployment rate in the U.S.

### Challenges

Throughout the project, various challenges are presented, such as checking data periodicity, handling missing values, converting data types, resampling time series data, and creating visually appealing and informative plots.

## Conclusion

The project illustrates how search volume data from Google Trends can be visualized alongside financial and economic data to reveal potential correlations and trends.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
