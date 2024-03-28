Decision Tree Classifier for Mushroom Classification

This project implements a Decision Tree classifier from scratch in Python, applied to the task of classifying mushrooms as either edible or poisonous. The implementation is a practical exercise designed to deepen understanding of Decision Tree algorithms and their application in classification problems.

Project Overview
The aim of this project is to use physical attributes of mushrooms to classify them as either edible or poisonous. The implementation is done from scratch, including functions for entropy calculation, dataset splitting, information gain calculation, and the best split identification, culminating in the construction of a Decision Tree classifier.

Table of Contents
Installation
Dataset
Usage
Implementation Details
Entropy Calculation
Dataset Splitting
Information Gain Calculation
Identifying the Best Split
Building the Decision Tree
Contributing
License
Installation
Clone the repository to your local machine:

bash
git clone https://github.com/your-github-username/mushroom-decision-tree.git
cd mushroom-decision-tree
Ensure you have Python installed on your system. The code is compatible with Python 3.7 and above. You can install the dependencies using:

pip install -r requirements.txt
Dataset
The dataset used in this project consists of examples of mushrooms with attributes such as cap color, stalk shape, and whether the mushroom grows in solitude. Each instance is labeled as either edible (1) or poisonous (0).

Usage
To run the Decision Tree classifier on the mushroom dataset:

python decision_tree.py
Implementation Details
Entropy Calculation
Calculates the entropy at a node, providing a measure of impurity based on the classification of edible or poisonous.

Dataset Splitting
Splits the dataset into left and right branches based on a given feature, facilitating the recursive construction of the tree.

Information Gain Calculation
Calculates the information gain from a potential split, guiding the selection of the feature that provides the most significant reduction in uncertainty.

Identifying the Best Split
Determines the best feature to split on by comparing the information gain across all features.

Building the Decision Tree
Utilizes the above functions to recursively build a Decision Tree to the specified depth, beginning with the root node containing all data instances.

Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests. For major changes or questions, please open an issue first to discuss your proposal.
# ml_lab4
