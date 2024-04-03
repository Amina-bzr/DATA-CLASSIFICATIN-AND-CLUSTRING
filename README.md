# DATA-CLASSIFICATIN-AND-CLUSTRING

The notebook provided contains solutions to the following exercises:

#### Exercise 1

In this exercise, we explore the impact of decision tree depth on classifier accuracy using the `car.data` and `tic-tac-toe.data` datasets. 

- Varying `max_depth` from 3 to 10, we observe how it affects the accuracy of the DecisionTreeClassifier.
- Utilizing K-fold cross-validation (K=10), we compute the average accuracy for each `max_depth`.
- We analyze the relationships among dataset size (attributes and records), decision tree depth, and classifier accuracy, presenting our observations along with graphical representations for clarity.

#### Exercise 2

In Exercise 2, we investigate the relationship between training data size and classifier accuracy using the Decision Tree Classifier on `car.data` and `tic-tac-toe.data`.

- We train the classifier with varying sizes of training data: 10%, 25%, 33%, 50%, 66%, and 75% of the entire dataset.
- Employing the Random Sub-sampling method, we calculate the average accuracy for each training data size by repeating the process 10 times.
- Our analysis focuses on identifying patterns between training data size and classifier accuracy, supported by graphical representations for visualization.

#### Exercise 3

This exercise delves into understanding the four linkage methods (single, average, complete) in the Agglomerative Clustering method using dendrograms.

- We generate dendrograms to illustrate how each linkage method works.
- By explaining the process visually, we aim to elucidate the distinctions and characteristics of single, average, and complete linkage methods in Agglomerative Clustering.
