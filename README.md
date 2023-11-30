# Trade Aide ReadMe File

## Description
Trade Aide is a utility for MT5 users that aims to simplify and enhance their trading experience. It provides a convenient solution for placing Limit or Stop orders and implements key combinations for order placement. Additionally, it automates the calculation of position size based on the risk set in the Inputs tab and allows for the automatic addition of multiple take profit levels.

Please note that Forex Robot Easy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Developer's Site
For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/trade-aide-a-comprehensive-review-of-forex-software-for-mt5-users/).

## Code Explanation

### OpenTrade Function
The `OpenTrade` function allows for the placement of entry or stop loss orders at the desired price level. If the SHIFT key is held down, an entry order is placed. If the CTRL key is held down, a stop loss order is placed.

### CalculatePositionSize Function
The `CalculatePositionSize` function automatically calculates the position size based on the risk percentage set in the Inputs tab. It takes into account the account balance, stop loss level, and point value of the market.

### AddTakeProfitLevels Function
The `AddTakeProfitLevels` function automatically adds multiple take profit levels based on the inputs provided. It places take profit levels at the specified price levels.

### Main Program
The main program consists of the following steps:
1. Opens a buy trade at the current market price.
2. Calculates the position size based on a 2% risk.
3. Prints the calculated position size.
4. Adds take profit levels at 100 pips, 200 pips, and 300 pips from the current market price.
5. Closes all open positions if the daily loss exceeds $100.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
