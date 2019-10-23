# Data Science Projects 
### by Soo Hyeon Kim
---

### 1. [Iris Dataset Analysis](https://github.com/soo-pecialist/DS_Projects/blob/master/Iris_Dataset_Analysis.ipynb) 
 (Date: Sep. 30, 2019)

The Iris data has 150 samples, 4 attributes, and 3 species (target) and they are confusing to distinguish with the naked eye. The goal is to predict the class of the flower as accurately as possible and Linear Discriminant Analysis(LDA) model, achieved 97.4% of accuracy on test set and only suffered 0.5% variance from training set. 

### 2. [Loan Prediction Analysis](https://github.com/soo-pecialist/DS_Projects/blob/master/Loan_Prediction_Analysis.ipynb)
 (Date: Oct. 5, 2019)
 
This project is to answer "should this loan be approved or denied?". From a company's perspective, you want to minimize the risk of not getting money back and of losing possible customers. 
The data had only 614 examples and the model was only trained on 591 examples. The data consisted of more categorical features than numerical thus through data transformation, data became sparse and it turned out data points were jumbled together regardless of its class and therefore it is hard to find the decision boundary. 
Extreme Gradient Boost (XGB) and SVM models achieved 0.83 of mean average precision and 0.85 of accuracy equally. With confusion matrix, the model clearly did excellent job in filtering out False Negatives reducing the risk of losing customers, but did relatively poorly in filtering out False Positives. 

### 3. [New York City Airbnb Price Prediction](https://github.com/soo-pecialist/DS_Projects/blob/master/NY_AirBnB.ipynb)
  (Date: Oct. 17, 2019)

This project aims at providing "smart pricing" for New York City Airbnbs. The data is composed of 48,895 rows and 16 columns. The optimal model achieves 95% coverage with $36.07 MAE (Mean Absolute Error). The reason the model could not achieve 100% coverage originates from the fact that high pricing airbnbs are rare and therefore not many training models provided for the model to be trained on. For predicted values above 95 percentile training price $350 should be examined by human experts. 

### 4. [Monthly Sunspot Numbers Prediction](https://github.com/soo-pecialist/DS_Projects/blob/master/Sunspot.ipynb)
  (Date: Oct. 23, 2019)

Predictions of sunspot number are also very important in planning space-related activities particularly for low Earth orbiting spacecraft. This project predicts monthly sunspot numbers. The data is composed of the observations over 18 years (2001 - 2018) from Australia. The CRNN (Convolutional Recurrent Neural Network) predicts the number of sunspot with 1.78 MAE (mean absolute error). 
