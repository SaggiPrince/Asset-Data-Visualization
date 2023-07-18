# Asset Data Visualization

Asset Data Visualization is a Python-based tool that allows users to analyze asset data from Yahoo Finance. It provides a user-friendly interface for downloading historical data, identifying buy and sell dates based on volume thresholds, plotting the asset's closing prices with buy and sell points, and displaying summary statistics.

## Description

Asset Data Visualization is designed to simplify the process of analyzing asset data for traders and investors. By leveraging the power of Yahoo Finance and matplotlib, users can quickly visualize the price trends of various assets and make informed decisions.

The tool allows users to specify an asset symbol, start and end dates, volume multiplier, and sell threshold. It then downloads the historical data for the specified asset, identifies potential buy and sell dates based on volume thresholds, plots the asset's closing prices over the selected date range, and provides summary statistics such as average volume, percentage change, daily range, and more.

The interactive interface allows users to easily customize the input parameters, view the plotted data, and export the downloaded asset data for further analysis.

## Features

- Download historical data from Yahoo Finance
- Calculate buy and sell dates based on volume thresholds
- Plot closing prices with buy and sell points
- Display summary statistics including average volume, percentage change, daily range, etc.
- Export downloaded asset data to a CSV file

## Usage

1. Enter the asset symbol, start date, end date, volume multiplier, and sell threshold in the provided input fields.

2. Click the "Plot" button to download the data, calculate buy/sell dates, and display the plot and summary statistics.

3. Use the "Clear" button to clear the plot and toolbar.

4. Click the "Export Data" button to export the downloaded asset data to a CSV file.

5. For each summary statistic, click the "Help" button to get a description of the statistic.

## Demo

![Project Demo](demo.gif)

## Dependencies

The following dependencies are required to run the project:

- tkinter
- tkcalendar
- yfinance
- matplotlib

## Install the dependencies using pip:

pip install tkinter tkcalendar yfinance matplotlib

## Acknowledgements

- This project uses the [tkinter](https://docs.python.org/3/library/tkinter.html) library for the graphical user interface.
- The date selection is powered by the [tkcalendar](https://github.com/j4321/tkcalendar) package.
- Financial data is retrieved using the [yfinance](https://pypi.org/project/yfinance/) library.
- Data visualization is done using the [matplotlib](https://matplotlib.org/) library.

## Contact

For any questions or suggestions, feel free to reach out to me:

- Kiavash D
- Email: kiavashdav@hotmail.com
- LinkedIn: https://www.linkedin.com/in/kiavash-davoodi/
