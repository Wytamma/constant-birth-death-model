# Understand the constant birth-death model

## Learning outcomes

Develop a good understand the constant birth-death model

## Goals 

Use the BDsky BEAST2 model to estimate the:

- Fit a constant birth-death model.
- The duration of infection is 10 calendar days, but note that the tree has dates in units of years, so you will need to convert it accordingly. Also note that the duration of infection is not a parameter in beast, so you will need to transform it accordingly. This parameter should be fixed in the model (i.e not estimated).
- We need to estimate:
    - reproductive number (R0 here)
    - the sampling proportion
    - TMRCA
    - clock-rate

Choose priors in BEAST2 accordingly. 

## Data
- [The simulated sequences](data/BD_sequences.fasta) in fasta format
- [The timetree](data/BDTree_hetero_fixedN_MASTER.newick.tree) from which the sequences were generated, in case you want to have a look at it.
- [Population trajectories](data/BDTree_MASTER_constant_samp.json) in json format. You don’t need to look at it now, but when you fit the model, we can compare its expectation with these.