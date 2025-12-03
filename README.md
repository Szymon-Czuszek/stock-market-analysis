🤝 Exploring Stock Market Data

🔀 This project involves the analysis of stock market data for the WIG20 index in August 2023 while creating a reusable Python Class.

🧰 Overview: 
The main goal of this project is to perform in-depth analysis on the WIG20 index using stock market data obtained from an online source. The data spans the period from August 1, 2023, to August 31, 2023. The primary focus is on visualizing the data using various graphical representations and calculating essential statistical measures.

🌐 Data Source: 
The data for this project was sourced from https://stooq.pl

🏗️ Project Structure: 
🧱 StockMarketAnalysis Class - A custom Python class StockMarketAnalysis has been developed to facilitate the analysis and visualization of stock market data.

🧮 Functions:
- 📏 calculate_median_spread: Calculates the median spread between high and low prices.
- 📉 calculate_open_std: Computes the standard deviation of open prices.
- 🔢 format_y_labels: Formats y-axis labels for thousands, millions, and billions.
- 🕯️ plot_candlestick_chart: Generates a candlestick chart.
- 📊 plot_candlestick_chart_vs_volume: Produces a candlestick chart with a volume bar chart on a secondary y-axis.
- 📈 plot_close_price_evolution: Plots the evolution of close prices with a shaded price range.
- 📦 plot_volume_distribution: Illustrates the distribution of trading volume per weekday.
- 🧷 plot_combined_graph: Combines various plots into a single graph.

Example Usage: 
An instance of the StockMarketAnalysis class is created using the provided data. Basic statistics are calculated and visualizations, such as candlestick charts, volume distributions, and close price evolution, are generated to provide comprehensive insights into the WIG20 index for August 2023.

Example Code: 
wig20_aug = StockMarketAnalysis("WIG20 - August 2023", "your_data.csv")
wig20_aug.plot_combined_graph(plot_type="both")

Usage: 
Obtain the necessary libraries and dependencies.
Download the data from the provided source or use your dataset.
Create an instance of the StockMarketAnalysis class.
Utilize the functions within the class to analyze and visualize the stock market data.

## Example Code

```python
wig20_aug = StockMarketAnalysis("WIG20 - August 2023", "your_data.csv")
wig20_aug.plot_combined_graph(plot_type="both")
```

License: 
This project is licensed under the MIT License.
