# ON Trade Joker Levels

This code is a sample implementation of the ON Trade Joker Levels trading tool developed by the Forex Robot Easy Team. The tool uses numerology key numbers to calculate support and resistance levels and automatically places trades based on these levels.

## Product Description

ON Trade Joker Levels is a numerology-driven Forex trading tool developed by the Forex Robot Easy Team. It is designed to identify support and resistance levels using key numbers derived from numerology principles. By analyzing the current price and applying these key numbers, the tool helps traders make informed trading decisions.

The tool utilizes the Trade.mqh and PositionInfo.mqh libraries to access trade functions and position information. It works on the EURUSD symbol and a specified timeframe.

The key numbers for support and resistance levels are defined as follows:
- Key Number 1: 7.0
- Key Number 2: 11.0
- Key Number 3: 22.0

The TradeJoker() function is the core of the tool. It calculates the support and resistance levels based on the current price and the defined key numbers. It then prints these levels and places trades accordingly.

If the current price is below the support level, a buy position is opened with a specified lot size, stop loss, and take profit. The stop loss is set at the support level minus the key number 3, and the take profit is set at the resistance level plus the key number 3.

If the current price is above the resistance level, a sell position is opened with the same lot size, stop loss, and take profit calculations as mentioned above.

The OnInit() function is the initialization function of the program. It initializes the trade functions and sets the trading context. It also adds the Trade Joker indicator to the chart.

The OnTick() function is the main program loop. It calls the Trade Joker indicator function to perform the necessary trading actions.

The OnDeinit() function is the program termination function. It finalizes the trade functions.

The OnStart() function is the entry point of the program. It starts the program execution.

Please note that ForexRobotEasy is not the official developer of this product. This code is a sample implementation provided to demonstrate the functionality of the ON Trade Joker Levels trading tool. To find the official developer of this product, please refer to the MQL5 platform.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - ON Trade Joker Levels Review](https://forexroboteasy.com/forex-robot-review/on-trade-joker-levels-review-numerology-driven-forex-trading-tool/).
