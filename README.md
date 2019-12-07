# Ensemble based approach for multi class image classification

The contents of this repo are as follows:

1. Images folder: contains images of result tables and confusion matrices of some of the experiments

2. Data folder:
	1. Data.zip 
		fashion_mnist_train.csv and fashion_mnist_test.csv are two large files zipped in this zip file.
	2. fold_acc_boruta_2.csv : Accuracies per fold by each model when cross validation is used on training data
	3. fold_pred_boruta_2.csv : Predictions of each model on each sample of the training data achieved through cross validation
	4. fold_boruta_pred_prob_1.csv : Predictions as probabilities of each model on each sample of the training data 
	5. val_pred_boruta_3.csv : Predictions of each model on the test data
	6. val_pred_prob_boruta_1.csv : Predictions as probabilities of each model on the test data
 	
3. Models folder: The random forest, knn and svm are big models and hence you will find them in zip files
Logistic regression, Naive Bayes and Decision Trees are lighter 

2. Fashion MNIST models (Boruta wrapper).ipynb
This python note book contains most of the code. Here is a list of sections within the notebook. 
	1. Data preprocessing
	2. Model Evaluation functions
	3. Training, cross validation and evaluation of base models
	4. Testing and training ensemble models on the tuned based models from previous section.
	5. Statistical Equivalence test for base learners

4. Fashion MNIST analysis.ipynb
The feature analysis was conducted in this notebook. These are the sections of the notebook.
	1. Data preprocessing
	2. Boruta Implementation (Wrapper based)
	3. Create code for the demo
	4. Correlation matrix evaluaton. (Filter based)
	5. Mutual Information (Filter based)


5. Demo.ipynb
This notebook is a simple demo code that was executed in the presentation. 
Simply run all cells of the notebook to see the final result.

6. demo.csv
CSV file with 10 samples from each class to run as a demo at the presentation
