# DR IDR Range Indicator ReadMe

## Introduction
The DR IDR Range Indicator is a custom indicator developed by the Forex Robot Easy Team. It is designed to calculate and display the Average Daily Range (ADR), Open Daily Range (ODR), and Range Daily Range (RDR) for a specified number of past days. This indicator can be used to analyze the daily price ranges of a trading instrument and identify potential trading opportunities.

Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

## Indicator Parameters
- **pastDays** (default: 10): The number of past days to calculate ranges for.

## Global Variables
- **adr[]**: An array to store the Average Daily Range.
- **odr[]**: An array to store the Open Daily Range.
- **rdr[]**: An array to store the Range Daily Range.

## Indicator Initialization
The initialization function sets up the indicator buffers and initializes the arrays.

## Indicator Iteration
The iteration function calculates the ranges for each day based on the input price data. It then calculates the success rate by counting the number of days where the Range Daily Range is greater than 0. The success rate is displayed as a comment on the chart.

## Example Usage
To use the DR IDR Range Indicator, follow these steps:
1. Download and install the indicator file (.mq4) into your MetaTrader platform.
2. Open the desired chart and attach the indicator to it.
3. Adjust the indicator parameters, if needed.
4. The indicator will calculate and display the Average Daily Range, Open Daily Range, and Range Daily Range for the specified number of past days.
5. Use the indicator's analysis and success rate to make informed trading decisions.

## Product Description
The DR IDR Range Indicator is a powerful tool that can enhance your forex trading analysis. Developed by the Forex Robot Easy Team, this indicator calculates and displays the Average Daily Range, Open Daily Range, and Range Daily Range for a specified number of past days. By analyzing the daily price ranges of a trading instrument, you can identify potential trading opportunities and improve your trading strategies.

Key Features:
- Calculates and displays the Average Daily Range, Open Daily Range, and Range Daily Range.
- Customizable number of past days to calculate ranges for.
- Provides a success rate indicator to help you assess the profitability of your trades.
- Easy to use and understand, even for beginner traders.
- Compatible with MetaTrader platforms.

Please note that Forex Robot Easy is not the official developer of this product. We only provide this code as a sample that can work as described in the product. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - DR IDR Range Indicator Review](https://forexroboteasy.com/forex-robot-review/dr-idr-range-indicator-review-enhancing-forex-backtests/).

For more information and support, please visit [forexroboteasy.com](https://forexroboteasy.com/).
