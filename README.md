# association-coefficients

Association coefficients measure the strength of a relationship. “Association” means that the variables have shared or common elements or some degree of agreement.

A large number of different association coefficients is available. Which you choose is dependent on many factors, including the data type (e.g. Kendall’s Tau for ranked nominal variables or Yule’s Y for binary variables). That said, a coefficient of association is independent of its measurement scale.

These coefficients typically range between 0 and 1, where 0 is no relationship and 1 is a perfect relationship. However, some measures of association range from -1 to 1, where -1 indicates a perfect inverse relationship.

Interestingly, the produced distance matrix can then be used as an input into an agglomerative clustering which is very useful for understanding overall structure and groups within a dataset

The provided notebook provides functions for calculating these coefficients. Depending on your data, certain coefficients can 'work best'
