# imputation
Repo to store code for working with imputation on iris dataset.

# How could I use this repository?
First, install `conda`. Then...

```
conda create -n imputation python=3.7 && source activate imputation
jupyter notebook
```

Then, once in select the `imputation.ipynb` file!

# What python is this using?
`python3.7`
# So what did you find out?
The following figures suggest that for the iris dataset where there is a considerable amount of missing data distributed at random that an iterative imputer assists a logistic regressor to attain a higher $`F_1`$ score than an imputer that imputes with $`\mu`$ substitution.
### Single Experiment
![Single Experiment's results](graphs/exp1.png)

### Average $`F_1`$ scores over $`n=30`$ experiments
![Average over 30 Experiments' results](graphs/expavg30.png)
