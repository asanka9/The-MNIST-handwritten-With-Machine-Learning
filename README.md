# The-MNIST-handwritten-With-Machine-Learning
<img src='https://machinelearningmastery.com/wp-content/uploads/2019/02/Plot-of-a-Subset-of-Images-from-the-MNIST-Dataset-1024x768.png' width='500px' >
<br>
## METHODOLOGY 
<br>
1) Data processing : <br>
Here we check whether NaN Value Contain or not and check whether 
the data set balanced or not
<br>
2) Determine most suitable algorithm ( algorithm_selection.ipynb ) : <br>
Here KNN, SVM, Random Forest, Logistic Regression algorithms were used to select 
the most suitable algorithm for this data set.
KNN and SVM were selected as the best algorithms to be tested with training data 
and testing data, from which the training time was compared and KNN was selected 
for the train.
Limitation: Here this takes a lot of computation power, therefore we use the sample 
of data set from the population to select the best algorithm <br>
3) Develop model using selected algorithm (model_train.ipynb) : <br>
First determine suitable K value :
The training was done using k = 1 and approximately 97% accuracy 
was obtained
