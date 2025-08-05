# Tableau Dashboard : Stock Price

Requirements : 

1. Price Behavior & Volatility : 
    
    Problem : How does the stock price behave daily, monthly, yearly. 
    
    - Insights:
        - Daily % Change (returns)
        - Volatility spikes (price range: `High - Low`)
        - Outlier days (based on price swings or volume)
    - Viz :
        - **Line chart**: Daily `Close` prices over time
        - **Bar chart**: Daily % return
        - **Area chart or lollipop**: Price range (High - Low)

1. Trend & Moving Average Analysis : 
    
    Problem: Is the stock in an upward, downward, or sideways trend?
    
    - Insights:
        - 7-day, 30-day, 200-day moving averages
        - Compare actual price vs MA for trend confirmation
    - Viz :
        - **Line chart**: `Close` with overlaid **moving averages**
        - **Dual-axis line chart**: Compare `Close` vs 50-day/200-day MA
        
    
2. Volume-Price Relationship : 
    
    Problem : Do volume spikes correlate with price movements?
    
    - Insights :
        - Detect accumulation/distribution
        - Volume divergence (price rising, volume falling = weak trend)
    - Viz :
        - **Dual-axis combo chart**: Line for `Close`, bar for `Volume`
        - **Scatter plot**: Price change % vs Volume
        
    
3. Identify Breakouts & Gaps :
    - Problem: Are there significant price gaps that signal events?
    - Insights :
        - Gaps between yesterday’s `Close` and today’s `Open`
        - Visualize these on a candlestick chart
        - Highlight breakout levels from resistance/support
    - Viz :
        - **Candlestick chart**: Visualize OHLC clearly
        - **Gantt chart or custom shapes**: Highlight gaps
    
4. Time-Based Insights : 
    - Problem : What’s the behavior by day of week or month?
    - Insights :
        - Average returns by weekday
        - Best-performing months
        - Calendar heatmaps of returns
    - Viz :
        - **Bar chart**: Avg return by weekday/month
        - **Calendar heatmap**: Color-coded by daily return
        - **Boxplot**: Returns grouped by weekday
        
    
5. Drawdowns & Recovery : 
    - Problem : How bad did a stock fall from its peak, and how fast did it recover?
    - Insights :
        - Time taken to recover
    - Viz :
        - **Line chart**:  `Close`  + dotted line for previous peak
        - **Slope chart**: Time to peak vs time to recover