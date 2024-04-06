# Randomly Possoinian statistic simulation
https://github.com/yfzzzzz/Secondary-electron-pulse-Poissonian-simulation.git

## Overview
The code enables generating randomly Poisson distribution Secondary electron events within a generated detection window. The event is a purely single exponential curve. Providing further analysis including curve fitting, exponential coefficients estimating, plotting, and making histograms.

## Installation
To download and install MATLAB, Simulink, and other MathWorks products:

1\ Sign in to your MathWorks Account or create a new one.

2\ Download your products from MathWorks Downloads.

3\ Follow the prompts to install the products for which you are licensed.

If you do not have a license for MathWorks products through an organization, such as a university or company, you can buy products or request a trial from the MathWorks Store.

## How it works
Modifying the single exponential coefficients. Then, adjusting parameters inside the 'Initialization' segments. After that, just play the 'run' button.

## Running an example
Here is an example of creating events parameters, the equation is given as y = a*exp(b*x):
```
a_factor = round(log10(mean(cell2mat((a1_descend)))),0);
a = (a1_descend)*10^(a_factor);  
b_factor = round(log10(abs(mean(cell2mat((b1_descend))))),0);  
b = (b1_descend)*10^(b_factor);  
```
The 'a_factor' and 'b_factor' compute the order of magnitude of input data for further calculation and simulation.
## Bugs & Feature Requests
Please report bugs and request features using the [Issue Tracker](https://github.com/yfzzzzz/Secondary-electron-pulse-Poissonian-simulation/issues).
