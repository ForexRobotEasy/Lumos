# Lumos Code Development

This code is developed by [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-lumos-a-customizable-forex-trading-assistant-for-better-decision-making/). Lumos is a customizable Forex trading assistant that provides better decision-making capabilities.

## Description

This code is designed to analyze the market and execute a trading strategy based on Moving Average (MA) and Relative Strength Index (RSI) indicators. It includes the necessary libraries for trading and indicator calculations.

## Installation

1. Copy the code and save it as a .mq5 file.
2. Open MetaEditor in MetaTrader 5.
3. Compile the code by clicking on the 'Compile' button or pressing F7.
4. Attach the compiled EA to a chart in MetaTrader 5.

## Usage

1. Set the desired parameters in the global variables section.
2. Customize the trading strategy in the `ExecuteStrategy()` function.
3. Run the EA on a desired chart and timeframe.

## Requirements

- MetaTrader 5 platform.

## Global Variables

- `timeframe`: Timeframe for analysis.
- `stopLossDistance`: Distance from the current price to the stop loss level.
- `maPeriod`: Period for Moving Average calculation.
- `rsiPeriod`: Period for RSI calculation.
- `rsiMaPeriod`: Period for RSI Moving Average calculation.

## Functions

- `AnalyzeMarket()`: Performs market analysis by calculating Moving Average, RSI, RSI Moving Average, and stop loss level.
- `ExecuteStrategy()`: Implements the trading strategy based on the analyzed market data.
- `Lumos()`: Main algorithm that calls `AnalyzeMarket()` and `ExecuteStrategy()` functions.
- `OnInit()`: Initialization function that sets up the necessary objects and indicator parameters.
- `OnTick()`: Program loop function that executes the Lumos algorithm on each tick.

## Disclaimer

This code is provided for educational purposes only. Use it at your own risk. Forex Robot Easy does not guarantee any trading performance or profitability.

For more information and to download the Lumos Forex trading assistant, visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-lumos-a-customizable-forex-trading-assistant-for-better-decision-making/).
