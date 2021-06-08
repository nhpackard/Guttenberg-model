# Guttenberg-model
N. Guttenberg predator prey model
Guttenberg, Nicholas, and Nigel Goldenfeld. "Cascade of complexity in evolving predator-prey dynamics." Physical review letters 100, no. 5 (2008): 058102.

Spatial predator-prey model with predator-prey interactions determined by evolving bit strings.


```
## configuration params

# world
Height = 64
Width = 64
Dens = 0.01                                # initial density of agents

# agent ID specification
LenID = 64    # length of ID string
Nletters = 8   # number of letters used  e.g. 4 => letters drawn from ABCDabcd
Nrelevant = 2       # number of relevant letters (others are neutral)
Seed = 0       # random seed

# reproduction
Mutrate = 0.02
Duprate = 0.01
Dierate = 0.001
```
