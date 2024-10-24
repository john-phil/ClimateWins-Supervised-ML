# ClimateWins: Supervised Machine Learning Project
## Project Description: Using various supervised machine learning models to assess ability to predict "pleasant weather days" in various cities across Europe using historical weather data from those areas.
### Used Python and various libraries (including pandas, numpy, seaborn, matplotlib, sklearn, and others) to run several iterations three different algorithms.
- K-Nearest Neighbors (KNN)
  - Adjusted the number of neighbors, trying models with 3,4,6 and 10 neighbors.
  - Attempted other techniques like undersampling and distance-based weighting.
  - Assessed model performance through examination of mutliabel confusion matrices and various performance metrics, including overall accuracy, recall, precision, and F1-scores.
  - Arrived at test accuracies that never went beyond 45%. 
- Decision Trees
  - Ran mdoels without pruning and then using a pre-pruning technique.
  - Attempted other techniques such as class weighting and Synthetic Minority Oversampling Technique (SMOTE)
  - Assessed model performance through examination of mutliabel confusion matrices and various performance metrics, including overall accuracy, recall, precision, and F1-scores.
  - Arrived at a test accuracy of 93% using the pre-pruning technique, however at the cost of class imbalance. 
- Artificial Neural Networks (ANNs)
  - Adjusted various hyperparameters including simple to complex layer architecture; the number of iterations, learning rate, tolerance, and alpha regularization.
  - Assessed model performance through examination of mutliabel confusion matrices and various performance metrics, including overall accuracy, recall, precision, and F1-scores.
  - Came to the best test accuracy of 64% after utilizing a simpler layer architecture (50,50); 500 iterations, and a tolerance of 0.0001.
  - Once again, this model demonstrated significant issues with class imbalance, working better for the well-represented weather stations, and much less so for the underrepresented ones.
### Utilized Gradient Descent Optimization (GDO) to Improve the Efficiency of the Models. 
