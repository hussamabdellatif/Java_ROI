# Java_ROI
Java class with functions on calculating ROI of trades throughout 2016
Includes the following function definitions: 
1) Get Price: Given a stock file name and date, it will return the price of the stock on that date
2) costOfTrade: returns the cost of a single trade
3) isTradingValid: Determine whether or not the given trader made all valid trades.
     A trade is invalid if any of the following are true:
     * 1. The trader buys more shares of a stock than can be afforded with their current cash
     * 2. The trader sells more shares of a stock than they own
4) getTraderROI: Compute the ROI of a given trader with a given starting cash.
5) getTotalROI: Compute the ROI of the firm.Compute the total ROI given a map of traders and their starting cash
