# Shipping Optimization Challgen my solution

## how to run

### RUN

```shell script
python src/train_hydra.py
```

### My environment

#### Python
- Python 3.7.9
- conda
- library(requirements.txt)

#### Computer

- Ubuntu 20.04
- CPU: i9 9900K
- Memory: 16 * 2 (GiB)

## solution

I used `train_2_pr.csv`, `test_2_csv` and `submission_2.csv`.

Features
1. Removed the duplicate feature.
2. Made features about time.
3. Made some features.(ex. cost, groupby_mean)

Modeling
1. Use LightGBM
2. Used optuna to search for the optimal parameters.


