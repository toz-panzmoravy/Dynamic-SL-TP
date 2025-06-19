# SmartTPSL Indicator Documentation

## Overview
SmartTPSL is an advanced TradingView indicator designed for precise Stop Loss and Take Profit level calculations. It combines multiple technical factors to provide dynamic trading levels adapted to current market conditions.

## Key Features

### 1. Dynamic Level Calculation
- **Stop Loss Levels**: Based on ATR volatility
- **Take Profit Levels**: Three targets with customizable risk-reward ratios
- **Automatic Adjustment**: Levels adapt to market volatility

### 2. Trend Analysis System
- EMA Crossover Analysis (9/21)
- RSI Level Monitoring (30-70)
- Volume Analysis
- Price Movement Tracking

### 3. Visual Elements
- Color-coded level lines
  - Red: Stop Loss
  - Green: Take Profit 1
  - Lime: Take Profit 2
  - Aqua: Take Profit 3
- Clear price labels
- Comprehensive information table

## Settings

### Appearance
| Parameter | Description | Default |
|-----------|-------------|---------|
| Show Labels | Toggle price labels | True |
| Show Zones | Toggle level zones | True |
| Label Offset | Adjust label position | 5 |

### TP/SL Parameters
| Parameter | Range | Default | Description |
|-----------|-------|---------|-------------|
| SL ATR Multiplier | 0.5 - 5.0 | 2.0 | Stop Loss distance |
| TP1 R/R Ratio | 1.0 - 3.0 | 1.5 | First target |
| TP2 R/R Ratio | 1.5 - 5.0 | 2.5 | Second target |
| TP3 R/R Ratio | 2.0 - 10.0 | 4.0 | Third target |

### Trend Settings
| Parameter | Range | Default | Description |
|-----------|-------|---------|-------------|
| Trend Sensitivity | 0.1 - 1.0 | 0.6 | Signal sensitivity |

## Information Table
The indicator displays a comprehensive information table including:
- Current Trend Direction (LONG/SHORT/NEUTRAL)
- Risk Percentage
- Stop Loss Level
- Take Profit Levels (1-3)
- Trend Strength
- Current ATR Value

## Installation
1. Open TradingView Chart
2. Go to Pine Editor
3. Create New Indicator
4. Copy and paste the indicator code
5. Add to Chart

## Usage Guide
1. **Initial Setup**
   - Add indicator to your chart
   - Adjust parameters according to your trading style
   - Position the information table as needed

2. **Trading Application**
   - Monitor the trend direction
   - Use displayed levels for trade planning
   - Consider trend strength for position sizing

3. **Risk Management**
   - Use the calculated Stop Loss level
   - Plan partial exits at Take Profit levels
   - Monitor risk percentage for position sizing

## Best Practices
- Adjust ATR multiplier based on market volatility
- Use multiple timeframe analysis
- Consider trend strength before entering trades
- Monitor volume confirmation
- Use in conjunction with other technical analysis tools

## Technical Details
- Platform: TradingView
- Language: Pine Script v6
- Type: Overlay Indicator
- Update Frequency: Real-time
- Calculation Base: ATR, EMA, RSI, Volume

## Support
For questions or suggestions, please use the TradingView comments section or contact the developer directly.

## Disclaimer
This indicator is for informational purposes only. Always conduct your own analysis and use proper risk management techniques.
