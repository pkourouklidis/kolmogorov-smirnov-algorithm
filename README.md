# Kolmogorov-Smirnov statistical test
This algorithm implements the [two-sample Kolmogorov-Smirnov test](https://en.wikipedia.org/wiki/Kolmogorov%E2%80%93Smirnov_test#Two-sample_Kolmogorov%E2%80%93Smirnov_test) between the first columns in the trainSet and liveSet input arguments to see if they are drawn from the same distribution.

## Parameters
- **pValue**: The p-value to be used with the statistical test. If not provided 0.05 will be used by default.