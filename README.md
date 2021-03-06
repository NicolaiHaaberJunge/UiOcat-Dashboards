# Data Dashboards for UiOcat

Clone and start using [UiOcat](https://github.com/NicHaaJun/UiOcat) with JupyterLab or
[Voila](https://voila.readthedocs.io/en/stable/using.html).

## GC Analysis

_GCAnalysisDashboard.ipynb_ <br>
A dashboard for analyzing GC data from the Cofeed and HighPressure rigs. <br><br>

![image](https://user-images.githubusercontent.com/70808555/130938331-b16e59a1-b6aa-4759-99ab-22d792e0149f.png)

## Reaction Setup

_ReactorSetup.ipynb_ <br>

A dashboard/Calculator for setting up a catalytic reaction with various liquids
as reactant. Uses the Antoine Eqs. to calculate reactant partial pressures. 
Gives _weight hourly space velocity_ as well as reactant partial pressure as a
function of temperature, catalyst mass, and carrier gas flow rates.

You can use the reaction calculator by:
```
from uiocat.reactions import ReactorSetup

ReactorSetup()
```

![image](https://user-images.githubusercontent.com/70808555/130938036-798d0b80-afe4-4849-ad01-170ea0d9a576.png)
