# Diabetes-Prediction-Using-Machine-Learning


Diabetes is an illness caused because of high glucose level in a human body. Diabetes should not be ignored if it is untreated then Diabetes may cause some major issues in a person like: heart related problems, kidney problem, blood pressure, eye damage and it can also affects other organs of human body. Diabetes can be controlled if it is predicted earlier. To achieve this goal this project work we will do early prediction of Diabetes in a human body or a patient for a higher accuracy through applying, Various Machine Learning Techniques. Machine learning techniques Provide better result for prediction by con- structing models from datasets collected from patients. In this work we will use Machine Learning Classification and ensemble techniques on a dataset to predict diabetes. Which are K-Nearest Neighbor (KNN), Logistic Regression (LR). The accuracy of model is noted . The Project work gives the accurate or higher accuracy model shows that the model is capable of predicting diabetes effectively. 

![image](https://user-images.githubusercontent.com/103196322/164281832-82b55887-6482-4dfe-b412-8f2ad8bc3cb5.png)


Dataset Description- the data is gathered from UCI repository which is named as Pima Indian Diabetes Da- taset. The dataset have many attributes of 768 patients.

Data Preprocessing- 

Data preprocessing is most im- portant process. Mostly healthcare related data contains missing vale and other impurities that can cause effective- ness of data. To improve quality and effectiveness obtained after mining process, Data preprocessing is done. To use Machine Learning Techniques on the dataset effectively ths process is essential for accurate result and successful prediction. For Pima Indian diabetes dataset we need to perform pre processing in two steps.

Missing Values removal- Remove all the instances that have zero (0) as worth. Having zero as worth is not possi- ble. Therefore this instance is eliminated. Through elimi- nating irrelevant features/instances we make feature subset and this process is called features subset selection, which reduces diamentonality of data and help to work faster.

Splitting of data- After cleaning the data, data is nor- malized in training and testing the model. When data is spitted then we train algorithm on the training data set and keep test data set aside. This training process will produce the training model based on logic and algorithms and val- ues of the feature in training data. Basically aim of normal- ization is to bring all the attributes under same scale.

Apply Machine Learning- When data has been ready we apply Machine Learning Technique. We use different classification and ensemble techniques, to predict diabetes. The methods applied on Pima Indians diabetes dataset. Main objective to apply Machine Learning Techniques to analyze the performance of these methods and find accura- cy of them, and also been able to figure out the responsi- ble/important feature which play a major role in prediction.

Logistic Regression- Logistic regression is also a su- pervised learning classification algorithm. It is used to es- timate the probability of a binary response based on one or more predictors. They can be continuous or discrete. Lo- gistic regression used when we want to classify or distin- guish some data items into categories.

It classify the data in binary form means only in 0 and 1 which refer case to classify patient that is positive or nega- tive for diabetes.

MODEL BUILDING

This is most important phase which includes model build- ing for prediction of diabetes. In this we have implemented various machine learning algorithms which are discussed above for diabetes prediction.

Procedure of Proposed Methodology-

Step1: Import required libraries, Import diabetes dataset.

Step2: Pre-process data to remove missing data.

Step3: Perform percentage split of 80% to divide dataset as Training set and 20% to Test set.

Step4: Select the machine learning algorithm i.e. K- Nearest Neighbor, Support Vector Machine, Decision Tree, Logistic regression, Random Forest and Gradient boosting algorithm.

Step5: Build the classifier model for the mentioned ma- chine learning algorithm based on training set.

Step6: Test the Classifier model for the mentioned ma- chine learning algorithm based on test set.

Step7: Perform Comparison Evaluation of the experi- mental performance results obtained for each classifier.

Step8: After analyzing based on various measures con- clude the best performing algorithm.

REFERENCES

Debadri Dutta, Debpriyo Paul, Parthajeet Ghosh, "Analyzing Feature Importances for Diabetes Prediction using Machine Learning". IEEE, pp 942-928, 2018.

Tejas N. Joshi, Prof. Pramila M. Chawan, "Diabetes Prediction Using Machine Learning Techniques".Int. Journal of Engineer- ing Research and Application, Vol. 8, Issue 1, (Part -II) Janu- ary 2018, pp.-09-13
