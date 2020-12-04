# Shipping Optimization Challenge my solution

## how to run

### RUN

```shell script
python features/features_func.py
python src/train_hydra.py
```

The first line is a shell to run the source code to create the feature.

### My environment

#### Python

- Python 3.7.9
- conda
- library(requirements.txt)

#### Computer

- Ubuntu 20.04
- CPU: i9 9900k
- GPU: RTX 2080
- Memory: 16 * 2 (GiB)

## solution

Features

1. Removed the duplicate feature.
2. Made features about time.
3. Made some features.(ex. cost, groupby_mean)

xfeat: https://github.com/pfnet-research/xfeat  
optuna: https://github.com/optuna/optuna

Modeling

1. Use LightGBM
2. Used optuna to search for the optimal parameters.

What didn't work

- Permutation importance
- groupby_{std, else...}

