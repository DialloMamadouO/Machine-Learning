# Machine-Learning
This exercise consiste of analyzing credit risk on one part using different resampling techniques and on the other part using ensemble techniques. On the first part we will use
oversampling, undersampling and a combination (Over and Under) sampling techniques to see which model does a better job predicting credit risk. On the second part we will do the same using different ensemble techniques to see which model does a better job predicting credit risk as well. The recoreds for the analysis are on the ipynb files.

RESAMPLING TECHNIQUES:

Which model had the best balanced accuracy score?
In this exercise we have used 4 models: Naive Rondom Oversampling, SMOTE Oversampling, Undersampling and Combination(Over and Under) Sampling.
The SMOTE Oversampling model produced the best balanced accuracy score at 0.8388510243681058 followed closely by the Combination (Over and Under)
Sampling at 0.8388319216626994 and the Naive Random Oversampling at 0.8325468421491353. The Undersampling model comes last at 0.8215575767118339
however it is important to note that all the balanced accuracy score values are very close. 

 Which model had the best recall score?
 The SMOTE Oversampling model produced the best average recall score at 0.87 it is followed by the Naive Random Oversampling model at 0.84 and
both the Undersampling and the Combination (Over and Under) Sampling models have the same recall score at 0.76. The SMOTE Oversampling model
has lower false negatives than every other model. 

Which model had the best geometric mean score?
The SMOTE Oversampling model had the best geometric mean score at 0.84 folowed by the Naive Random Oversampling at 0.83 and the two other models
had the same geometric mean score at 0.82. The SMOTE Oversampling model had the overall best scores.

ENSEMBLE TECHNIQUES:
In this part of the exercise, we have used 2 models: Balanced Random Forest Classifier model and the Easy Ensemble Classifier model.

Which model had the best balanced accuracy score?
The Easy Ensemble Classifier had the best balanced accuracy score at 0.931601605553446 it has a lower false negatives on average per class than 
the balanced random forest classifer which is at 0.7887512850910909.

 Which model had the best recall score?
The Easy Ensemble Classifier had the best recall score at 0.94 compared to 0.87 for the balanced random forest classifier. Again the Easy 
Ensemble Classifier has lower false negatives than the balanced random forest classifier.

Which model had the best geometric mean score?
The Easy Ensemble Classifier model had the best geometric mean score at 0.93 compared to 0.78 Balanced Random Forest Classifier. The Easy Ensemble Classifier model had the overall best scores on this part of the analysis.

What are the top three features?  
According to the features importances classification on the ipynb file the top three features are:
    
    0.07876809003486353, total_rec_prncp,
    0.05883806887524815, total_pymnt,
    0.05625613759225244, total_pymnt_inv

      


