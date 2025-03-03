# Inferential Statistics

## Why do we need Inferential Statistics? 
- Correlation Vs. Causation
- Controlled Experiment
    - A/B Testing
    - Medical Trials

## Population
## Sample
### Why do we need sampling
### Sampling Distribution
- Probability distribution
- Area under the curve
- Gaussian distribution and Normal distribution
- Sampling Distribution of the Mean
- Central Limit Theorem (CLT)
    - [Online stats visualization](https://onlinestatbook.com/stat_sim/sampling_dist/)
    - If you take many samples from a population and calculate their averages, those averages will form a bell-shaped curve (normal distribution), even if the original data isn’t bell-shaped. This is useful because it lets us make predictions about the population.

## Hypothesis Testing
### Null Hypothesis
### Alternate Hypothesis
### P-value
### Significance Level (α)


## Z-test
A Z-test is used to compare means when the sample size is large $n>30$ and the population variance is known. It follows the standard normal distribution ($Z$-distribution).

$Z=\dfrac{\bar{x}-\mu}{\left(\frac{\sigma}{\sqrt{n}}\right)} \nonumber$

- $\bar{x}$ = sample mean
- $\mu$ = population mean
- $\sigma$ = population standard deviation
- $n$ = sample size

### [Z-Table](https://math.arizona.edu/~rsims/ma464/standardnormaltable.pdf)
- Finding p-value using Z-table

## T-test
## [T-Table](https://www.sjsu.edu/faculty/gerstman/StatPrimer/t-table.pdf)
### One Sample T-test
Compares the sample mean to a known population mean

$t=\dfrac{\bar{x}-\mu}{\left(\frac{s}{\sqrt{n}}\right)} \nonumber$

- $\bar{x}$ = sample mean
- $\mu$ = population mean
- $s$ = sample standard deviation
- $n$ = sample size

### Independent Sample T-test
- Compares means of two independent groups

### Paired Sample T-test
- Compares means from the same group at different times (before/after)

## F-Distribution