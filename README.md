# WaveTrend Osc V20

This is a customizable market analysis tool that utilizes the WaveTrend oscillator. It provides traders with the ability to enable or disable lag and divergences indicators, and allows for the selection of the applied price for calculations.

## Features

- Customizable market analysis
- Lag indicator enable/disable option
- Divergences indicator enable/disable option
- Selectable applied price for calculations
- Overbought and oversold levels identification

## Input Parameters

- **EnableLag**: Enable or disable lag indicator (default: true)
- **EnableDivergences**: Enable or disable divergences indicator (default: true)
- **AppliedPrice**: Applied price for calculations (default: PRICE_CLOSE)
- **OverboughtLevel**: Level to identify overbought zone (default: 300)
- **OversoldLevel**: Level to identify oversold zone (default: -300)

## Trading Functions

The trading logic should be implemented in the `OnTick()` function. This is where you can add your own trading strategy based on the WaveTrend Oscillator.

## Indicator Functions

The indicator calculations should be implemented in the `OnCalculate()` function. This is where you can add your own calculations based on the provided market data.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in the official product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/wavetrend-osc-v20-review-advanced-forex-software-features/).
