# Decision-tree-post-pruning-
Pruning in decision trees is a technique used to prevent overfitting by reducing the complexity of the tree after it has been created. There are two main types of pruning:

Pre-Pruning (Early Stopping):
This method stops the tree from growing beyond a certain point during the construction phase. It involves setting limits, such as a minimum number of samples required to split a node, or a maximum tree depth. The tree is pruned as it's being built to avoid unnecessary complexity.

Post-Pruning (Cost-Complexity Pruning):
Post-pruning involves growing the tree fully first and then pruning it by removing nodes that provide little predictive power. This process usually involves evaluating subtrees and removing those that reduce the model's overall performance or lead to overfitting.

Code Implementation
This repository includes an implementation of both pre-pruning and post-pruning techniques. The decision tree can be pruned during the tree construction (pre-pruning) or after it has been fully grown (post-pruning). The implementation ensures that overfitting is minimized and the model generalizes better to unseen data.

