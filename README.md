# Python_Sims
## Title and Description
Wealth Growth with a Fluctuating Fund
This Python script simulates long-term wealth growth and forecasts various investment scenarios.
It includes contributions, retirement withdrawals, and rare market shocks.
A fluctuating fund is characterized by its arithmetic mean, with volatility determined by the difference between the arithmetic mean and a fixed geometric mean.
The simulation can run in either dynamic mode, where fund parameters change yearly, or static mode, where they remain constant throughout the simulation.

## Features
*Switch between dynamic and static modes for determining fund parameters.
*Calculate standard deviation based on the gap between the arithmetic mean and geometric mean.
*Simulate rare positive and negative market events that impact wealth accumulation.
*Output the average wealth and the percentage of successful (non-bankruptcy) simulation runs.
*Visualize results in two graphs: Overall View and Expanded View.

## Requirements
This project requires Python 3.8 or later, along with the following libraries:
```pip install numpy matplotlib```

## Usage
-Clone this repository:
```git clone https://github.com/your-username/your-repo-name.git cd your-repo-name```
-Run the script:
```python wealth_simulation.py```
-Adjust parameters in the simulate_wealth() call at the bottom of the script to test different scenarios:
*mean1: Expected annual return (%)
*geometry_ave1: Geometric average of annual return (%)
*dynamic_volatility: True for dynamic mode, False for static mode
*yearly_contribution: Annual savings amount (in yen)
*years_contribute: Number of years to contribute before retirement
*years_to_retire: Total years before retirement
*yearly_spend: Annual expenses after retirement (in yen)
-View results:
*Console output: Average wealth and non-bankruptcy rate
*Graphs: Overall view & expanded view of wealth over time

## Acknowledgements
This project was inspired by GUI-Retirement-Investment-Forecast.
