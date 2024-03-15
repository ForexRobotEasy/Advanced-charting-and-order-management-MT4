# T Manager Plus - Advanced Charting and Order Management System

This repository contains code for an advanced charting and order management system called T Manager Plus. It is developed by the Forex Robot Easy Team and is designed for Forex traders. Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product.

## Product Description

T Manager Plus is a powerful platform that combines trade management, trade assistance, and advanced charting facilities. It is designed to simplify and enhance the Forex trading experience. With T Manager Plus, traders can easily plan trades, execute them with a single click, and set orders quickly and efficiently.

### Trade Planning Functionality

T Manager Plus provides a user-friendly graphical interface for easy trade planning. Traders can set the price for their trades, as well as the stop loss and take profit levels. The platform also includes an automated risk calculation feature that allows users to set their risk as a percentage of their account balance. Additionally, T Manager Plus calculates the monetary value of the risk and displays the reward-to-risk ratio before entering any trade.

### Trade Execution Functionality

Trade execution is made simple with T Manager Plus. Traders can execute trades with just a single click, saving time and effort. The platform also allows for quick and efficient order setting. Users can specify the symbol, trade type, lots, price, stop loss, and take profit levels, and T Manager Plus will execute the trade accordingly.

## Code Explanation

The provided code includes functions for the trade planning and execution functionalities of T Manager Plus. Here is a breakdown of each section:

### Trade Planning Functionality

- `CalculateRisk()`: This function calculates the monetary value of the risk based on the account balance and the risk percentage set in the global variable `riskPercentage`.
- `CalculateRewardToRiskRatio()`: This function calculates the reward-to-risk ratio based on the entry price, stop loss, and take profit levels.

### Trade Execution Functionality

- `ExecuteTrade()`: This function executes a trade with a single click. It takes parameters such as the symbol, trade type, lots, price, stop loss, and take profit levels.
- `SetOrders()`: This function sets orders quickly and efficiently. It calculates the lot size based on the symbol's minimum volume and the risk amount. If the calculated lots exceed the minimum volume, it uses the minimum volume instead. Finally, it calls the `ExecuteTrade()` function to execute the trade.

### Logical Conclusion

The example usage of the trade planning and execution functionality is demonstrated in the `OnStart()` function. It sets the symbol, entry price, stop loss, and take profit levels, calculates the reward-to-risk ratio, and calls the `SetOrders()` function to execute the trade.

## Trading Results and Reviews

For detailed reviews and trading results of T Manager Plus, please visit [Forex Robot Easy's T Manager Plus Review](https://forexroboteasy.com/forex-robot-review/t-manager-plus-review-simplified-forex-trading-with-mt4/).
