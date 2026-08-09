# dsk-er-st-grid-sweep
# DSK ER-ST Grid Sweep v1.3

Pine Script indicator for comparing Standard ST vs ER-Gated Supertrend across 11 multiplier levels.

## Features
- 11 multiplier levels (1.75 to 4.25, step 0.25)
- 4 columns: STD_OFF, STD_HTF, ER_OFF, ER_HTF
- Peak and plateau detection with recommendations
- HTF filter support (SMA/EMA/WMA/ALMA)

## Usage
1. Copy/paste into TradingView Pine Editor
2. Set parameters in Inputs
3. Run on your chart

## Parameters
| Parameter | Default | Description |
|-----------|---------|-------------|
| Multiplier Start | 1.75 | Start of sweep range |
| Multiplier Step | 0.25 | Step between levels |
| Number of Levels | 11 | Total levels to sweep |
| ER Min Multiplier | 1.75 | Multiplier when ER=1 |
| Plateau Threshold | 5% | Max % diff for plateau |

## Version
v1.3 - Fixed compilation errors, stable release
