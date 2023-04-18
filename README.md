# Cavitation Inception Calculation Script
The script determines the onset of cavitation in a water system by taking inputs of temperature, flowrate, and throat area. It then calculates the cavitation number for a range of flowrates and generates a table of flowrate, cavitation number, and velocity at which cavitation is expected to occur. The script also generates graphs for cavitation number vs flowrate, temperature vs inception velocity, and velocity vs flowrate.

This script can be useful in various fluid engineering applications, such as designing pumps, turbines, and propellers, as well as in predicting the onset of cavitation in various fluid systems. The script has been published on GitHub, making it easily accessible for anyone interested in using it or contributing to its development.

## Calculation Model Used:
- Cavitation Number - Euler's Equation
- Water Density - IAPWS Formulation 1995 equation
- Vapor Pressure - Antoine equation of water vapor

## Assumptions:
1. Cavitation will incept at cavitation number of 1 (i.e, unity)
2. Pure water is considered

## Note:
- Install Prettytable Library before running this program by executing following command:
```bash
  pip install prettytable
```
- Under General Public License (GNU)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)  

## 🚀 About Me
Author: Mohin Patel  
Mail: mohin00950@gmail.com
