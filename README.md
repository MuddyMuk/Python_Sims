# Python_Sims
## Title and Description
Wealth Growth with a Fluctuating Fund
This Python script simulates long-term wealth growth and forecasts various investment scenarios.
It includes contributions, retirement withdrawals, and rare market shocks.
A fluctuating fund is characterized by its arithmetic mean, with volatility determined by the difference between the arithmetic mean and a fixed geometric mean.
The simulation can run in either dynamic mode, where fund parameters change yearly, or static mode, where they remain constant throughout the simulation.

Features
*Switch between dynamic and static modes for determining fund parameters.
*Calculate standard deviation based on the gap between the arithmetic mean and geometric mean.
*Simulate rare positive and negative market events that impact wealth accumulation.
*Output the average wealth and the percentage of successful (non-bankruptcy) simulation runs.
*Visualize results in two graphs: Overall View and Expanded View.

Requirements
This project requires Python 3.8 or later, along with the following libraries:
```pip install numpy matplotlib```
