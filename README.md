# Calculator - Computing Statistics from Aggregate Measures

👉 [Try the calculator here](https://wfranceys.github.io/pairwise-sample-variance/)

### What is this for?

Given a summary table from a study, how do you calculate the combined mean age with standard deviation across the groups?

| Diagnosis | n  | Mean age    |
|-----------|----|-------------|
| A         | 62 | 43.9 ± 15.3 |
| B         | 11 | 46.3 ± 13.8 |
| C         | 12 | 40.7 ± 14.6 |

Follows algorithm by [Chan, Tony F.; Golub, Gene H.; LeVeque, Randall J. (1979), "Updating Formulae and a Pairwise Algorithm for Computing Sample Variances." (PDF), Technical Report STAN-CS-79-773, Department of Computer Science, Stanford University.](http://i.stanford.edu/pub/cstr/reports/cs/tr/79/773/CS-TR-79-773.pdf) and credits to previous implementation [here](https://github.com/himbeles/pairwise-statistics/tree/main).

Created as a proof of concept to help calculate aggregate statistics in meta studies.

### Website

![alt text](example.png "homepage")