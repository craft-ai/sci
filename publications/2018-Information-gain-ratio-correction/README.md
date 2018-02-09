# Information gain ratio correction: Improving prediction with more balanced decision tree splits (2018) #

[_official permalink_](https://arxiv.org/abs/1801.08310)

## Authors ##

- Matthieu Boussard, <matthieu@craft.ai>
- Antonin Leroux, <<antonin.leroux@polytechnique.edu>
- Rémi Dès, <remi@craft.ai>

## Abstract ##

Decision trees algorithms use a gain function to select the best split during the tree's induction. This function is crucial to obtain trees with high predictive accuracy. Some gain functions can suffer from a bias when it compares splits of different arities. Quinlan proposed a gain ratio in C4.5's information gain function to fix this bias. In this paper, we present an updated version of the gain ratio that performs better as it tries to fix the gain ratio's bias for unbalanced trees and some splits with low predictive interest.

Machine Learning, Decision trees, Split, Gain ratio
