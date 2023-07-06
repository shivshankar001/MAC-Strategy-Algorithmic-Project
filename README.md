# Moving Average Crossover Strategy Algorithmic Project

## Overview
This project implements a trading strategy known as the Moving Average Crossover Strategy. The strategy is based on the concept of moving averages, which are widely used in technical analysis of financial markets. The goal of the strategy is to generate buy and sell signals based on the crossover of two moving averages.

## Dependencies
To run this project, you will need the following dependencies:
- Python (version 3.5 or higher)
- Pandas library
- Numpy library
- Matplotlib library

## Installation
1. Clone the project repository from [GitHub](https://github.com/yourusername/project-repo).
2. Install Python if you don't have it installed already. You can download Python from the official website: [python.org](https://www.python.org/downloads/).
3. Install the required libraries by running the following command in your terminal:
   ```
   pip install pandas numpy matplotlib
   ```

## Usage
1. Open the terminal or command prompt and navigate to the project directory.
2. Run the `main.py` file using the following command:
   ```
   python main.py
   ```
3. The program will load historical price data from a CSV file located in the `data` directory.
4. The moving average crossover strategy will be applied to the price data.
5. The buy and sell signals will be plotted on a chart.
6. The program will generate a report file containing the trading signals and performance metrics.

## Configuration
You can configure the following parameters in the `config.py` file:

- `data_file`: Path to the CSV file containing the historical price data.
- `fast_ma_period`: Period of the fast moving average.
- `slow_ma_period`: Period of the slow moving average.
- `buy_threshold`: Threshold value for generating a buy signal.
- `sell_threshold`: Threshold value for generating a sell signal.

Adjust these parameters according to your preference and trading strategy.

## Data Format
The historical price data should be in CSV format with the following columns:
- `Date`: The date of the price data (format: YYYY-MM-DD).
- `Open`: The opening price of the security.
- `High`: The highest price during the trading day.
- `Low`: The lowest price during the trading day.
- `Close`: The closing price of the security.
- `Volume`: The trading volume for the day.

## Results
After running the program, you will find the following files in the project directory:

- `chart.png`: A chart showing the buy and sell signals.
- `report.txt`: A report containing the trading signals and performance metrics.

## Disclaimer
This project is for educational and informational purposes only. The trading strategy implemented in this project does not guarantee profits or success in the financial markets. Use it at your own risk.

## Contributing
If you would like to contribute to this project, you can fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
