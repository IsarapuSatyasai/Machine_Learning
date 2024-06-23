# Classification on Imbalanced Data using Python
In Machine Learning, imbalanced data refers to a situation in classification problems where the number of observations in each class significantly differs. In such datasets, one class (the majority class) vastly outnumbers the other class (the minority class). This imbalance can lead to biased models that favour the majority class, resulting in poor predictive performance on the minority class, which is often the class of greater interest. In this project, I’ll take you through the task of performing classification on imbalanced data using Python.

## Process:
1. Start by examining the class distribution in your dataset to gauge the level of imbalance.
2. Assess the significance of each class relative to your specific problem.
3.  Augment the minority class by replicating instances to achieve a balanced class distribution.
4.  Consider algorithms that are less affected by class imbalance, such as tree-based methods or ensemble techniques like Random Forest or Gradient Boosted Trees.
5.  Use evaluation metrics that are more appropriate for imbalanced datasets, such as Precision, Recall, F1 Score, or the Area Under the Receiver Operating   
Characteristic (AUROC) curve, rather than relying solely on accuracy.
## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/IsarapuSatyasai/machine_learning.git
```

2. Go to imbalanaced data project directory

```bash
   cd imbalanced_data
```

3. Install the requirements using requirement text file.
```bash
   pip install -r requirements.txt
```

4. Finally, open and run the notebook using jupyter notebook.
