# Private Blotto
Supporting code for "Private Blotto: Viewpoint Competition with Polarized Agents"

## Overview of notebooks

`Sec_4_more_players_than_fronts.ipynb` reproduces results in Section 4, specifically for the case with $T=2$ types of players, arbitrarily many fronts, and the requirement that each front have at least one player (which requires at least as many players as fronts). This code reproduces Figure 1 and demonstrates empirical support for Hypothesis 1 (that any stable arrangement for mean outcome functions must be "close" to proportional). 

`Sec_5_arbitrary_stability.ipynb` reproduces results in Section 5, where there may be $T>2$ types of players and fronts can be left empty. It is a more comprehensive but slower version of the code in `Sec_4_more_players_than_fronts.ipynb`. This code provides intuition and demonstrates theoretical results from Section 5, such as showing that a stable arrangement always exists for mean outcome functions with $M=4$ fronts and $N=3$ players. 


## Versions

Python: 3.8.10

numpy: 1.22.3

pandas: 1.4.2

matplotlib: 3.5.1

json: 2.0.9
