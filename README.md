Golden Cross EA for MT5
Overview

The Golden Cross EA for MetaTrader 5 is an automated trading bot that implements the Golden Cross and Death Cross strategy. It uses two moving averages (50-period and 200-period) to trigger buy and sell signals, combined with the MACD indicator for further confirmation. The EA opens a trade when a Golden Cross (bullish crossover) occurs and closes it when a Death Cross (bearish crossover) is detected. Additionally, it supports trailing stop functionality and allows for the use of customizable stop loss and take profit levels, all configurable in USD.
Features

    Golden Cross Strategy: Open buy positions when the 50-period moving average crosses above the 200-period moving average.

    Death Cross Strategy: Open sell positions when the 50-period moving average crosses below the 200-period moving average.

    MACD Confirmation: Adds an additional filter to the crossovers using the MACD indicator.

    Trailing Stop: Implement trailing stop functionality that adjusts the stop loss in USD.

    Stop Loss and Take Profit: Configurable in USD. You can specify the desired values for stop loss and take profit directly from the parameters panel.

    Parameters:

        Fast MA Period: The period for the fast moving average (default: 50).

        Slow MA Period: The period for the slow moving average (default: 200).

        Lot Size: The lot size per trade (default: 0.1).

        Stop Loss: Stop loss in USD (default: 700).

        Take Profit: Take profit in USD (default: 3500).

        Shift Bars: Number of bars to wait before opening a trade (default: 1).

        Trailing Stop: Trailing stop distance in USD (default: 200).

        MACD Parameters: Fast, slow, and signal periods (default: 12, 26, and 9).

Installation

    Download the EA file GoldenCrossEA.mq5.

    Place the file in your MetaTrader 5 platform's Experts folder:

        MQL5 > Experts > GoldenCrossEA.mq5

    Restart MetaTrader 5 and navigate to the Navigator panel.

    Find the EA under Expert Advisors and drag it onto your chart.

Parameters
Parameter	Description	Default Value
Fast_MA_Period	Period for the fast moving average.	50
Slow_MA_Period	Period for the slow moving average.	200
Lot_Size	Lot size per trade.	0.1
Stop_Loss	Stop loss in USD.	700
Take_Profit	Take profit in USD.	3500
Shift_Bars	Number of bars to wait before opening a trade.	1
Trailing_Stop	Trailing stop in USD.	200
MACD_Fast	Fast period for the MACD indicator.	12
MACD_Slow	Slow period for the MACD indicator.	26
MACD_Signal	Signal period for the MACD indicator.	9
Usage

    Attach the EA to a chart.

    Configure the parameters based on your strategy and preferences.

    The EA will automatically open buy positions when a Golden Cross occurs and sell positions when a Death Cross happens.

    It will close the open positions based on the strategy.

    Trailing stop functionality will activate once a position is open, adjusting stop losses as the price moves in favor of the trade.

    You can also configure a stop loss and take profit in USD, which is automatically converted to points based on the current market price.

Risk Disclaimer

Automated trading carries significant risk. You should only trade with capital that you can afford to lose. Ensure that you fully understand the strategy and risks involved before using the EA on a live account. Always test the EA on a demo account first.
License

This EA is for personal use and educational purposes. You may freely use and modify it for non-commercial purposes. For commercial licensing or inquiries, please contact the repository owner.
