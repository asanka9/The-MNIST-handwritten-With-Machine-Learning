# The-MNIST-handwritten-With-Machine-Learning
METHODOLOGY 
1) Data processing
Here we check whether NaN Value Contain or not and check whether 
the data set balanced or not
2) Determine most suitable algorithm ( algorithm_selection.ipynb )
Here KNN, SVM, Random Forest, Logistic Regression algorithms were used to select 
the most suitable algorithm for this data set.
KNN and SVM were selected as the best algorithms to be tested with training data 
and testing data, from which the training time was compared and KNN was selected 
for the train.
Limitation: Here this takes a lot of computation power, therefore we use the sample 
of data set from the population to select the best algorithm3
3) Develop model using selected algorithm (model_train.ipynb)
First determine suitable K value :
The training was done using k = 1 and approximately 97% accuracy 
was obtained4
