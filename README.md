# HospitalDeathPredictions

`preprocessor.py` file is responsible for preprocessing the given data

`model.py` and `requirnments.txt` with  `finding_the_model.py` are responsible for testing classification models mentioned below and selecting the best among tested ones.

1. KNN
2. Logistic Regression
3. Naive Bayes
4. LDA
5. QDA
6. SVM
7. Decision Tree
8. Random Forest
9. Adaboost
10. Gradient Boosting


In the `models.png` you can see the Accuracy, Sensitivity, Specificity and AUC scores for all the mentioned models. Out of them Gradient Boosting was taken as a main model in the file `model.py` because of high accuracy and less sensitivity score.

Lastly `our_predictions.json` ,`preprocessor.py`, `run_pipeline.py` files are responsible for running the pipeline and json file for the threshhold. 
