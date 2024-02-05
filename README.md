## Fundamental Breakout Expert Advisor for MQL5

This is the code for the Fundamental Breakout Expert Advisor developed by the Forex Robot Easy Team. Please note that Forex Robot Easy is not the official developer of this product. This code serves as a sample and can work as described in the product.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Fundamental Breakout EA Review](https://forexroboteasy.com/forex-robot-review/fundamental-breakout-ea-review-free-forex-software-with-profit-sharing/).

### Description
The Fundamental Breakout Expert Advisor is designed to trade breakouts based on a custom indicator. It places Buy Stop and Sell Stop orders when certain conditions are met. The EA allows customization of parameters such as Stop Loss, Take Profit, Trailing Stop, Magic Number, Symbol Name, and Timeframe.

### Global Variables
- `StopLoss`: Stop Loss value in pips.
- `TakeProfit`: Take Profit value in pips.
- `TrailingStop`: Trailing Stop value in pips.
- `MagicNumber`: Unique Magic Number for trades.

### Custom Indicator Constants
- `RANGE_HIGH`: Index of the Range High value in the indicator buffer.
- `RANGE_LOW`: Index of the Range Low value in the indicator buffer.

### Expert Advisor Input Parameters
- `SymbolName`: Symbol name to trade.
- `Timeframe`: Timeframe for trading.

### Initialization Function
The `OnInit()` function is responsible for initializing the expert advisor. It sets the required time settings and subscribes to the specified symbol and timeframe.

### Start Function
The `OnTick()` function is the main function that gets called on each tick of the chart. It checks if it's time to place orders and calculates the Range High and Range Low values using the custom indicator. It then places Buy Stop and Sell Stop orders based on the calculated values. If the Trailing Stop parameter is enabled, it sets a trailing stop for the orders.

### Helper Functions
- `IsTimeToTrade()`: Determines if it's time to trade based on custom logic. (Placeholder logic used in this code)
- `SetOptimization()`: Sets the required time settings. (Custom logic needs to be implemented)

For more information about this product and to find the official developer, please refer to MQL5.
