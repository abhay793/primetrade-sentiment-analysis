# Trader Performance vs Market Sentiment – Summary

## Methodology
Two datasets were used: Bitcoin market sentiment (Fear/Greed index) and historical Hyperliquid trader data.  
Trades were aligned at a daily level using timestamps, and key metrics such as daily PnL, win rate, leverage proxy, trade frequency, and long/short bias were computed.

Analysis was conducted across sentiment regimes and further segmented by trader behavior (leverage usage, trading frequency, and consistency).

---

## Key Insights

1. **Sentiment impacts risk more than average returns**  
   Average daily PnL does not differ significantly between Fear and Greed regimes, but Fear periods exhibit substantially higher downside risk and volatility.

2. **Greed encourages overtrading without improving outcomes**  
   Trade frequency, leverage, and position sizes increase during Greed periods, yet win rates remain largely unchanged—indicating overconfidence-driven behavior.

3. **Leverage is the primary drawdown amplifier during Fear**  
   High-leverage traders experience significantly worse losses during Fear regimes, while low-leverage traders remain relatively stable.

4. **Discipline separates consistent winners**  
   Traders with higher historical win rates maintain controlled leverage and activity across regimes, resulting in smaller drawdowns.

---

## Strategy Recommendations

### 1. Sentiment-Based Leverage Control
Fear regimes should trigger reduced leverage exposure, particularly for high-leverage traders, to mitigate tail risk.

**Rule:**  
If sentiment = Fear → cap leverage or reduce position size.

---

### 2. Restrict Overtrading During Greed
Increased trading activity during Greed should be permitted only for historically consistent traders.

**Rule:**  
If sentiment = Greed → allow higher trade frequency only for consistent winners.

---

## Conclusion
Market sentiment acts as a **risk regime switch**, not a direct profitability signal. Effective strategies should prioritize leverage control and behavioral discipline over sentiment-driven aggression.
