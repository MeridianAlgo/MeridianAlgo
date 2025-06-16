# Volume Pulse Reversal (VPR) Indicator

## Overview
The **Volume Pulse Reversal (VPR)** indicator is a Pine Script v5-based tool designed for the TradingView platform. It identifies potential reversal points in financial markets by combining volume spikes, RSI momentum, and price dynamics relative to a Volume-Weighted Moving Average (VWMA) and Exponential Moving Averages (EMAs). The indicator provides visual signals, highlighted reversal zones, and a customizable information table displaying key metrics.

Developed by **MeridianAlgo**, this indicator is tailored for traders seeking to enhance their technical analysis with a unified user interface and clear visual feedback.

## Features
- **Volume Analysis**: Detects significant volume spikes relative to a moving average, indicating potential market turning points.
- **RSI Momentum**: Uses Relative Strength Index (RSI) to confirm overbought or oversold conditions for reversal signals.
- **Price Dynamics**: Incorporates VWMA and EMAs to assess price position and trend direction.
- **Visual Signals**: Displays buy/sell signals with customizable labels and reversal zones with background highlights.
- **Information Table**: Shows real-time status (Bullish, Bearish, Neutral) and RSI values in a customizable table.
- **User Interface**: Unified settings panel for easy configuration of lookback periods, thresholds, and display options.
- **Alerts**: Configurable alerts for bullish and bearish reversal signals.

## Installation
1. **Copy the Code**: Copy the Pine Script code from the provided script file.
2. **Access TradingView**: Log in to your TradingView account and open the Pine Editor.
3. **Paste and Compile**: Paste the code into the Pine Editor and click "Add to Chart."
4. **Customize Settings**: Adjust the indicator settings via the input panel to suit your trading strategy.
5. **Save**: Save the indicator to your TradingView library for future use.

## Settings
The indicator features a unified user interface with the following configurable groups:

### General Settings
- **Lookback Period**: Sets the period for VWMA and volume averaging (default: 20, range: 5–100).
- **Volume Threshold Multiplier**: Multiplier for detecting volume spikes (default: 1.5, range: 0.5–5.0).

### RSI Settings
- **RSI Length**: Period for RSI calculation (default: 14, range: 5–50).
- **RSI Overbought**: Threshold for bearish reversals (default: 70, range: 50–90).
- **RSI Oversold**: Threshold for bullish reversals (default: 30, range: 10–50).

### Display Settings
- **Show Buy/Sell Signals**: Toggle buy/sell signal labels (default: true).
- **Show Reversal Zones**: Toggle background highlights for reversal zones (default: true).
- **Show VWAP**: Toggle VWMA display (default: true).
- **Show EMAs**: Toggle fast (9-period) and slow (21-period) EMA display (default: true).
- **Table Position**: Set the position of the info table (options: top_right, top_left, bottom_right, bottom_left).

### Color Settings
- **Bullish Zone Color**: Color for bullish reversal zones (default: semi-transparent green).
- **Bearish Zone Color**: Color for bearish reversal zones (default: semi-transparent red).
- **VWAP Color**: Color for VWMA line (default: blue).
- **EMA Fast Color**: Color for 9-period EMA (default: orange).
- **EMA Slow Color**: Color for 21-period EMA (default: purple).

## Usage
- **Chart Elements**:
  - **VWMA and EMAs**: Plotted on the main chart for trend and price context.
  - **Reversal Zones**: Highlighted with colored backgrounds when reversal conditions are met.
  - **Buy/Sell Signals**: Labeled on the chart at potential entry points.
  - **Momentum Histogram**: Displayed in a separate pane to show price momentum relative to VWMA.
  - **Info Table**: Located at the user-specified position, showing current status and RSI value.

- **Trading Strategy**:
  - Use bullish signals (green "BUY" labels) for potential long entries when price is below VWMA, RSI is oversold, and volume spikes occur.
  - Use bearish signals (red "SELL" labels) for potential short entries when price is above VWMA, RSI is overbought, and volume spikes occur.
  - Confirm signals with additional analysis, such as trend direction (via EMAs) and market context.

- **Alerts**:
  - Set up alerts for "VPR Buy Signal" and "VPR Sell Signal" to receive notifications when reversal conditions are met.

## Example
When applied to a chart, the VPR indicator will:
1. Plot the VWMA and EMAs (if enabled).
2. Highlight bullish (green) or bearish (red) zones when reversal conditions are detected.
3. Display "BUY" or "SELL" labels for confirmed signals.
4. Show a momentum histogram in a separate pane.
5. Present a table with the current status (Bullish/Bearish/Neutral) and RSI value.

## Legal Disclaimer
**Important**: This indicator is provided for educational and informational purposes only. It is not financial advice, nor a recommendation to buy or sell any financial instrument. Trading involves significant risk, including the potential loss of your entire investment. Past performance is not indicative of future results. Always conduct your own research and consult a qualified financial advisor before making trading decisions. **MeridianAlgo** is not liable for any losses incurred from using this indicator.

## Contributing
This indicator is maintained by **MeridianAlgo**. For suggestions, bug reports, or contributions, please contact **meridianalgo@gmail.com** or submit feedback via the TradingView community.

## Contact
For support or inquiries, reach out to **MeridianAlgo** at **meridianalgo@gmail.com**.

---
*Developed by MeridianAlgo, 2025*
