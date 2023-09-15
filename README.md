# Decision_Tree_with_Markdown


**Decision Tree:** 

In this assignment, I've build a decision tree based on the dataset provided.

- steps for building a decision tree are as follows:
    - Start with all examples at the root node
    - Calculate information gain for splitting on all possible features, and pick the one with the highest information gain
    - Split dataset according to the selected feature, and create left and right branches of the tree
    - Keep repeating splitting process until stopping criteria is met
  
  
- I'll implement the following functions, which will let you split a node into left and right branches using the feature with the highest information gain
    - Calculate the entropy at a node 
    - Split the dataset at a node into left and right branches based on a given feature
    - Calculate the information gain from splitting on a given feature
    - Choose the feature that maximizes information gain
    
- Use the helper functions I've implemented to build a decision tree by repeating the splitting process until the stopping criteria is met 
    - For this the stopping criteria we've chosen is setting a maximum depth of 2
