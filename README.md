# Razor MT5 Expert Advisor

This is an expert advisor (EA) named Razor MT5 developed by the Forex Robot Easy Team. 

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/razor-mt5-review-optimize-forex-with-automated-system/).

## Description

Razor MT5 is designed to trade in the forex market by utilizing two different mechanisms - scalping and grid trading. The EA is capable of identifying strong market movements and executing the respective trading strategies.

### Scalper Mechanism

The scalper mechanism is responsible for identifying and exploiting small price changes in the market. It uses custom logic to determine optimal entry and exit points for trades. The EA will place trades and manage positions based on this mechanism.

### Grid Mechanism

The grid mechanism is implemented to take advantage of market volatility and price movements within a predefined range. The EA calculates grid levels based on the current price and the specified parameters such as grid distance, take profit, and stop loss. It then places a series of grid trades at these levels.

## Trading Parameters

The following trading parameters are defined in the code:

- Take Profit (TP): 10 pips
- Stop Loss (SL): 5 pips
- Grid Size: 10 trades
- Grid Distance: 5 pips

## Expert Functions

The expert advisor consists of the following functions:

### OnInit()

This function is called during the initialization of the EA. It sets the trading parameters for the selected symbols.

### OnTick()

This function is called on each tick of the selected symbols. It checks for strong market movements and executes the scalper and grid mechanisms accordingly.

### IsStrongMovement()

This function determines if there is a strong market movement based on custom logic. It returns a boolean value.

### ExecuteScalperMechanism()

This function executes the scalper mechanism by identifying and exploiting small price changes. It also handles trade placement and position management.

### ExecuteGridMechanism()

This function executes the grid mechanism by calculating grid levels and placing grid trades at those levels.

### OnDeinit(const int reason)

This function is called during the deinitialization of the EA. It can be used for custom cleanup code if necessary.

## Disclaimer

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work based on the description of the product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/razor-mt5-review-optimize-forex-with-automated-system/).
