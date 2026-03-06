# Primetrade.ai Data Science Intern Assignment
Trader Performance vs Market Sentiment (Fear/Greed)

## Project Kya Hai
Bitcoin Fear/Greed sentiment aur Hyperliquid traders ke data ko analyze kiya. Dekha ki sentiment (Fear/Greed) se traders ka profit/loss, trades count, win rate kaise affect hota hai.

## How To Run
1. Open Google Colab .
2. Dono CSV files upload karo (fear_greed_index.csv aur historical_data.csv).
3. Notebook file (.ipynb) run karo – sab cells ek-ek karke.
   Libraries: pandas, matplotlib, seaborn, scikit-learn

## Methodology 
- Dates clean kiye aur dono datasets merge kiye (date pe).
- Har din ke liye trader metrics banaye: total PnL, num_trades, win_rate, buy_ratio.
- Bar plots aur box plots se patterns dekhe.
- Bonus: Random Forest model se next-day PnL predict kiya (error \~$6142).

## Key Insights
1. Fear days pe average PnL sabse zyada (\~$5328) – panic selling se opportunities banti hain.
2. Extreme Greed pe win rate highest (\~38.64%) lekin trades kam hote hain.
3. Fear periods mein traders zyada aggressive (higher buy ratio aur trade variation).

## Strategy Recommendations
1. Fear days pe thoda zyada leverage use karo (strict stop-loss ke saath) – profit potential high.
2. Extreme Greed mein sirf high win-rate wale traders ko aggressive allow karo – win probability better.

## Bonus Model Summary
- Model: Random Forest
- Average Error: $6142
- Most Important: num_trades (0.39) > avg_size_usd > win_rate
- Sentiment score ka asar kam (0.07) – trader behavior zyada matter karta hai.

Thanks for the opportunity!  
Sagar Singh 
8839618687