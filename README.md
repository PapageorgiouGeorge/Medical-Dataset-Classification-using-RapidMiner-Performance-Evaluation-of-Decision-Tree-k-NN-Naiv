# Medical-Dataset-Classification-using-RapidMiner-Performance-Evaluation-of-Decision-Tree-k-NN-Naiv
This project focuses on classifying two datasets, Haberman's Survival and Pima Indians Diabetes, using RapidMiner. The classification is performed using four algorithms: Decision Tree, k-NN, Naive Bayes, and LibSVM. The datasets are imported and preprocessed in RapidMiner, and 10-fold cross-validation is performed for each algorithm.


Methodology:

Created a new repository in RapidMiner with two subfolders for Data and Processes.
Imported the datasets to the repository and set appropriate labels.
Implemented a pattern of processes for each dataset using each algorithm:
a. Added a 10-fold Cross Validation node.
b. In the Training panel, used the desired algorithm.
c. In the Testing panel, applied the model and recorded the performance metrics.
d. Recorded the execution time of Cross Validation.


Findings:

Pima Indians Diabetes:

Naive Bayes performed best with an accuracy of 74.22% +/- 5.82% and weighted mean of precision of 72.97% +/- 7.33%.
Linear Regression outperformed the other algorithms with an accuracy of 77.08% +/- 4.45%.
Haberman's Survival:

Decision Tree performed best with an accuracy of 77.13% +/- 3.38% and weighted mean of precision of 70.52% +/- 15.09%.


Insights:

For the Pima Indians Diabetes dataset, Naive Bayes and Decision Tree were suitable algorithms, with Naive Bayes having slightly better results.
Linear Regression was found to be an even better algorithm for classifying the Pima Indians Diabetes dataset based on accuracy and other metrics.
In the case of the Haberman's Survival dataset, the Decision Tree was the best algorithm for classification.
