
A dataset related to cars was provided, divided into train and test sections. In this project, we created a decision tree that classifies the training data based on car models. We then used the test data to evaluate the model's performance. The decision tree created adhered to the concepts taught in class.

**Phase One**

The dataset included some missing data. We handled this issue using the methods discussed in class. We reviewed and analyzed the results of each method and compared them. For loading and processing the data, we used the Pandas library.

**Phase Two**

As studied in class, we used the ID3 algorithm to construct the decision tree. Using this algorithm, we created an appropriate decision tree by calculating Entropy and Information Gain at each stage to select the suitable attribute. We implemented the Node class and also manually implemented the Entropy and Information Gain functions. In this phase, we examined and reported the following:
- The process of tree formation and feature selection.
- Our solution for continuous features, explaining how we determined the optimal threshold for discretizing these features.
- When Entropy and Information Gain reached their maximum values.

**Phase Three**

We examined the issue of overfitting in decision trees, identifying when this problem occurs. We reviewed at least two solutions to address this issue (implementation was not required).

**Phase Four**

Finally, we visualized the constructed decision tree (similar to Figure 1). In each node of the tree, we included the name of the attributes, Entropy, and the corresponding Information Gain. For this purpose, we used libraries such as Graphviz, Plotly, or similar tools.

---
