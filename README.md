# rbf-neuralnetwork

*Files Explanation*
1. Research Codes.ipynb contains complete Python codes of all experiments explained in Research Report.pdf.
2. Research Report.pdf contains complete explanation of experiments.

*Project Description*
The experiment of putting different amount of data into Radial Basis Function Neural Network (RBF NN) in Python. The dataset used is Limit Order Book (LOB) Data.
RBF FF is an artificial neural network that uses radial basis functions as activation functions.

The RBF NN model's performance was found to be sensitive to the amount of training data and the inclusion of certain features.
When trained with a limited subset of the data, the model demonstrated a high RMSE, suggesting inadequate predictive capability.

However, as the training dataset size increased, the model's predictive performance improved significantly, demonstrating the importance
of large datasets in training complex models.
In terms of feature engineering, the introduction of bid-ask spread features exhibited mixed results. 
While mean performance decreased, the median performance improved. This pattern hints at the model's varying performance across different 
folds and points to the need for further exploration and refinement of these features.

Feature selection using a variance threshold and PCA helped reduce data dimensionality.
While PCA improved the model's performance in the classification task, its application in the
regression task saw a decrease in performance. This reflects the inherent trade-offs when
employing PCA: while it aids in dimensionality reduction, it may not always preserve the
essential information for every task.
